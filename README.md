🌐 **Language:** English (this document)

# RTL Loan Sizer & Pricer — Catch the Error Before It Reaches Closing

![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Excel%20%7C%20Web-2251FF.svg)
![Type](https://img.shields.io/badge/type-Decision%20Support%20Tool-051C2C.svg)

**Cross-checks every RTL deal against three leverage caps and a margin floor at once — so a clean-looking single metric never closes a deal that fails on the other two.**

**[Live Demo](./RTL_Loan_Sizer_Pricer_App.html)** · **[Download the Workbook](./RTL_Loan_Sizer_Pricer.xlsx)** · **[Methodology](#workbook-logic-for-the-skeptical-reviewer)**

![RTL Loan Sizer — Quote Summary view](./assets/hero-quote-summary.png)
*(Placeholder — replace with a screenshot of the Quote Summary tab before publishing.)*

---

## What Decision Does This Help You Make?

1. Does this deal clear every leverage cap — LTV, LTC, and LTARV — or does it only look acceptable on the one metric someone happened to check first?
2. Is the proposed note rate still above the minimum spread floor once the FICO/LTV-tier buy rate is applied, or has margin already compressed below the line?
3. After short interest and the servicing fee reserve are deducted, does net funding actually cover the cash-to-close requirement — or is there a liquidity shortfall hiding behind the gross loan amount?
4. Which single constraint is actually binding the deal, and how far is it from triggering an exception?

---

## About The Builder

Three positions shape the workbook. Decision support over system replacement: it answers one underwriting question correctly, not a replacement for origination software. Productized reasoning over feature accumulation: every cell supports a gate the deal genuinely depends on, not a demonstration of spreadsheet skill. Low-friction execution over implementation complexity: no macros, no database, no IT ticket. An originator opens the file, enters the deal, and gets a gated answer before the call ends.

---

## Who This Is For

| User | Typical Situation | Decision Supported | Why Existing Methods Fail |
|---|---|---|---|
| RTL Loan Originator | Quoting a Fix-and-Flip or Light Rehab deal against a verbal rate sheet | Quote, decline, or flag for exception before submission | Mental math checks one leverage ratio and skips the other two |
| Underwriting Manager | Reviewing a submitted file against caps and the margin floor | Whether the file clears every cap at once, not just the obvious one | Spreadsheets recalculate LTV but rarely cross-check LTC and LTARV together |
| Mortgage Broker (Bridge / Rehab Referrals) | Pre-qualifying a borrower before sending the file to a lender | Whether the deal is fundable as structured | Broker tools price the loan but don't model the lender's spread floor |
| Capital Markets Analyst | Pricing a warehouse line draw or a loan-for-sale package | Whether booked spread on a closed loan still clears the minimum margin | Loan-level spread is recalculated post-close, after the error has shipped |

---

## Why Most RTL Underwriting Errors Aren't Judgment Errors

The error rarely starts with bad judgment. It starts with a process that checks one number and stops. An originator pulls As-Is Value, divides it into the loan amount, gets a clean LTV, and moves on. Total project cost — purchase price plus rehab budget — sits in a different cell, checked separately, sometimes not at all. Three leverage ratios exist because one ratio can pass while another fails on the same deal. A process that checks them in sequence, rather than as a single gate, will eventually let a Fail through disguised as a Pass.

The same gap shows up in pricing. Note rate gets compared to a target spread remembered from the last rate sheet update, not the spread floor on the current one. Buy rate is a lookup against FICO and LTV tiers, not a fixed number — a borrower one tier worse on either axis prices materially higher, and the spread compresses without anyone recalculating it.

Verification closes the gap by replacing sequential checks with a single gate:

```
BEFORE                            AFTER
Check LTV   → looks fine          Compute LTV, LTC, LTARV, Spread together
Check LTC   → skipped             → Fail if ANY metric fails
Decide: approve                   → Exception if ANY metric is within 5 pts of cap
                                   → Pass only if ALL metrics clear
```

Operationally, this means the deal that gets quoted is the deal that was actually checked — not the deal that was checked fastest.

---

## Three Traps That Catch Even Experienced Underwriters

### Trap 1 — The Single-Metric Pass

**The decision:** An originator reviews a Light Rehab submission, checks LTV at 69.2% against an 80% cap, and verbally approves the deal pending paperwork.

**The unnoticed flaw:** Total project cost — purchase price plus rehab budget — was never checked against the loan amount. LTC, the second leverage gate, was sitting at 93.75% against a 90% cap.

**How the flaw changes the recommendation:** A deal comfortably inside one cap is breaching another by 3.75 points. The correct call is decline-or-restructure, not approve.

**Why the reasoning was wrong:** LTV measures collateral coverage against current value. It says nothing about how much of the total cost basis the loan is funding. A loan can be conservative against value and aggressive against cost basis at the same time — independent constraints, not proxies for each other.

**Corrected approach:** Compute LTV, LTC, and LTARV from the same inputs and require a Pass across all three before recommending approval.

**Corrected outcome:** Global Eligibility returns Fail. The deal is restructured — loan amount reduced or rehab budget re-scoped — before it reaches a credit committee.

| Metric | Actual | Cap | Flag |
|---|---|---|---|
| LTV | 69.2% | 80% | Pass |
| LTC | 93.75% | 90% | **Fail** |
| Global Eligibility | — | — | **Fail** |

<details>
<summary>Formulas</summary>

```
Actual_LTV = Loan_Amount / As_Is_Value
Actual_LTC = Loan_Amount / (Purchase_Price + Rehab_Budget)
Flag       = "Fail" if Actual > Cap
           = "Exception" if Actual >= Cap - 0.05
           = "Pass" otherwise
Global_Eligibility = "Fail" if ANY flag = "Fail"
```
</details>

### Trap 2 — The Stale Buy-Rate Trap

**The decision:** A Heavy Rehab deal is quoted at a 10.75% note rate. The originator recalls the desk's target margin as roughly 2 points and treats the deal as priced correctly.

**The unnoticed flaw:** Buy rate is not a fixed number. It is looked up against the borrower's FICO tier and the deal's actual LTV tier, and that lookup returned 9.75% — not the lower buy rate the originator was picturing from a prior, better-leveraged file.

**How the flaw changes the recommendation:** Spread is 10.75% minus 9.75%, or 1.00 point — less than half the desk's 2.50-point minimum floor.

**Why the reasoning was wrong:** Margin was estimated from memory of a typical spread, not recalculated from the actual FICO/LTV-tier intersection on this file. Buy rate moves with leverage; assuming it stayed flat is the error.

**Corrected approach:** Recompute spread from the actual tier lookup whenever loan amount, FICO, or As-Is Value changes — never carry a margin assumption across deals.

**Corrected outcome:** Spread Status returns Below Margin with a 1.50-point deficit. The desk raises the note rate or declines the file before committing terms to the borrower.

| | Assumed | Actual |
|---|---|---|
| Buy Rate | ~8.75% (recalled) | 9.75% (tier lookup) |
| Spread | ~2.00% | 1.00% |
| Status | Looks fine | **Below Margin (-1.50 pts)** |

<details>
<summary>Formulas</summary>

```
FICO_Tier = largest tier in {620,640,660,680,700,720,740} <= Borrower_FICO
LTV_Tier  = largest tier in {50%,55%,...,80%}             <= Actual_LTV
Buy_Rate  = Grid[FICO_Tier][LTV_Tier]
Spread    = Note_Rate - Buy_Rate
Status    = "Below Margin" if Spread < Min_Spread_Floor else "Valid"
```
</details>

### Trap 3 — The Gross-vs-Net Funding Trap

**The decision:** A $600,000 Construction loan against a $630,000 total project cost looks $30,000 short at closing. The borrower has $25,000 verified liquid — close enough, the file moves forward.

**The unnoticed flaw:** The $30,000 gap was calculated against the gross loan amount. It ignores two deductions that happen before any dollar reaches the borrower: prepaid short interest and the servicing fee reserve.

**How the flaw changes the recommendation:** Short interest on this file is $4,000 (20 days at a 12% note rate). The servicing fee reserve is $2,250 over an 18-month term. Net funding is $593,750 — not $600,000.

**Why the reasoning was wrong:** Cash-to-close is a function of net funding, not gross loan amount. Treating the two as interchangeable understates the real gap by exactly the amount of the deductions.

**Corrected approach:** Compute net funding first — gross loan amount minus short interest minus the servicing fee reserve — then compare that figure, not the gross amount, to total project cost.

**Corrected outcome:** Cash-to-close is actually $36,250. Against $25,000 in verified liquidity, the real shortfall is $11,250 — more than double what the gross-amount math suggested.

| | Gross-Amount Math | Net-Funding Math |
|---|---|---|
| Funding figure used | $600,000 | $593,750 |
| Cash-to-Close | $30,000 | **$36,250** |
| Shortfall vs. $25,000 liquid | $5,000 | **$11,250** |

<details>
<summary>Formulas</summary>

```
Short_Interest  = Loan_Amount * (Note_Rate / 360) * Short_Interest_Days
Servicing_Fee   = Loan_Amount * (Annual_Fee_Pct / 12) * Term_Months
Net_Funding     = Loan_Amount - Short_Interest - Servicing_Fee
Cash_To_Close   = MAX(0, Total_Project_Cost - Net_Funding)
Liquidity_Gap   = MAX(0, Cash_To_Close - Verified_Liquid_Assets)
```
</details>

---

## Example Scenario

A Fix-and-Flip deal arrives: $350,000 purchase price, $380,000 as-is value, $65,000 rehab budget, $520,000 ARV. The borrower requests $340,000 at an 11.50% note rate, carries a 690 FICO, three to five completed projects, $45,000 in verified liquid assets, a 12-month term, and 15 days of prepaid short interest.

Leverage runs first. LTV is 340,000 / 380,000 = 89.47% against a 90% cap — inside the line but past the 85% exception threshold. LTC is 340,000 / 415,000 = 81.93% against an 85% cap — same exception pattern. LTARV is 340,000 / 520,000 = 65.38% against a 70% cap, again inside the 65-point exception band. No single metric fails outright. All three sit in the same narrow exception zone — exactly the pattern a metric-by-metric review misses and a global gate catches: Global Eligibility returns Exception Needed, not Pass.

Pricing runs next. FICO 690 and LTV 89.47% resolve to the 680 / 80% tier on the grid: an 11.25% buy rate. Spread is 11.50% minus 11.25%, or 0.25 points, against a 2.50-point minimum floor. Status returns Below Margin, with a 2.25-point deficit.

Settlement runs last. Servicing fee reserve is $850. Short interest on 15 days at 11.50% is $1,629. Net funding is $337,521. Total project cost is $415,000, putting cash-to-close at $77,479. Against $45,000 in verified liquidity, the shortfall is $32,479.

**Recommendation:** this deal does not close as structured. Three leverage metrics simultaneously sitting in the exception band, a spread under 10% of the required floor, and a $32,479 liquidity gap are three independent reasons to renegotiate terms — not one originator's judgment call to override.

---

## What The Workbook Actually Delivers (Not How It Calculates)

- A single Pass / Exception Needed / Fail answer that requires all three leverage caps to clear at once — never a partial check.
- A live spread calculation against the actual FICO/LTV-tier buy rate, not a remembered margin target.
- A net-funding-based cash-to-close figure that already accounts for short interest and the servicing fee reserve.
- A liquidity shortfall figure compared against verified borrower assets, not an estimate.
- A client-safe quote view that never exposes buy rate, spread, or lender profit to anyone outside the desk.
- The same gated answer whether the deal is entered once or re-run ten times — no manual recalculation steps to skip.

---

## Workbook Logic (For the Skeptical Reviewer)

Five layers, each reading only from the layer above it.

```
Guide         → no calculations, documentation only
Inputs        → single point of data entry, no formulas
Pricing       → leverage caps, spread floor, buy-rate grid (admin-editable)
Calc Engine   → every leverage, eligibility, pricing, and settlement formula
Quote Summary → formula links into Calc Engine only — zero hardcoded values
```

Data flows one direction. Inputs never read from Calc Engine. Quote Summary never reads from Inputs or Pricing directly — every figure on the client-facing view references Calc Engine, so the number an underwriter sees and the number a borrower sees cannot drift apart.

Validation runs in two passes. The first computes the three leverage ratios and assigns a Pass / Exception / Fail flag to each, independently. The second collapses those flags into one Global Eligibility value — Fail dominates Exception, Exception dominates Pass. Pricing runs in parallel: a tier lookup resolves buy rate, spread is computed against it, and checked against the floor.

Output dependency is intentionally narrow. Buy rate, spread, and lender profit exist only inside Calc Engine and are never referenced anywhere in Quote Summary's formulas — the privacy boundary is structural, not a formatting choice.

---

## Implementation Notes (For Those Who Want to Look Under the Hood)

<details>
<summary>Leverage and eligibility formulas</summary>

```
Actual_LTV   = IF(As_Is_Value=0, 0, Loan_Amount / As_Is_Value)
Actual_LTC   = IF((Purchase+Rehab)=0, 0, Loan_Amount / (Purchase+Rehab))
Actual_LTARV = IF(ARV=0, 0, Loan_Amount / ARV)
Flag(x, cap) = IF(cap=NULL OR x=0, "N/A",
               IF(x > cap, "Fail",
               IF(x >= cap-0.05, "Exception", "Pass")))
Global_Eligibility = IF(ANY flag="Fail", "Fail",
                     IF(ANY flag="Exception", "Exception Needed", "Pass"))
```
</details>

<details>
<summary>Pricing and settlement formulas</summary>

```
Buy_Rate       = INDEX(Grid, MATCH(FICO, FICO_Tiers, 1), MATCH(LTV, LTV_Tiers, 1))
Spread         = Note_Rate - Buy_Rate
Spread_Status  = IF(Spread < Min_Spread_Floor, "Below Margin", "Valid")
Servicing_Fee  = Loan_Amount * (Annual_Fee_Pct/12) * Term_Months
Short_Interest = Loan_Amount * (Note_Rate/360) * Short_Interest_Days
Net_Funding    = Loan_Amount - Short_Interest - Servicing_Fee
Cash_To_Close  = MAX(0, Total_Project_Cost - Net_Funding)
Liquidity_Gap  = MAX(0, Cash_To_Close - Verified_Liquid_Assets)
```
</details>

<details>
<summary>Validation rules</summary>

Every division is guarded against a zero or blank denominator — a cleared input returns zero or "N/A," not a formula error. Buy-rate lookups that fall outside the grid return a flag, not a blank cell, so a missing rate stays visible rather than silently zero.
</details>

<details>
<summary>Two implementations, one formula set</summary>

The Excel workbook and the standalone web version run identical formula logic — one in spreadsheet formulas, one in JavaScript — checked against the same test deals to confirm matching Global Eligibility, Spread Status, and Cash-to-Close figures before either was published. The Excel file targets Excel 2016 and later; the web version runs in any modern browser, with no server, no install, and no external dependency.
</details>

---

## Get The Workbook

Two formats, same engine. `RTL_Loan_Sizer_Pricer.xlsx` for desks that work inside Excel. `RTL_Loan_Sizer_Pricer_App.html` for a browser-based version with no install — open the file, no spreadsheet software required. Both compute the same gates from the same inputs. Pull either one, drop in a deal, and check whether it actually clears.

---

## Limitations

This is a pricing and eligibility calculator, not a loan origination system. It does not connect to a live rate sheet, a credit bureau, or a loan servicing platform — every input is entered manually, and the buy-rate grid is only as current as whoever last updated it. It does not make a credit decision or satisfy a regulatory compliance requirement; Exception Needed means a human underwriter reviews the file, not that the workbook approved it. It assumes a single borrower and a single property per run — no multi-property or cross-collateralized scenarios. Day-count conventions (Actual/360) and the 5-point exception buffer are fixed assumptions that should be checked against the desk's actual policy before relying on the output for a real commitment.

---

## Other Decision Tools You Might Need

The same gate-before-quote approach applies beyond RTL pricing:

- Healthcare pricing and margin analysis, for desks pricing against actuarial assumptions instead of leverage caps.
- Inventory replenishment planning, for operations gating reorder decisions against multiple stock thresholds at once.
- Lightweight asset tracking and audit, for teams that need a Pass/Fail gate on compliance status rather than a free-form log.

Available on request — see the builder's other listings.

---

## License

Licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0). Use, modification, and redistribution are permitted under the terms of that license; see the `LICENSE` file in this repository for the full text.
