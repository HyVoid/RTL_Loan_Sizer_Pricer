[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# RTL-Darlehensrechner und Preisgestalter

## Leichtgewichtiges Entscheidungsunterstützungswerkzeug für Residential Transitional Loans zur präzisen Darlehensstrukturierung, Preisgestaltung, Bonitätsprüfung und kundenfertigen Angebotserstellung

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Status](https://img.shields.io/badge/Version-Stable-brightgreen)

**Dimensionieren, validieren und bepreisen Sie Residential Transitional Loans in wenigen Minuten konsistent—ohne Installation, ohne Programmierung und ohne Offenlegung proprietärer Preislogik. Sowohl als Browserversion als auch als Excel-Arbeitsmappe verfügbar.**

**Keine Registrierung. Keine Installation. Kostenlos in Ihrem Browser.**

Testen Sie die Browserversion kostenlos. Wenn Sie die Excel-Version benötigen, können Sie sie mit 30-tägiger Geld-zurück-Garantie ohne Rückfragen erwerben.
>
> 🌐 **Im Browser öffnen**  
> [*HTML-Version*](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> 📥 **Excel herunterladen**  
> [*Excel-Download*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Was es Ihnen hilft zu verfolgen

- Darlehensberechtigung gegen die Kreditprüfungs-Belegungsgrenzen vor Angebotserstellung.
- Tatsächliches LTV, LTC, LTP und LTARV über verschiedene RTL-Darlehensstrukturen hinweg.
- Finanzierungsanforderungen des Kreditnehmers, Nettofinanzierungserlös und geschätzter Barbedarf zum Abschluss.
- Preiskonsistenz über FICO-Stufen, Belegungsniveaus und Preisannahmen des Kreditgebers hinweg.
- Margin-Schutz durch Identifizierung von Darlehen, die unter internen Spread-Anforderungen bepreist sind.
- Kundenfertige Darlehenskonditionen aus einem einzigen Kreditprüfungs-Workflow statt manuell zusammengestellter Berechnungen.

---

## Schnellstart-Workflow

### 1. Annahmen der Kreditprüfung konfigurieren

Administrative Benutzer definieren die Kreditparameter einmal auf dem dedizierten Arbeitsblatt Pricing & Assumptions. Dazu gehören Belegungsgrenzen, Preisraster, Servicegebühren, Spread-Anforderungen, Darlehensprogramme und Kreditprüfungsschwellen. Diese Einstellungen erfordern normalerweise nur periodische Wartung statt täglicher Anpassung.

---

### 2. Ein neues Darlehensszenario eingeben

Öffnen Sie das Arbeitsblatt **Inputs** und vervollständigen Sie die angeforderten Informationen.

Typische Informationen umfassen:

- Kaufpreis
- Ist-Wert
- Sanierungsbudget
- Wert nach Instandsetzung (ARV)
- Angefragte Darlehenshöhe
- FICO-Score des Kreditnehmers
- Erfahrung des Kreditnehmers
- Liquide Mittel
- Darlehenslaufzeit
- Angefragter Sollzins

Dropdown-Menüs und Validierungsregeln reduzieren fehlerhafte Eingaben, während bedingte Formatierungen Felder, die für das gewählte Darlehensprogramm nicht anwendbar sind, automatisch deaktivieren.

---

### 3. Ergebnisse sofort überprüfen

Wechseln Sie zur Seite Quote Summary.

Alle Kreditprüfungsberechnungen aktualisieren sich automatisch, einschließlich:

- Darlehensberechtigung
- Belegungskennzahlen
- Preisvalidierung
- Barzahlung zum Abschluss
- Nettofinanzierung
- Vorausbezahlte Zinsen
- Abschlusskostenschätzungen

Keine manuellen Berechnungen oder separaten Preisarbeitsblätter erforderlich.

---

### 4. Für jedes neue Darlehen wiederholen

Jedes weitere Darlehen erfordert nur das Ersetzen der Kreditnehmereingaben.

Es ist nicht nötig, Formeln neu aufzubauen, Berechnungen zu ändern oder Berichte neu zu gestalten. Die Preis-Engine bleibt über Brückendarlehen, Fix-and-Flip-Darlehen, umfassende Sanierung, leichte Sanierung und Baufinanzierungsszenarien hinweg wiederverwendbar.

**Legen Sie die Kreditprüfungsparameter einmal fest. Geben Sie das Darlehensszenario ein. Prüfen Sie die Preisgestaltung. Erstellen Sie das Angebot. Wiederholen Sie, wann immer ein weiteres Darlehen bewertet werden muss.**

*   👉 [*Laden Sie die Excel-Vorlage für die Offline-Nutzung herunter*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Warum ich das gebaut habe

Die Kreditprüfung von Residential Transitional Loans erscheint oft unkompliziert, weil erfahrene Kreditgeber die wichtigsten Quoten, die sie genehmigen wollen, bereits kennen. In Wirklichkeit passieren die meisten Preisgestaltungsfehler lange bevor ein Darlehen die Ausschussprüfung erreicht.

Das Problem ist selten die Berechnung von LTV oder LTC einzeln. Das Problem ist, jede Kreditprüfungsregel gleichzeitig zu bewerten und gleichzeitig die Rentabilität des Kreditgebers zu schützen.

Ein Bearbeiter könnte ein akzeptables LTV berechnen, aber übersehen, dass der angefragte Sollzins die Mindest-Spread-Anforderung nicht mehr erfüllt. Ein anderer Vermittler mag einen attraktiven Zins anbieten, der den Erwartungen des Kreditnehmers entspricht, aber unbeabsichtigt unter dem erforderlichen Ankaufszins des Kreditgebers preisen. Eine dritte Transaktion mag die Belegungsanforderungen erfüllen, aber dennoch deutlich mehr Kreditnehmerliquidität erfordern als erwartet, weil vorausbezahlte Zinsen und Servicegebühren die verfügbare Finanzierung reduzieren.

Anstatt auf mehrere getrennte Tabellenkalkulationen zu vertrauen oder Kreditprüfungsrichtlinien manuell Regel für Regel zu prüfen, wollte ich ein wiederverwendbares Analyseverfahren, das jede wichtige Kreditprüfungsbeschränkung gemeinsam bewertet.

Zum Beispiel:

**Vorher**

- Das LTV sieht akzeptabel aus.
- Der Kreditnehmer erhält ein mündliches Angebot.
- Die Preisprüfung entdeckt später unzureichenden Kreditgeber-Spread.
- Das Angebot muss überarbeitet werden.
- Das Vertrauen des Kreditnehmers sinkt.
- Die interne Bearbeitungszeit steigt.

**Nachher**

Die Arbeitsmappe bewertet Belegung, Preisgestaltung, Spread-Schutz, Abschlusskosten, Liquiditätsanforderungen und Bonität gemeinsam, bevor das Angebot erstellt wird. Der Kreditgeber weiß sofort, ob das Szenario besteht, eine Ausnahme erfordert oder nicht fortgeführt werden sollte.

Diese Arbeitsmappe ist nicht einfach ein Rechner. Sie verpackt Kreditprüfungslogik in einen wiederholbaren Entscheidungsunterstützungsprozess, der inkonsistente Darlehensstrukturierung zwischen verschiedenen Benutzern reduziert.

---

## Häufige RTL-Kreditvergabeprobleme, die dieses Tool löst

| Problem | Ohne dieses Tool | Mit diesem Tool |
|------------|-----------------|----------------|
| Darlehen anhand nur einer Belegungsquote genehmigt | Wichtige Kreditprüfungsgrenzen können bis zur Endprüfung übersehen werden | Alle wichtigen Belegungsquoten werden vor Angebotserstellung gemeinsam bewertet |
| Manuelle Preisgestaltung | Verschiedene Vermittler nennen für identische Kreditnehmer unterschiedliche Zinsen | Die Preisgestaltung erfolgt konsistent mit zentralisierten Preisregeln |
| Versteckte Rentabilitätserosion | Darlehen erscheinen akzeptabel, verletzen aber Mindest-Margin-Anforderungen | Die Spread-Validierung meldet sofort Preisgestaltung unter Kreditgeberanforderungen |
| Unerwarteter Kreditnehmer-Barbedarf | Abschlusskosten werden spät beim Schließen entdeckt | Barzahlung zum Abschluss und Nettofinanzierung werden während der Erststrukturierung berechnet |
| Darlehensausnahmen zu spät identifiziert | Mehrere Überarbeitungen verzögern die Kreditprüfung | Ausnahmeszenarien werden sofort für die Managementprüfung hervorgehoben |
| Interne Preislogik offengelegt | Sensible Ankaufszinsberechnungen werden für externe Benutzer sichtbar | Interne Preisblätter bleiben in vermittlerseitigen Versionen geschützt |

---

## Für wen dieses Tool bestimmt ist

Diese Arbeitsmappe ist für Fachleute gedacht, die an Residential Transitional Lending beteiligt sind, einschließlich:

- Privatkreditgeber
- Hard-Money-Kreditgeber
- Darlehensvermittler
- Darlehensbearbeiter
- Kreditprüfer
- Kapitalmarktabteilungen
- Kleine Kreditvergabefirmen, die standardisierte Darlehenspreise anstreben
- Kreditabteilungen, die Brücken-, Sanierungs- und Baudarlehen bewerten

Es ist besonders nützlich für Organisationen, die einen leichten Kreditprüfungs-Workflow ohne Implementierung eines vollständigen Loan Origination System (LOS) benötigen.

Dies ist **nicht** dazu gedacht, Kreditvergabeplattformen für Unternehmen, Servicing-Software oder Compliance-Management-Systeme zu ersetzen.

Keine Tabellenkalkulations-Expertise erforderlich. Öffnen Sie die Browserversion oder die Excel-Arbeitsmappe, geben Sie die Darlehensinformationen ein und beginnen Sie sofort mit der Bewertung von Darlehensszenarien.

---

## Über

Ich baue leichte Analysewerkzeuge für Situationen, in denen zu viele operative Variablen gleichzeitig berücksichtigt werden müssen. Anstatt Unternehmenssoftware zu ersetzen, verpacken diese Arbeitsmappen praktische Entscheidungsfindung in wiederverwendbare Verfahren, die Teams helfen, mit weniger manuellem Aufwand zu konsistenten Schlussfolgerungen zu gelangen.

Der **RTL-Darlehensrechner und Preisgestalter** folgt dieser Philosophie, indem er Kreditprüfungsregeln, Preislogik, Belegungsvalidierung, Abschlussberechnungen und Angebotserstellung in einem strukturierten Workflow zusammenführt. Die zentrale Frage ist immer dieselbe: **Welche Informationen müssen an einem Ort sichtbar sein, um die nächste Kreditentscheidung sicher zu treffen?**
## Technische Details

<details>
<summary><strong>Für technische Prüfer, Excel-Praktiker und Mitarbeiter</strong></summary>

---

## Arbeitsmappen-Architektur

Die Arbeitsmappe folgt einer geschichteten Architektur, die Benutzerinteraktion, Geschäftsregeln, analytische Berechnungen und Darstellung trennt. Dies verhindert versehentliche Änderungen der Preislogik und hält den täglichen Betrieb für Darlehensvermittler einfach.

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

## Aufgaben der Arbeitsblätter

| Arbeitsblatt | Zweck | Bearbeitbar |
|------------|---------|----------|
| 01_ReadMe | Anweisungen, Versionshistorie, Administrator-Dokumentation | Ja |
| 02_Inputs | Kreditnehmerinformationen und angefragte Darlehenskonditionen | Ja |
| 03_Pricing_&_Assumptions | Ankaufszinsraster, Belegungsregeln, Preisannahmen | Nur Administratoren |
| 04_Calc_Engine | Kreditprüfungsberechnungen, Preis-Engine und Validierung | Nein |
| 05_Quote_Summary | Kundenfertiges druckbares Konditionsblatt | Nein |

---

## Datenfluss

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

Jede den Benutzern angezeigte Ausgabe stammt aus der Berechnungsmaschine. Keine Werte werden manuell in das endgültige Angebot eingegeben.

---

## Sicherheitsstrategie

Die Arbeitsmappe wird absichtlich in zwei Vertriebsformate kompiliert.

| Version | Vorgesehene Benutzer | Geschützte Komponenten |
|---------|----------------|----------------------|
| Interne Version | Prinzipale, Kreditprüfer, Betrieb | Alle Arbeitsblätter sichtbar mit Administrator-Passwort |
| Vermittlerversion | Darlehensvermittler | Preistabellen und Berechnungsmaschine versteckt mit xlSheetVeryHidden |

Zusätzliche Schutzmaßnahmen umfassen:

- Arbeitsmappen-Strukturschutz
- Versteckte Formeln
- Gesperrte Berechnungszellen
- Geschützte Preisraster
- Versteckte Formelleiste (Vermittlerversion)
- Passwortgeschützte Arbeitsblattstruktur

Dieser Ansatz schützt proprietäre Kreditgeberpreise, ohne zwei unabhängige Arbeitsmappen zu pflegen.

---

## Drei Fallen, die selbst erfahrene Darlehensvermittler fangen

---

## Falle 1 — Nur auf das LTV schauen

Viele Kreditgeber konzentrieren sich instinktiv auf die Loan-to-Value-Quote, weil sie die vertrauteste Kreditprüfungskennzahl ist.

Leider stützt sich Transitional Lending selten auf nur eine Belegungsquote.

### Falsche Entscheidung

Kaufpreis

```
$400,000
```

Angefragtes Darlehen

```
$320,000
```

Ist-Wert

```
$420,000
```

Berechnetes LTV

```
76.2%
```

Der Vermittler schlussfolgert:

> "Das Darlehen entspricht der Richtlinie."

Jedoch...

Sanierungsbudget

```
$160,000
```

Gesamtprojektkosten

```
$560,000
```

Tatsächliches LTC

```
57.1%
```

Tatsächliches LTARV

```
88%
```

Das LTARV überschreitet die interne Richtlinie.

Das Darlehen liegt tatsächlich außerhalb der Kreditvergaberichtlinien.

### Richtiger Ansatz

Bewerten Sie:

- LTV
- LTC
- LTARV
- LTP

bevor Sie die Bonität bestimmen.

<details>

<summary>Formelreferenz</summary>

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

Ergebnis:

Die Arbeitsmappe bewertet automatisch jede Belegungsquote gemeinsam, bevor sie einen Status Pass, Exception oder Fail vergibt.

---

## Falle 2 — Angebotserstellung vor Margin-Prüfung

Ein Kreditnehmer bittet um einen attraktiven Zins.

Der Vermittler senkt den Sollzins, um wettbewerbsfähig zu bleiben.

Alles erscheint akzeptabel.

Später...

Das Sekundärmarketing entdeckt, dass der Kreditgeber-Spread unter interne Minima gefallen ist.

Das Angebot muss überarbeitet werden.

### Falsche Entscheidung

Kreditnehmerzins

```
10.00%
```

Ankaufszins

```
8.20%
```

Spread

```
1.80%
```

Mindestens erforderlicher Spread

```
2.50%
```

Die Transaktion liegt tatsächlich unter den Rentabilitätsanforderungen des Kreditgebers.

### Richtiger Ansatz

Jedes Angebot sollte die Preisgestaltung vor der Präsentation validieren.

<details>

<summary>Formelreferenz</summary>

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

Anstatt das Problem während der Endprüfung zu entdecken, meldet die Arbeitsmappe sofort:

```
Below Margin
```

was eine Korrektur der Preisgestaltung erlaubt, bevor der Kreditnehmer ein Angebot erhält.

---

## Falle 3 — Unterschätzung des Barbedarfs zum Abschluss

Viele Kreditnehmer bewerten nur die angefragte Darlehenshöhe.

Abschlusskosten reduzieren den tatsächlichen Erlös.

Diese Abzüge zu ignorieren, erzeugt häufig unrealistische Erwartungen des Kreditnehmers.

### Beispiel

Angefragtes Darlehen

```
$450,000
```

Zwischenzinsen

```
$6,250
```

Servicegebühr

```
$2,250
```

Nettofinanzierung

```
$441,500
```

Erforderliche liquide Mittel

```
$468,000
```

Tatsächliche Barzahlung zum Abschluss

```
$26,500
```

Wenn die Liquidität des Kreditnehmers nur

```
$18,000
```

beträgt, kann das Darlehen nicht ohne zusätzliche Mittel geschlossen werden.

### Richtiger Ansatz

Berechnen Sie den Abschlusserlös, anstatt anzunehmen, dass die Brutto-Darlehenssumme der verfügbaren Finanzierung entspricht.

<details>

<summary>Formelreferenz</summary>

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

Die Arbeitsmappe identifiziert Liquiditätsengpässe, bevor Abschlussdokumente vorbereitet werden.

---

## Beispielszenario

Betrachten Sie die folgende Fix-and-Flip-Transaktion.

| Posten | Wert |
|------|------:|
| Kaufpreis | $300,000 |
| Sanierungsbudget | $70,000 |
| Ist-Wert | $310,000 |
| ARV | $465,000 |
| Angefragtes Darlehen | $340,000 |
| FICO | 726 |
| Erfahrung | 6+ Projects |
| Sollzins | 11.25% |
| Darlehenslaufzeit | 12 Months |

Die Preis-Engine ruft den entsprechenden Ankaufszins basierend auf der FICO-Stufe des Kreditnehmers und der berechneten Belegung ab.

Die Berechnungsmaschine bestimmt dann:

- Tatsächliches LTV
- Tatsächliches LTC
- Tatsächliches LTP
- Tatsächliches LTARV
- Spread
- Nettofinanzierung
- Barzahlung zum Abschluss
- Geschätzter Kreditgebergewinn

Angenommen, die resultierenden Kennzahlen sind:

| Kennzahl | Ergebnis |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Bonität | Exception Needed |

Obwohl die Preisgestaltung rentabel bleibt, überschreitet die Belegung die bevorzugte LTV-Schwelle.

Anstatt das Darlehen sofort abzulehnen, klassifiziert die Arbeitsmappe es als **Exception Needed**, was dem Management erlaubt, ausgleichende Faktoren wie Kreditnehmererfahrung, Liquidität oder zusätzliche Sicherheiten zu prüfen.

Dieser strukturierte Workflow schafft einen konsistenten Kreditprüfungsprozess, in dem Preisgestaltung, Belegung, Abschluss und Rentabilität gemeinsam statt unabhängig bewertet werden.

---

## Formelreferenz

<details>

<summary>Belegungsberechnungen</summary>

| Berechnung | Formel |
|-------------|---------|
| Tatsächliches LTV | `Loan Amount ÷ As-Is Value` |
| Tatsächliches LTC | `Loan Amount ÷ (Purchase + Rehab)` |
| Tatsächliches LTP | `Loan Amount ÷ Purchase Price` |
| Tatsächliches LTARV | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Preis-Engine</summary>

| Formel | Zweck |
|----------|----------|
| XLOOKUP | Ankaufszins abrufen |
| INDEX + MATCH | Legacy-Preisabruf |
| Spread | Sollzins − Ankaufszins |
| Spread-Status | Margin-Validierung |

Die Preisgestaltung verwendet immer exaktes Abrufverhalten mit Standard-Fehlerbehandlung, um ungültige Preisausgaben zu verhindern.

</details>

<details>

<summary>Abschlussberechnungen</summary>

| Berechnung | Zweck |
|-------------|----------|
| Zwischenzinsen | Beim Abschluss erhobene Zinsen |
| Servicegebühr | Über die Darlehenslaufzeit abgezogene Gebühr |
| Nettofinanzierung | Dem Kreditnehmer verfügbare Mittel |
| Barzahlung zum Abschluss | Zusätzlicher Kreditnehmerbeitrag |
| Liquiditätslücke | Finanzierungsdefizit |

</details>

<details>

<summary>Bonitätsregeln</summary>

Die Kreditprüfungsmaschine bewertet:

- Maximales LTV
- Maximales LTC
- Maximales LTARV
- Preis-Margin
- Kreditnehmerliquidität

Mögliche Ergebnisse:

- PASS
- EXCEPTION NEEDED
- FAIL

Die Gesamtbonität spiegelt immer das restriktivste Kreditprüfungsergebnis wider.

</details>

## Validierungsregeln

| Feld | Validierungsregel | Fehlerverhalten |
|------|-----------------|----------------|
| Loan Type | Nur Dropdown | Ungültige Werte zurückweisen |
| Purchase Price | Größer als null | Nullberechnungen zurückgeben |
| As-Is Value | Größer als null | Division durch null verhindern |
| Rehab Budget | Null für Brückendarlehen | Feld automatisch ausgegraut |
| ARV | Erforderlich für Sanierungsprodukte | N/A anzeigen, wo anwendbar |
| Requested Loan | Positive Währung | Negative Werte zurückweisen |
| FICO | 300–850 | Ungültigen Score zurückweisen |
| Experience Tier | Nur Dropdown | Abruffehler verhindern |
| Loan Term | 12 / 18 / 24 Monate | Andere Werte zurückweisen |
| Short Interest Days | 0–30 | Ungültige Eingabe zurückweisen |
| Buy Rate Lookup | XLOOKUP mit Rückfallwert | "Check Risk Rules" |
| Division Operations | IFERROR-Wrapper | 0 zurückgeben statt Excel-Fehler |
| Text Lookups | TRIM + UPPER | Abstands- und Groß-/Kleinschreibungs-Abweichungen verhindern |
| Margin Check | Vergleich gegen Mindest-Spread | "Below Margin" zurückgeben |
| Eligibility | Alle Kreditprüfungsflags bewerten | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Weitere Tools dieser Reihe

Der **RTL-Darlehensrechner und Preisgestalter** ist Teil einer wachsenden Sammlung leichter operativer Entscheidungsunterstützungswerkzeuge, die für Fachleute gebaut wurden, die verlässliche Analysen ohne Implementierung von Unternehmenssoftware benötigen.

Jedes Tool folgt denselben Prinzipien:

- Keine Registrierung erforderlich
- Keine Installation erforderlich
- Verfügbar in Browser- und Excel-Editionen
- Formelgetrieben statt makroabhängig
- Gebaut für wiederholbare operative Entscheidungen statt einmalige Berichterstattung

| Tool | Zweck |
|------|---------|
| Construction Estimating System | Standardisierung von Projektkalkulation, Baugruppen, Angebotspreisen und Kostentracking. |
| Inventory Forecasting & Reorder Planner | Prognose der Lagerbedarfe, Identifizierung des Nachbestellzeitpunkts und Überwachung des Bestandsrisikos. |
| Retail & Maquila Inventory Ledger | Verfolgung von Bestandsbewegungen auf Stückebene, Produktion, Fehlern und Verteilung. |
| Unified Personal & Business Budget Framework | Konsolidierung von privatem und geschäftlichem Cashflow in einem einzigen Finanzplanungsmodell. |
| Cross-Border VAT Compliance Dashboard | Überwachung von Mehrwertsteuerpflichten über mehrere Länder und Verkaufskanäle hinweg. |
| Project Financial Control Dashboard | Vergleich von Budget, Bindungen, Rechnungen, Fortschrittsabrechnungen und Projektrentabilität. |
| Coffee Shop Operations Audit Toolkit | Bewertung der operativen Café-Leistung mit standardisierter Audit-Bewertung und KPI-Analyse. |

---

## Haftungsausschluss

Diese Arbeitsmappe ist als analytisches Entscheidungsunterstützungswerkzeug gedacht.

Sie stellt **keine** dar:

- Rechtsberatung,
- Kreditberatung,
- Kreditprüfungsgenehmigung,
- Buchhaltungsberatung,
- regulatorische Compliance-Zertifizierung,
- Anlageempfehlung.

Alle Darlehensentscheidungen bleiben den Kreditvergaberichtlinien der Institution, geltenden Vorschriften, Investorenanforderungen und der endgültigen Kreditgenehmigung unterworfen.

Benutzer sind dafür verantwortlich, alle Annahmen, Preisparameter, Gebührenpläne und Kreditprüfungsregeln zu verifizieren, bevor sie sich auf die generierten Ausgaben verlassen.

---

## Danksagung

Dieses Projekt spiegelt gängige Kreditprüfungspraktiken wider, die im Residential Transitional Lending verwendet werden, einschließlich Brückendarlehen, Fix-and-Flip-Finanzierung, Sanierungsdarlehen und Wohnungsbaudarlehen.

Seine Architektur betont Transparenz, Wiederholbarkeit und operative Konsistenz, damit Preisentscheidungen reproduziert, überprüft und auditiert werden können, statt von individuellem Tabellenkalkulationswissen abzuhängen.

---

**Apache License 2.0 © 2026**

Gebaut als Teil einer breiteren Sammlung leichter operativer Entscheidungsunterstützungswerkzeuge für Finanzen, Bau, Bestandsverwaltung und Geschäftsbetrieb.
