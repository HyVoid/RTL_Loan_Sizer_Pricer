[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# RTL Loan Sizer / Pricer

## Lightweight Residential Transitional Loan Decision Support Tool for Accurate Loan Structuring, Pricing, Eligibility Validation, and Client-Ready Quote Generation

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Status](https://img.shields.io/badge/Version-Stable-brightgreen)

**Size, validate, and price Residential Transitional Loans consistently in minutes—without installation, without coding, and without exposing proprietary pricing logic. Available as both a browser version and an Excel workbook.**

**No signup. No installation. Free in your browser.**

Try the browser version for free. If you need the Excel version, you can buy it with a 30-day, no-questions-asked money-back guarantee.
>
> 🌐 **Open in Browser**  
> [*HTML version*](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> 📥 **Download Excel**  
> [*Excel download*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## What It Helps You Track

- Loan eligibility against underwriting leverage limits before a quote is issued.
- Actual LTV, LTC, LTP, and LTARV across different residential transitional loan structures.
- Borrower funding requirements, net funding proceeds, and estimated cash required at closing.
- Pricing consistency across FICO tiers, leverage levels, and lender pricing assumptions.
- Margin protection by identifying loans priced below internal spread requirements.
- Client-ready loan terms generated from a single underwriting workflow instead of manually assembling calculations.

---

## Quick Start Workflow

### 1. Configure underwriting assumptions

Administrative users define lending parameters once on the dedicated Pricing & Assumptions worksheet. These include leverage limits, pricing grids, servicing fees, spread requirements, loan programs, and underwriting thresholds. These settings normally require only periodic maintenance rather than daily adjustment.

---

### 2. Enter a new loan scenario

Open the **Inputs** worksheet and complete the requested information.

Typical information includes:

- Purchase price
- As-Is value
- Rehabilitation budget
- After Repair Value (ARV)
- Requested loan amount
- Borrower FICO
- Borrower experience
- Liquid assets
- Loan term
- Requested note rate

Dropdown menus and validation rules reduce incorrect entries while conditional formatting automatically disables fields that are not applicable for the selected loan program.

---

### 3. Review results instantly

Switch to the Quote Summary page.

All underwriting calculations update automatically, including:

- Loan eligibility
- Leverage metrics
- Pricing validation
- Cash-to-close
- Net funding
- Prepaid interest
- Settlement estimates

No manual calculations or separate pricing worksheets are required.

---

### 4. Repeat for every new loan

Each additional loan only requires replacing the borrower inputs.

There is no need to rebuild formulas, modify calculations, or redesign reports. The pricing engine remains reusable across Bridge Loans, Fix-and-Flip Loans, Heavy Rehab, Light Rehab, and Construction financing scenarios.

**Set the underwriting parameters once. Enter the loan scenario. Review the pricing. Generate the quote. Repeat whenever another loan needs to be evaluated.**

*   👉 [*Download the Excel Template for Offline Use*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Why I Built This

Residential Transitional Loan underwriting often appears straightforward because experienced lenders already know the major ratios they want to approve. In reality, most pricing mistakes happen long before a loan reaches committee review.

The problem is rarely calculating LTV or LTC individually. The problem is evaluating every underwriting rule simultaneously while also protecting lender profitability.

A processor might calculate an acceptable LTV but overlook that the requested note rate no longer satisfies the minimum spread requirement. Another originator may quote an attractive rate that fits borrower expectations but unintentionally prices below the lender's required buy rate. A third transaction may satisfy leverage requirements but still require substantially more borrower cash than expected because prepaid interest and servicing fees reduce available funding.

Instead of relying on multiple disconnected spreadsheets or manually checking underwriting guidelines one rule at a time, I wanted a reusable analytical framework that evaluates every major underwriting constraint together.

For example:

**Before**

- LTV looks acceptable.
- Borrower receives a verbal quote.
- Pricing review later discovers insufficient lender spread.
- Quote must be revised.
- Borrower confidence decreases.
- Internal processing time increases.

**After**

The workbook evaluates leverage, pricing, spread protection, settlement costs, liquidity requirements, and eligibility together before the quote is issued. The lender immediately knows whether the scenario passes, requires an exception, or should not proceed.

This workbook is not simply a calculator. It packages underwriting reasoning into a repeatable decision-support process that reduces inconsistent loan structuring across different users.

---

## Common RTL Lending Problems This Solves

| Problem | Without This Tool | With This Tool |
|------------|-----------------|----------------|
| Loan approved using only one leverage ratio | Important underwriting limits may be overlooked until final review | All major leverage ratios are evaluated simultaneously before quoting |
| Manual pricing | Different originators quote different rates for identical borrowers | Pricing is generated consistently using centralized pricing rules |
| Hidden profitability erosion | Loans appear acceptable but violate minimum margin requirements | Spread validation immediately flags pricing below lender requirements |
| Unexpected borrower cash requirement | Settlement costs discovered late in closing | Cash-to-close and net funding are calculated during initial structuring |
| Loan exceptions identified too late | Multiple revisions delay underwriting | Exception scenarios are highlighted immediately for management review |
| Internal pricing logic exposed | Sensitive buy-rate calculations become visible to external users | Internal pricing sheets remain protected in originator-facing versions |

---

## Who This Is For

This workbook is designed for professionals involved in Residential Transitional Lending, including:

- Private lenders
- Hard money lenders
- Loan originators
- Loan processors
- Underwriters
- Capital markets teams
- Small lending firms seeking standardized loan pricing
- Credit teams evaluating Bridge, Rehab, and Construction loans

It is particularly useful for organizations that need a lightweight underwriting workflow without implementing a full Loan Origination System (LOS).

This is **not** intended to replace enterprise lending platforms, servicing software, or compliance management systems.

No spreadsheet expertise is required. Open the browser version or Excel workbook, enter the loan information, and begin evaluating loan scenarios immediately.

---

## About

I build lightweight analytical tools for situations where too many operational variables must be considered at the same time. Rather than replacing enterprise software, these workbooks package practical decision-making into reusable frameworks that help teams reach consistent conclusions with less manual effort.

The **RTL Loan Sizer / Pricer** follows that philosophy by bringing underwriting rules, pricing logic, leverage validation, settlement calculations, and quote generation together in one structured workflow. The central question is always the same: **What information needs to be visible in one place to make the next lending decision confidently?**
## Technical Details

<details>
<summary><strong>For technical reviewers, Excel practitioners, and collaborators</strong></summary>

---

## Workbook Architecture

The workbook follows a layered architecture that separates user interaction, business rules, analytical calculations, and presentation. This prevents accidental modification of pricing logic while keeping daily operation simple for loan originators.

```text
                    USER LAYER
 ┌─────────────────────────────────────┐
 │          01_ReadMe                  │
 │ Documentation & Version Control     │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │          02_Inputs                  │
 │ Borrower & Loan Information         │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │ 03_Pricing_&_Assumptions            │
 │ Pricing Rules & Risk Parameters     │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │       04_Calc_Engine                │
 │ Underwriting & Pricing Logic        │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │      05_Quote_Summary               │
 │ Client Ready Output                 │
 └─────────────────────────────────────┘
```

## Worksheet Responsibilities

| Worksheet | Purpose | Editable |
|------------|---------|----------|
| 01_ReadMe | Instructions, version history, administrator documentation | Yes |
| 02_Inputs | Borrower information and requested loan terms | Yes |
| 03_Pricing_&_Assumptions | Buy rate grids, leverage rules, pricing assumptions | Administrators only |
| 04_Calc_Engine | Underwriting calculations, pricing engine and validation | No |
| 05_Quote_Summary | Client-facing printable term sheet | No |

---

## Data Flow

```text
Borrower Inputs
        │
        ▼
Input Validation
        │
        ▼
Pricing Lookup
        │
        ▼
Leverage Calculations
        │
        ▼
Eligibility Validation
        │
        ▼
Settlement Calculations
        │
        ▼
Profitability Analysis
        │
        ▼
Quote Summary
```

Every output displayed to users originates from the calculation engine. No values are manually entered into the final quote.

---

## Security Strategy

The workbook is intentionally compiled into two distribution formats.

| Version | Intended Users | Protected Components |
|---------|----------------|----------------------|
| Internal Version | Principals, Underwriters, Operations | All worksheets visible with administrator password |
| Originator Version | Loan Originators | Pricing tables and calculation engine hidden using xlSheetVeryHidden |

Additional protection measures include:

- Workbook Structure Protection
- Hidden formulas
- Locked calculation cells
- Protected pricing grids
- Hidden Formula Bar (Originator Version)
- Password-protected worksheet structure

This approach protects proprietary lender pricing without maintaining two independent workbooks.

---

## Three Traps That Catch Even Experienced Loan Originators

---

## Trap 1 — Looking Only at LTV

Many lenders instinctively focus on Loan-to-Value because it is the most familiar underwriting metric.

Unfortunately, Transitional Lending rarely relies on only one leverage ratio.

### Incorrect Decision

Purchase Price

```
$400,000
```

Requested Loan

```
$320,000
```

As-Is Value

```
$420,000
```

Calculated LTV

```
76.2%
```

The originator concludes:

> "The loan fits within policy."

However...

Rehab Budget

```
$160,000
```

Total Project Cost

```
$560,000
```

Actual LTC

```
57.1%
```

Actual LTARV

```
88%
```

The LTARV exceeds internal policy.

The loan is actually outside lending guidelines.

### Correct Approach

Evaluate:

- LTV
- LTC
- LTARV
- LTP

before determining eligibility.

<details>

<summary>Formula Reference</summary>

```excel
Actual LTV
=IFERROR(LoanAmount/AsIsValue,0)

Actual LTC
=IFERROR(LoanAmount/(PurchasePrice+RehabBudget),0)

Actual LTARV
=IF(ARV=0,0,
IFERROR(LoanAmount/ARV,0))
```

</details>

Result:

The workbook automatically evaluates every leverage ratio together before assigning a Pass, Exception, or Fail status.

---

## Trap 2 — Quoting Before Checking Margin

A borrower requests an attractive rate.

The originator lowers the note rate to remain competitive.

Everything appears acceptable.

Later...

Secondary marketing discovers that lender spread has fallen below internal minimums.

The quote must be revised.

### Incorrect Decision

Borrower Rate

```
10.00%
```

Buy Rate

```
8.20%
```

Spread

```
1.80%
```

Minimum Required Spread

```
2.50%
```

The transaction is actually below lender profitability requirements.

### Correct Approach

Every quote should validate pricing before presentation.

<details>

<summary>Formula Reference</summary>

```excel
Spread

=NoteRate-BuyRate

Spread Status

=IF(
Spread<MinimumSpread,
"Below Margin",
"Valid")
```

</details>

Instead of discovering the problem during final review, the workbook immediately flags:

```
Below Margin
```

allowing pricing to be corrected before the borrower receives a quote.

---

## Trap 3 — Underestimating Cash Required at Closing

Many borrowers evaluate only the requested loan amount.

Settlement costs reduce actual proceeds.

Ignoring these deductions frequently produces unrealistic borrower expectations.

### Example

Requested Loan

```
$450,000
```

Short Interest

```
$6,250
```

Servicing Fee

```
$2,250
```

Net Funding

```
$441,500
```

Required Cash

```
$468,000
```

Actual Cash to Close

```
$26,500
```

If borrower liquidity equals only

```
$18,000
```

the loan cannot close without additional funds.

### Correct Approach

Calculate settlement proceeds rather than assuming gross loan amount equals available funding.

<details>

<summary>Formula Reference</summary>

```excel
Net Funding

=LoanAmount
-ShortInterest
-ServiceFee

Cash To Close

=MAX(
0,
TotalProjectCost-
NetFunding)

Liquidity Shortfall

=MAX(
0,
CashToClose-
LiquidAssets)
```

</details>

The workbook identifies liquidity shortages before closing documents are prepared.

---

## Example Scenario

Consider the following Fix-and-Flip transaction.

| Item | Value |
|------|------:|
| Purchase Price | $300,000 |
| Rehab Budget | $70,000 |
| As-Is Value | $310,000 |
| ARV | $465,000 |
| Requested Loan | $340,000 |
| FICO | 726 |
| Experience | 6+ Projects |
| Note Rate | 11.25% |
| Loan Term | 12 Months |

The pricing engine retrieves the corresponding Buy Rate based on the borrower's FICO tier and calculated leverage.

The calculation engine then determines:

- Actual LTV
- Actual LTC
- Actual LTP
- Actual LTARV
- Spread
- Net Funding
- Cash to Close
- Estimated Lender Profit

Suppose the resulting metrics are:

| Metric | Result |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Eligibility | Exception Needed |

Although pricing remains profitable, leverage exceeds the preferred LTV threshold.

Rather than immediately declining the loan, the workbook classifies it as **Exception Needed**, allowing management to review compensating factors such as borrower experience, liquidity, or additional collateral.

This structured workflow creates a consistent underwriting process where pricing, leverage, settlement, and profitability are evaluated together rather than independently.

---

## Formula Reference

<details>

<summary>Leverage Calculations</summary>

| Calculation | Formula |
|-------------|---------|
| Actual LTV | `Loan Amount ÷ As-Is Value` |
| Actual LTC | `Loan Amount ÷ (Purchase + Rehab)` |
| Actual LTP | `Loan Amount ÷ Purchase Price` |
| Actual LTARV | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Pricing Engine</summary>

| Formula | Purpose |
|----------|----------|
| XLOOKUP | Retrieve Buy Rate |
| INDEX + MATCH | Legacy pricing lookup |
| Spread | Note Rate − Buy Rate |
| Spread Status | Margin validation |

Pricing always uses exact lookup behavior with default error handling to prevent invalid pricing outputs.

</details>

<details>

<summary>Settlement Calculations</summary>

| Calculation | Purpose |
|-------------|----------|
| Short Interest | Interest collected at closing |
| Servicing Fee | Fee deducted over loan term |
| Net Funding | Funds available to borrower |
| Cash to Close | Additional borrower contribution |
| Liquidity Shortfall | Funding deficiency |

</details>

<details>

<summary>Eligibility Rules</summary>

The underwriting engine evaluates:

- Maximum LTV
- Maximum LTC
- Maximum LTARV
- Pricing Margin
- Borrower Liquidity

Possible outcomes:

- PASS
- EXCEPTION NEEDED
- FAIL

The overall eligibility always reflects the most restrictive underwriting result.

</details>

## Validation Rules

| Field | Validation Rule | Error Behavior |
|------|-----------------|----------------|
| Loan Type | Dropdown only | Reject invalid values |
| Purchase Price | Greater than zero | Return zero calculations |
| As-Is Value | Greater than zero | Prevent divide-by-zero |
| Rehab Budget | Zero for Bridge loans | Field automatically grayed out |
| ARV | Required for rehab products | Display N/A where applicable |
| Requested Loan | Positive currency | Reject negative values |
| FICO | 300–850 | Reject invalid score |
| Experience Tier | Dropdown only | Prevent lookup failures |
| Loan Term | 12 / 18 / 24 months | Reject other values |
| Short Interest Days | 0–30 | Reject invalid input |
| Buy Rate Lookup | XLOOKUP with fallback value | "Check Risk Rules" |
| Division Operations | IFERROR wrapper | Return 0 instead of Excel errors |
| Text Lookups | TRIM + UPPER | Prevent spacing and case mismatches |
| Margin Check | Compare against minimum spread | Return "Below Margin" |
| Eligibility | Evaluate all underwriting flags | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Other Tools in This Series

The **RTL Loan Sizer / Pricer** is part of a growing collection of lightweight operational decision-support tools built for professionals who need reliable analysis without implementing enterprise software.

Each tool follows the same principles:

- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Why is cash always tight? — Forecast future liquidity under changing operational and financial assumptions.
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Which trade flows are actually profitable after currency effects? — Measure multi-currency trade profitability across cross-border operations.
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Where is personal and business cash being mixed or misallocated? — Separate personal and business cash flows into independently tracked budget tracks.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Does this real estate acquisition still create equity value after renovation and operating assumptions? — Evaluate multifamily acquisition returns under renovation financing and operating scenarios.
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — What is a property worth under different valuation methods? — Calculate property value across multiple valuation methods with tax and capital expenditure modeling.
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Are shared costs being allocated fairly across entities or are some assets overburdened while others escape their true cost exposure? — Distribute supplier invoices across multiple legal entities and operating assets using configurable allocation methodologies.
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — What is each participant actually owed based on their entry timing and current pool value? — Track investment pool ownership continuously using NAV-based unit accounting.
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Which operational commitments will create a cash problem in the next twelve weeks? — Connect Shopify sales bank transactions advertising spend and inventory purchasing into a unified cash flow decision framework.
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — Has enough meaningful information changed to justify a pricing adjustment? — Govern pricing recommendations through configurable guard rails that prevent unnecessary revenue volatility.
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — What actually changed in the business this period and which products or keywords drove the change? — Transform Amazon Seller Central SQP and Sellerboard exports into standardized executive business reviews.
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Which products are actually profitable after all manufacturing costs are allocated and which are destroying margin? — Allocate factory labor utilities overhead and material costs to every SKU for true unit manufacturing economics.
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Which orders are actually profitable after all hidden costs and where is money leaking across channels and currencies? — Reconstruct true order-level profitability by reconciling sales payouts shipping costs payment fees and marketplace commissions across multi-channel e-commerce operations.
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Which contractor projects and customers are actually profitable after all job costs? — Connect lead estimation, job execution, and actual cost tracking into a unified contractor profitability framework.
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — Is the shop genuinely profitable after all ingredient, labor, and operating costs? — Connect recipe costing, sales, inventory consumption, and operating expenses into a unified profitability and cash flow framework.
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Which freight bookings are actually profitable after all costs, fees, and currency conversion? — Measure booking-level freight profitability by reconciling revenue, COGS, bank fees, and container costs across mixed-currency transactions.
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Which containers and customers are actually profitable across customs and fleet operations? — Consolidate customs clearance and fleet execution data into a single container-level profitability view.
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — What is actually owed today after years of transfers and accrued interest? — Reconcile long-term fund transfers and interest accruals into a current outstanding balance.
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — What will our financial statements look like under different operating and financing scenarios? — Forecast integrated financial statements by linking revenue, expenses, working capital, and debt into a unified model.
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — How much of each building's reported margin is actually generated by that building versus by the way corporate costs were allocated? — Allocate shared expenses across operating units while preserving source transactions and reconciling unit-level results to company totals.
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — At what maximum land acquisition price does this development project become a bankable investment? — Evaluate residential development opportunities by screening land comparables, estimating construction costs, and calculating profit-on-cost thresholds.
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Will this construction project actually hit its target margin once site logistics, waste factors, and trade rate changes are accounted for? — Separate physical building quantities from volatile trade rates and site preliminaries to cascade commercial markups across tender budgets and client quotations.
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Which wholesale prices and customer segments actually preserve margin once freight, duties, payment terms, and FX are fully costed? — Calculate SKU-level landed costs, cost-to-serve, and pocket-margin price waterfalls to simulate cross-border wholesale profitability.
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — What should we charge for a custom label order at each quantity tier to stay competitive and profitable? — Calculate parametric label pricing by modeling substrate square-inch costs, setup charges, and quantity-tier discount breaks against competitor benchmarks.
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — What is the true net margin on each SKU once actual landed costs and retailer deductions are accounted for? — Reconcile PO-estimated landed costs against actual freight, duty, FX, and drayage charges while auditing retailer remittance deductions to expose SKU-level net margin.
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Can we make this week's hiring, marketing, and vendor commitments without running out of cash before the books close? — Track weekly cash burn pacing, MRR/ARR waterfall variance, retention metrics, and payroll costs against budget before month-end close.
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — Will our growth plan run out of cash before cohort monetization catches up? — Forecast multi-year cash burn, runway, unit economics, and fundraising dilution from bottom-up cohort and headcount assumptions.
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Is each Shopify storefront actually profitable once true SKU-level costs, shared expenses, and bank charges are reconciled? — Reconcile multi-store Shopify sales exports against SKU-level COGS, allocated multi-currency OPEX, and bank statements to produce a trustworthy monthly P&L.
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Which tour bookings actually generate net profit and positive cash flow after supplier costs and B2B collections? — Calculate per-booking tour job costs, gross margins, AR/AP settlement, and operating cash flow across multiple currencies.

| Tool | Purpose |
|------|---------|
| Construction Estimating System | Standardize project estimating, assemblies, bid pricing, and cost tracking. |
| Inventory Forecasting & Reorder Planner | Forecast inventory demand, identify replenishment timing, and monitor stock risk. |
| Retail & Maquila Inventory Ledger | Track piece-level inventory movement, production, defects, and distribution. |
| Unified Personal & Business Budget Framework | Consolidate personal and business cash flow into one financial planning model. |
| Cross-Border VAT Compliance Dashboard | Monitor VAT obligations across multiple countries and selling channels. |
| Project Financial Control Dashboard | Compare budget, commitments, invoices, progress billing, and project profitability. |
| Coffee Shop Operations Audit Toolkit | Evaluate café operational performance using standardized audit scoring and KPI analysis. |

---

## Disclaimer

This workbook is intended as an analytical decision-support tool.

It does **not** constitute:

- legal advice,
- lending advice,
- underwriting approval,
- accounting guidance,
- regulatory compliance certification,
- investment recommendation.

All loan decisions remain subject to the lending institution's underwriting policies, applicable regulations, investor requirements, and final credit approval.

Users are responsible for verifying all assumptions, pricing parameters, fee schedules, and underwriting rules before relying on the generated outputs.

---

## Acknowledgements

This project reflects common underwriting practices used in Residential Transitional Lending, including Bridge Loans, Fix-and-Flip financing, Rehabilitation Loans, and Residential Construction Lending.

Its architecture emphasizes transparency, repeatability, and operational consistency so that pricing decisions can be reproduced, reviewed, and audited rather than depending on individual spreadsheet knowledge.

---

**Apache License 2.0 © 2026**

Built as part of a broader collection of lightweight operational decision-support tools for finance, construction, inventory management, and business operations.
