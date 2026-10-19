[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# RTL-leningcalculator en prijsbepaler

## Lichtgewicht beslissingsondersteunende tool voor residentiële transitieleningen voor nauwkeurige leningsstructurering, prijsbepaling, geschiktheidsvalidatie en klantklare prijsopgaven

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Status](https://img.shields.io/badge/Version-Stable-brightgreen)

**Dimensioner, valideer en prijs residentiële transitieleningen consistent in enkele minuten—zonder installatie, zonder programmeren en zonder de propriëtaire prijslogica bloot te leggen. Beschikbaar als zowel een browserversie als een Excel-werkmap.**

**Geen registratie. Geen installatie. Gratis in uw browser.**

Probeer de browserversie gratis. Als u de Excel-versie nodig heeft, kunt u die kopen met een 30-daagse geld-terug-garantie zonder vragen.
>
> 🌐 **Openen in browser**  
> [*HTML-versie*](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> 📥 **Excel downloaden**  
> [*Excel-download*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Wat dit u helpt bij te houden

- Leninggeschiktheid tegen de beleningslimieten van de kredietbeoordeling voordat een prijsopgave wordt uitgebracht.
- Werkelijke LTV, LTC, LTP en LTARV over verschillende structuren van residentiële transitieleningen heen.
- Financieringsbehoeften van de kredietnemer, netto financieringsopbrengst en geschatte benodigde cash bij afsluiting.
- Prijsconsistentie over FICO-niveaus, beleningsniveaus en prijsaannames van de geldgever heen.
- Margebescherming door leningen te identificeren die onder interne spreadvereisten zijn geprijsd.
- Klantklare leningvoorwaarden gegenereerd uit één kredietbeoordelingsworkflow in plaats van handmatig samengestelde berekeningen.

---

## Snelle startworkflow

### 1. Aannames voor kredietbeoordeling configureren

Administratieve gebruikers definiëren de leningparameters eenmaal op het speciale werkblad Pricing & Assumptions. Deze omvatten beleningslimieten, prijsrasters, servicevergoedingen, spreadvereisten, leningprogramma's en drempels voor kredietbeoordeling. Deze instellingen vereisen normaal gesproken alleen periodiek onderhoud in plaats van dagelijkse aanpassing.

---

### 2. Een nieuw leningsscenario invoeren

Open het werkblad **Inputs** en vul de gevraagde informatie in.

Typische informatie omvat:

- Aankoopprijs
- Huidige waarde
- Renovatiebudget
- Waarde na reparatie (ARV)
- Gevraagde leningbedrag
- FICO-score van de kredietnemer
- Ervaring van de kredietnemer
- Liquide middelen
- Leningstermijn
- Gevraagde rentevoet

Keuzemenu's en validatieregels verminderen onjuiste invoeren, terwijl voorwaardelijke opmaak automatisch velden uitschakelt die niet van toepassing zijn op het geselecteerde leningprogramma.

---

### 3. Resultaten direct bekijken

Schakel over naar de pagina Offerteoverzicht.

Alle kredietbeoordelingsberekeningen werken automatisch bij, waaronder:

- Leninggeschiktheid
- Beleningsmetrics
- Prijsvalidatie
- Cash bij afsluiting
- Netto financiering
- Vooruitbetaalde rente
- Afwikkelingsramingen

Geen handmatige berekeningen of aparte prijswerkbladen vereist.

---

### 4. Herhalen voor elke nieuwe lening

Elke extra lening vereist alleen het vervangen van de invoeren van de kredietnemer.

Het is niet nodig om formules opnieuw op te bouwen, berekeningen te wijzigen of rapporten opnieuw te ontwerpen. De prijsengine blijft herbruikbaar over bruikleningen, Fix-and-Flip-leningen, zware renovatie, lichte renovatie en bouwfinancieringsscenario's heen.

**Stel de parameters voor kredietbeoordeling eenmaal in. Voer het leningsscenario in. Bekijk de prijs. Genereer de prijsopgave. Herhaal wanneer een andere lening moet worden beoordeeld.**

---

## Waarom ik dit heb gebouwd

De kredietbeoordeling van residentiële transitieleningen lijkt vaak eenvoudig omdat ervaren geldgevers de belangrijkste ratio's die zij willen goedkeuren al kennen. In werkelijkheid gebeuren de meeste prijsfouten lang voordat een lening de commissiebeoordeling bereikt.

Het probleem is zelden het afzonderlijk berekenen van LTV of LTC. Het probleem is om elke regel voor kredietbeoordeling gelijktijdig te evalueren terwijl de rentabiliteit van de geldgever ook wordt beschermd.

Een verwerker zou een acceptabele LTV kunnen berekenen maar over het hoofd zien dat de gevraagde rentevoet de minimaal vereiste spread niet langer haalt. Een andere bemiddelaar kan een aantrekkelijke rente offreren die past bij de verwachtingen van de kredietnemer maar onbedoeld onder de vereiste inkooprente van de geldgever prijst. Een derde transactie kan aan de beleningsvereisten voldoen maar toch aanzienlijk meer cash van de kredietnemer vereisen dan verwacht, omdat vooruitbetaalde rente en servicevergoedingen de beschikbare financiering verminderen.

In plaats van te vertrouwen op meerdere losstaande spreadsheets of de richtlijnen voor kredietbeoordeling handmatig regel voor regel te controleren, wilde ik een herbruikbaar analytisch kader dat elke belangrijke beperking voor kredietbeoordeling samen evalueert.

Bijvoorbeeld:

**Voor**

- De LTV ziet er acceptabel uit.
- De kredietnemer krijgt een mondelinge prijsopgave.
- De prijsreview ontdekt later onvoldoende spread voor de geldgever.
- De prijsopgave moet worden herzien.
- Het vertrouwen van de kredietnemer daalt.
- De interne verwerkingstijd neemt toe.

**Na**

De werkmap evalueert belening, prijs, spreadbescherming, afwikkelingskosten, liquiditeitsvereisten en geschiktheid samen voordat de prijsopgave wordt uitgebracht. De geldgever weet onmiddellijk of het scenario slaagt, een uitzondering vereist of niet moet worden voortgezet.

Deze werkmap is niet simpelweg een rekenmachine. Het verpakt de redenering achter kredietbeoordeling in een reproduceerbaar beslissingsondersteunend proces dat inconsistente leningsstructurering tussen verschillende gebruikers vermindert.

---

## Veelvoorkomende RTL-uitleningsproblemen die dit oplost

| Probleem | Zonder deze tool | Met deze tool |
|------------|-----------------|----------------|
| Lening goedgekeurd met slechts één beleningsratio | Belangrijke limieten voor kredietbeoordeling kunnen tot de eindcontrole over het hoofd worden gezien | Alle belangrijke beleningsratio's worden samen geëvalueerd voordat een prijsopgave wordt gegeven |
| Handmatige prijzing | Verschillende bemiddelaars noemen verschillende rentes voor identieke kredietnemers | De prijs wordt consistent gegenereerd met gecentraliseerde prijsregels |
| Verborgen erosie van de rentabiliteit | Leningen lijken acceptabel maar schenden de minimale margevereisten | Spreadvalidatie signaleert onmiddellijk prijzing onder de vereisten van de geldgever |
| Onverwachte cashbehoefte van de kredietnemer | Afwikkelingskosten worden laat bij afsluiting ontdekt | Cash bij afsluiting en netto financiering worden berekend tijdens de initiële structurering |
| Leninguitzonderingen te laat geïdentificeerd | Meerdere revisies vertragen de kredietbeoordeling | Uitzonderingsscenario's worden onmiddellijk uitgelicht voor beoordeling door het management |
| Interne prijslogica blootgesteld | Gevoelige berekeningen van de inkooprente worden zichtbaar voor externe gebruikers | Interne prijsbladen blijven beschermd in bemiddelaargerichte versies |

---

## Voor wie dit is

Deze werkmap is ontworpen voor professionals die betrokken zijn bij residentiële transitieleningen, waaronder:

- Particuliere geldgevers
- Niet-bancaire geldgevers
- Leningbemiddelaars
- Leningverwerkers
- Kredietbeoordelaars
- Kapitaalmarktteams
- Kleine uitlenerijen die gestandaardiseerde leningprijzen nastreven
- Kredietteams die brug-, renovatie- en bouwleningen beoordelen

Het is bijzonder nuttig voor organisaties die een lichtgewicht workflow voor kredietbeoordeling nodig hebben zonder een volledig Loan Origination System (LOS) te implementeren.

Dit is **niet** bedoeld om ondernemingsuitleningsplatforms, servicingsoftware of compliancemanagementsystemen te vervangen.

Geen spreadsheet-expertise vereist. Open de browserversie of Excel-werkmap, voer de leninginformatie in en begin onmiddellijk met het beoordelen van leningsscenario's.

---

## Over

Ik bouw lichtgewicht analytische tools voor situaties waarin te veel operationele variabelen gelijktijdig moeten worden overwogen. In plaats van ondernemingssoftware te vervangen, verpakken deze werkmappen praktische besluitvorming in herbruikbare kaders die teams helpen met minder handmatige inspanning consistente conclusies te bereiken.

De **RTL-leningcalculator en prijsbepaler** volgt die filosofie door regels voor kredietbeoordeling, prijslogica, beleningsvalidatie, afwikkelingsberekeningen en het genereren van prijsopgaven samen te brengen in één gestructureerde workflow. De centrale vraag is altijd dezelfde: **Welke informatie moet op één plek zichtbaar zijn om de volgende uitleningbeslissing vol vertrouwen te nemen?**
## Technische details

<details>
<summary><strong>Voor technische beoordelaars, Excel-beoefenaars en medewerkers</strong></summary>

---

## Werkmapsarchitectuur

De werkmap volgt een gelaagde architectuur die gebruikersinteractie, bedrijfsregels, analytische berekeningen en presentatie scheidt. Dit voorkomt accidentele wijziging van de prijslogica terwijl de dagelijkse werking eenvoudig blijft voor leningbemiddelaars.

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

## Verantwoordelijkheden van werkbladen

| Werkblad | Doel | Bewerkbaar |
|------------|---------|----------|
| 01_ReadMe | Instructies, versiegeschiedenis, beheerdersdocumentatie | Ja |
| 02_Inputs | Kredietnemerinformatie en gevraagde leningvoorwaarden | Ja |
| 03_Pricing_&_Assumptions | Inkooprenterasters, beleningsregels, prijsaannames | Alleen beheerders |
| 04_Calc_Engine | Kredietbeoordelingsberekeningen, prijsengine en validatie | Nee |
| 05_Quote_Summary | Klantgericht printbaar voorwaardenblad | Nee |

---

## Gegevensstroom

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

Elke uitvoer die aan gebruikers wordt weergegeven, komt uit de berekeningsengine. Er worden geen waarden handmatig in de definitieve prijsopgave ingevoerd.

---

## Beveiligingsstrategie

De werkmap wordt opzettling gecompileerd in twee distributievormen.

| Versie | Beoogde gebruikers | Beschermde componenten |
|---------|----------------|----------------------|
| Interne versie | Principals, kredietbeoordelaars, operaties | Alle werkbladen zichtbaar met beheerderswachtwoord |
| Bemiddelaarsversie | Leningbemiddelaars | Prijstabellen en berekeningsengine verborgen met xlSheetVeryHidden |

Aanvullende beschermingsmaatregelen omvatten:

- Bescherming van de werkmapstructuur
- Verborgen formules
- Vergrendelde berekeningscellen
- Beschermde prijsrasters
- Verborgen formulebalk (bemiddelaarsversie)
- Met wachtwoord beschermde werkbladstructuur

Deze aanpak beschermt de propriëtaire prijs van de geldgever zonder twee onafhankelijke werkmappen te onderhouden.

---

## Drie valkuilen die zelfs ervaren leningbemiddelaars vangen

---

## Valkuil 1 — Alleen naar de LTV kijken

Veel geldgevers concentreren zich instinctief op de loan-to-value-ratio omdat dat de meest vertrouwde maatstaf voor kredietbeoordeling is.

Helaas vertrouwt transitieleiding zelden op slechts één beleningsratio.

### Onjuiste beslissing

Aankoopprijs

```
$400,000
```

Gevraagde lening

```
$320,000
```

Huidige waarde

```
$420,000
```

Berekende LTV

```
76.2%
```

De bemiddelaar concludeert:

> "De lening past binnen het beleid."

Echter...

Renovatiebudget

```
$160,000
```

Totale projectkosten

```
$560,000
```

Werkelijke LTC

```
57.1%
```

Werkelijke LTARV

```
88%
```

De LTARV overschrijdt het interne beleid.

De lening valt in werkelijkheid buiten de uitleningsrichtlijnen.

### Juiste aanpak

Evalueer:

- LTV
- LTC
- LTARV
- LTP

voordat u de geschiktheid bepaalt.

<details>

<summary>Formulereferentie</summary>

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

Resultaat:

De werkmap evalueert automatisch elke beleningsratio samen voordat een status Pass, Exception of Fail wordt toegekend.

---

## Valkuil 2 — Offreren voordat de marge is gecontroleerd

Een kredietnemer vraagt om een aantrekkelijke rente.

De bemiddelaar verlaagt de rentevoet om concurrerend te blijven.

Alles lijkt acceptabel.

Later...

Het secundaire marketing ontdekt dat de spread van de geldgever onder interne minima is gezakt.

De prijsopgave moet worden herzien.

### Onjuiste beslissing

Rente van de kredietnemer

```
10.00%
```

Inkooprente

```
8.20%
```

Spread

```
1.80%
```

Minimaal vereiste spread

```
2.50%
```

De transactie ligt in werkelijkheid onder de rentabiliteitsvereisten van de geldgever.

### Juiste aanpak

Elke prijsopgave zou de prijs moeten valideren voordat deze wordt gepresenteerd.

<details>

<summary>Formulereferentie</summary>

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

In plaats van het probleem tijdens de eindcontrole te ontdekken, signaleert de werkmap onmiddellijk:

```
Below Margin
```

waardoor de prijs kan worden gecorrigeerd voordat de kredietnemer een prijsopgave ontvangt.

---

## Valkuil 3 — De benodigde cash bij afsluiting onderschatten

Veel kredietnemers evalueren alleen het gevraagde leningbedrag.

Afwikkelingskosten verminderen de werkelijke opbrengst.

Het negeren van deze aftrek leidt vaak tot onrealistische verwachtingen van de kredietnemer.

### Voorbeeld

Gevraagde lening

```
$450,000
```

Tussentijdse rente

```
$6,250
```

Servicevergoeding

```
$2,250
```

Netto financiering

```
$441,500
```

Benodigde cash

```
$468,000
```

Werkelijke cash bij afsluiting

```
$26,500
```

Als de liquiditeit van de kredietnemer slechts

```
$18,000
```

bedraagt, kan de lening niet zonder extra middelen worden afgesloten.

### Juiste aanpak

Bereken de afwikkelingsopbrengst in plaats van aan te nemen dat het bruto leningbedrag gelijk is aan de beschikbare financiering.

<details>

<summary>Formulereferentie</summary>

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

De werkmap identificeert liquiditeitstekorten voordat afsluitingsdocumenten worden opgesteld.

---

## Voorbeeldscenario

Beschouw de volgende Fix-and-Flip-transactie.

| Post | Waarde |
|------|------:|
| Aankoopprijs | $300,000 |
| Renovatiebudget | $70,000 |
| Huidige waarde | $310,000 |
| ARV | $465,000 |
| Gevraagde lening | $340,000 |
| FICO | 726 |
| Ervaring | 6+ Projects |
| Rentevoet | 11.25% |
| Leningstermijn | 12 Months |

De prijsengine haalt de overeenkomstige inkooprente op basis van het FICO-niveau van de kredietnemer en de berekende belening.

De berekeningsengine bepaalt vervolgens:

- Werkelijke LTV
- Werkelijke LTC
- Werkelijke LTP
- Werkelijke LTARV
- Spread
- Netto financiering
- Cash bij afsluiting
- Geschatte winst van de geldgever

Stel dat de resulterende metrics zijn:

| Metric | Resultaat |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Geschiktheid | Exception Needed |

Hoewel de prijs rendabel blijft, overschrijdt de belening de voorkeursdrempel voor LTV.

In plaats van de lening onmiddellijk af te wijzen, classificeert de werkmap deze als **Exception Needed**, waardoor het management compenserende factoren zoals ervaring van de kredietnemer, liquiditeit of extra onderpand kan beoordelen.

Deze gestructureerde workflow creëert een consistent proces voor kredietbeoordeling waarin prijs, belening, afwikkeling en rentabiliteit samen worden geëvalueerd in plaats van onafhankelijk.

---

## Formulereferentie

<details>

<summary>Beleningsberekeningen</summary>

| Berekening | Formule |
|-------------|---------|
| Werkelijke LTV | `Loan Amount ÷ As-Is Value` |
| Werkelijke LTC | `Loan Amount ÷ (Purchase + Rehab)` |
| Werkelijke LTP | `Loan Amount ÷ Purchase Price` |
| Werkelijke LTARV | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Prijsengine</summary>

| Formule | Doel |
|----------|----------|
| XLOOKUP | Inkooprente ophalen |
| INDEX + MATCH | Legacy-prijsopzoekactie |
| Spread | Rentevoet − Inkooprente |
| Spreadstatus | Margevalidatie |

De prijs gebruikt altijd exact opzoekgedrag met standaard foutafhandeling om ongeldige prijsuitvoer te voorkomen.

</details>

<details>

<summary>Afwikkelingsberekeningen</summary>

| Berekening | Doel |
|-------------|----------|
| Tussentijdse rente | Rente geïnd bij afsluiting |
| Servicevergoeding | Vergoeding afgetrokken over de leningstermijn |
| Netto financiering | Beschikbare middelen voor de kredietnemer |
| Cash bij afsluiting | Extra bijdrage van de kredietnemer |
| Liquiditeitstekort | Financieringstekort |

</details>

<details>

<summary>Geschiktheidsregels</summary>

De engine voor kredietbeoordeling evalueert:

- Maximale LTV
- Maximale LTC
- Maximale LTARV
- Prijsmarge
- Liquiditeit van de kredietnemer

Mogelijke uitkomsten:

- PASS
- EXCEPTION NEEDED
- FAIL

De algehele geschiktheid weerspiegelt altijd het meest beperkende resultaat van de kredietbeoordeling.

</details>

## Validatieregels

| Veld | Validatieregel | Foutgedrag |
|------|-----------------|----------------|
| Loan Type | Alleen keuzemenu | Ongeldige waarden afwijzen |
| Purchase Price | Groter dan nul | Nulberekeningen teruggeven |
| As-Is Value | Groter dan nul | Deling door nul voorkomen |
| Rehab Budget | Nul voor bruikleningen | Veld automatisch grijs gemaakt |
| ARV | Vereist voor renovatieproducten | N/A weergeven waar van toepassing |
| Requested Loan | Positieve valuta | Negatieve waarden afwijzen |
| FICO | 300–850 | Ongeldige score afwijzen |
| Experience Tier | Alleen keuzemenu | Opzoekfouten voorkomen |
| Loan Term | 12 / 18 / 24 maanden | Andere waarden afwijzen |
| Short Interest Days | 0–30 | Ongeldige invoer afwijzen |
| Buy Rate Lookup | XLOOKUP met terugvalwaarde | "Check Risk Rules" |
| Division Operations | IFERROR-omhulling | 0 teruggeven in plaats van Excel-fouten |
| Text Lookups | TRIM + UPPER | Verschillen in spaties en hoofdletters voorkomen |
| Margin Check | Vergelijken met minimale spread | "Below Margin" teruggeven |
| Eligibility | Alle flags voor kredietbeoordeling evalueren | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Andere tools in deze serie

De **RTL-leningcalculator en prijsbepaler** maakt deel uit van een groeiende collectie lichtgewicht operationele beslissingsondersteunende tools die zijn gebouwd voor professionals die betrouwbare analyses nodig hebben zonder ondernemingssoftware te implementeren.

Elke tool volgt dezelfde principes:

- Geen registratie vereist
- Geen installatie vereist
- Beschikbaar in browser- en Excel-edities
- Formulegedreven in plaats van macro-afhankelijk
- Gebouwd voor reproduceerbare operationele beslissingen in plaats van eenmalige rapportage

| Tool | Doel |
|------|---------|
| Construction Estimating System | Standaardiseren van projectraming, assemblages, offerteprijzen en kostentracking. |
| Inventory Forecasting & Reorder Planner | Voorspellen van voorraadvraag, identificeren van het moment van nabestelling en monitoren van voorraadrisico. |
| Retail & Maquila Inventory Ledger | Bijhouden van voorraadbewegingen op stukniveau, productie, defecten en distributie. |
| Unified Personal & Business Budget Framework | Consolideren van persoonlijke en zakelijke cashflow in één financieel planningsmodel. |
| Cross-Border VAT Compliance Dashboard | Monitoren van btw-verplichtingen over meerdere landen en verkoopkanalen. |
| Project Financial Control Dashboard | Vergelijken van budget, toezeggingen, facturen, voortgangsfacturatie en projectrendabiliteit. |
| Coffee Shop Operations Audit Toolkit | Evalueren van operationele prestaties van het café met gestandaardiseerde auditscores en KPI-analyse. |

---

## Disclaimer

Deze werkmap is bedoeld als analytisch beslissingsondersteunend middel.

Het vormt **geen**:

- juridisch advies,
- advies over uitlening,
- goedkeuring van kredietbeoordeling,
- boekhoudkundige begeleiding,
- certificering van naleving van regelgeving,
- beleggingsaanbeveling.

Alle leningbeslissingen blijven onderworpen aan het uitleningsbeleid van de instelling, de toepasselijke regelgeving, de vereisten van investeerders en de definitieve kredietgoedkeuring.

Gebruikers zijn verantwoordelijk voor het verifiëren van alle aannames, prijsparameters, vergoedingenschema's en regels voor kredietbeoordeling voordat zij zich op de gegenereerde uitvoer verlaten.

---

## Met dank aan

Dit project weerspiegelt gangbare praktijken voor kredietbeoordeling die worden gebruikt bij residentiële transitieleningen, waaronder bruikleningen, Fix-and-Flip-financiering, renovatieleningen en financiering van woningbouw.

De architectuur benadrukt transparantie, reproduceerbaarheid en operationele consistentie, zodat prijsbeslissingen kunnen worden gereproduceerd, beoordeeld en geaudit in plaats van te afhangen van individuele spreadsheetkennis.

---

**Apache License 2.0 © 2026**

Gebouwd als onderdeel van een bredere collectie lichtgewicht operationele beslissingsondersteunende tools voor financiën, bouw, voorraadbeheer en bedrijfsvoering.
