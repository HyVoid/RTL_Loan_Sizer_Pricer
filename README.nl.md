[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# RTL Loan Sizer & Pricer: Gratis Leningcalculator voor Residentiële Transitieleningen & Fix-and-Flip Excel-sjabloon voor Kredietbeoordeling
<img width="1245" height="1209" alt="image" src="https://github.com/user-attachments/assets/856c2ddf-16a5-4212-a162-b3e82ab67dcc" />


![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser Web App and Offline Excel Workbook](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Category: RTL Underwriting and Loan Pricing Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Release Status: Production Stable](https://img.shields.io/badge/Version-Stable-brightgreen)

**RTL Loan Sizer & Pricer** is een kant-en-klare **calculator voor residentiële transitieleningen (RTL)**, een **prijsbepalingsengine voor Fix-and-Flip-leningen** en een **Excel-sjabloon voor hard money-kredietbeoordeling**. Dimensioneer Bridge-, renovatie- en nieuwbouwleningen (Ground-Up Construction), valideer LTV-, LTC-, LTP- en LTARV-limieten, controleer de yield spread tegen uw inkooprente en bereken de Cash-to-Close van de kredietnemer in minder dan één minuut. Test de browsertool gratis online zonder registratie, of koop de herbruikbare offline Excel-werkmap eenmalig met een 30-daagse geld-terug-garantie zonder vragen.

> **Gratis online tool (probeer direct in uw browser)**  
> [Start de gratis browsergebaseerde RTL-leningcalculator (directe Fix-and-Flip- en Bridge-leningdimensionering)](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> **Herbruikbare offline spreadsheet (eenmalige aankoop, 30-daagse geld-terug-garantie)**  
> [Haal de herbruikbare offline RTL Loan Sizer & Pricer Excel-sjabloon op via Theseus Workshop](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Pijnpunten bij kredietbeoordeling van residentiële transitieleningen & geautomatiseerde oplossingen

Deals in private lending lopen vast wanneer beleningslimieten, renteaanpassingen per kredietniveau en afsluitingsaftrekposten in aparte spreadsheets worden gecontroleerd. Deze RTL-tool koppelt elke veelvoorkomende rekenkloof direct aan geautomatiseerde output:

| Pijnpunt bij hard money- & RTL-leningen | Geautomatiseerde oplossing in deze RTL Loan Sizer | Gevolgde kernmetrics & output voor kredietbeoordeling |
| :--- | :--- | :--- |
| **Offreren van niet-geschikte deals vóór de kredietbeoordeling** | Controleert elke deal automatisch tegen uw programmalimieten vóór het uitgaan van een term sheet | Geschiktheidsstatus Pass / Exception / Decline voor Bridge-, renovatie- en bouwprogramma's |
| **Handmatig berekenen van slechts één beleningsratio** | Evalueert alle vier de RTL-dimensioneringsbeperkingen tegelijk en bindt de lening aan de strengste limiet | **LTV** (Loan-to-Value), **LTC** (Loan-to-Cost), **LTP** (Loan-to-Purchase) en **LTARV** (Loan-to-After-Repair-Value) |
| **Late Cash-to-Close-verrassingen voor de kredietnemer** | Trekt afsluitprovisie, vooruitbetaalde rente en servicekosten vooraf af tijdens de dealdimensionering | **Netto financieringsopbrengst**, totale **Cash-to-Close**, renovatieholdback-structuur en liquiditeitsreservecheck |
| **Inconsistente rentes tussen leninginitiators** | Haalt prijsaanpassingen uit één gecentraliseerde rentematrix gekoppeld aan kredietscore- en beleningstiers | **FICO-tierprijzen**, aanpassingen op kredietnemerervaring en gestandaardiseerde nominale rente-output |
| **Verborgen marge-erosie onder de inkooprente** | Markeert elke gevraagde rente onder uw interne yield spread-vloer direct | **Inkooprente van de geldgever**, **validatie van de minimale spread** en status van nettemargebescherming |
| **Traag handmatig samenstellen van offertes tijdens piekperiodes** | Consolidieert invoer, beoordelingsregels en afsluitingsberekeningen in één klantklare weergave | Kant-en-klare **Quote Summary** en voorlopige uitsplitsing van de leningvoorwaarden |

---

## Snelstartgids: dimensioneer en prijs een Fix-and-Flip- of Bridgelening in 4 stappen

U kunt nu direct een testscenario draaien in de [gratis online RTL Loan Sizer web-app](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/), en verplaats uw dagelijkse pipeline daarna naar de offline Excel-werkmap zodra deze past bij uw leningsrichtlijnen.

### Stap 1. Stel uw kredietbeoordelingsregels en prijsraster eenmaal in

Configureer uw leningsparameters op het werkblad **Pricing & Assumptions**. Voer maximale beleningslimieten (LTV, LTC, LTP, LTARV), FICO-prijsrasters, afsluitprovisie, servicevergoedingen, minimale spreadvereisten en ondersteunde leningprogramma's in. Na de eerste setup werkt u dit tabblad alleen bij wanneer uw kapitaalpartner of kredietcommissie de richtlijnen wijzigt.

### Stap 2. Plak dealgegevens van kredietnemer en pand in Inputs

Open het werkblad **Inputs** en voer de dealgegevens in:

- Aankoopprijs en As-Is-waarde van het pand
- Renovatie-/bouwbudget en waarde na renovatie (ARV)
- Gevraagd leningbedrag en looptijd
- FICO-score van de kredietnemer, eerdere flip-ervaring en geverifieerde liquide middelen
- Gevraagde nominale rente en geselecteerd leningprogramma (Bridge, lichte renovatie, zware renovatie of bouw)

Ingebouwde dropdownmenu's en datavalidatie blokkeren ongeldige invoer. Voorwaardelijke opmaak maakt velden grijs die niet van toepassing zijn op het gekozen leningprogramma.

### Stap 3. Lees de geautomatiseerde resultaten voor kredietbeoordeling, prijzen en Cash-to-Close

Open het werkblad **Quote Summary** om de volledige uitsplitsing van de deal op één plek te bekijken:

- Geschiktheidsuitspraak voor de lening en exception-markeringen
- Bepalende beleningsmetrics (LTV, LTC, LTP en LTARV)
- Rentevalidatie tegen de inkooprente en de regels voor minimale spread
- Vooruitbetaalde rente, afwikkelingsramingen, netto opbrengst en Cash-to-Close van de kredietnemer

### Stap 4. Schakel over naar de herbruikbare offline Excel-werkmap voor dagelijkse pipeline-deals

Prijzen voor residentiële transitieleningen omvatten meerlagige kredietbeoordelingslogica, toch hoeft u nooit een formule te schrijven, kapotte celverwijzingen te debuggen of formules door een kolom te slepen. Elke regel en automatisch bijgewerkte formule is al vooraf gebouwd in de Excel-sjabloon.

Download de werkmap, plak uw eigen dealcijfers in de invoercellen en bekijk heldere kredietbeoordelingsbeslissingen in minder dan één minuut. Zelfs een beginner zonder spreadsheet-ervaring krijgt direct gestructureerde commerciële analyse, waardoor drukke seizoensuren vrijkomen voor bemiddelaarsgesprekken, kredietnemeronderhandelingen en dealafsluitingen.

**Waarom leningsteams overstappen van de gratis browserproefversie naar de betaalde offline Excel-werkmap:**

- **Eenmalige aankoop, onbeperkt hergebruik:** Betaal één keer in plaats van terugkerende maandelijkse SaaS-abonnementen voor enterprise Loan Origination Systems (LOS) of cloud-prijsengines. Vervang de invoer en hergebruik dezelfde vaste workflow voor elke deal.
- **100% lokale gegevensprivacy:** Sla het bestand op en voer het lokaal uit op uw eigen machine. Gevoelige kredietnemergegevens, interne inkooprentes en spreadvloeren van de geldgever staan nooit op cloudservers van derden.
- **Risicovrije garantie:** De browserversie is gratis te testen online. De downloadbare Excel-werkmap is een betaald product met een **30-daagse, geen-vragen-gestelde geld-terug-garantie**.

> **Klaar om uw kredietbeoordelingsworkflow offline te standaardiseren?**  
> [Download de herbruikbare offline RTL Loan Sizer & Pricer Excel-sjabloon (eenmalige aankoop, 30-daagse geld-terug-garantie)](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## De bedrijfslogica & methodologie: hoe geautomatiseerde RTL-kredietbeoordeling verborgen beslissingsblinde vlekken voorkomt

De meeste prijsfouten in private vastgoedfinanciering ontstaan lang vóórdat een leningdossier de kredietcommissie bereikt. Zelfs ervaren initiators maken kostbare offertefouten wanneer ze ratio's één voor één in losstaande werkbladen berekenen. Voor nieuwkomers in hard money- of Fix-and-Flip-leningen doden vier commerciële blinde vlekken stilletjes deals of de winst van de geldgever.

### 1. De blinde vlek van de enkele ratio (waarom een geslaagde LTV toch kan mislukken)

**Objectief feit:** Een Fix-and-Flip-lening die er veilig uitziet bij 75% As-Is-LTV kan toch een 90% LTC-limiet of 70% LTARV-limiet overschrijden zodra een groot renovatiebudget meeweegt.  
**Hoe dit model het oplost:** De engine berekent LTV, LTC, LTP en LTARV parallel en dwingt het laagste toegestane leningbedrag af. U ziet de bepalende beperking vóór het offreren van voorwaarden aan een kredietnemer.

### 2. De blinde vlek van rente-versus-spread (een deal winnen terwijl u marge verliest)

**Objectief feit:** De nominale rente van een concurrent matchen duwt de lening vaak onder uw interne inkooprente of minimale yield spread nadat FICO- en beleningsprijskortingen zijn toegepast.  
**Hoe dit model het oplost:** Elke geofferde rente wordt automatisch getest tegen uw gecentraliseerde inkooprentematrix en de minimale spreadvereiste. Schendt een deal uw winstvloer, dan markeert het werkblad dit direct zodat u kunt herprijsen of afsluitprovisie kunt toevoegen vóór het uitgeven van een term sheet.

### 3. De blinde vlek van Cash-to-Close (deals die dagen vóór de afwikkeling sterven)

**Objectief feit:** Eerste keer kredietnemers en junior verwerkers gaan er vaak van uit dat de aanbetaling gelijk is aan het totale benodigde bedrag. Vooruitbetaalde rente, afsluitkosten, servicekosten en liquiditeitsreserveregels verminderen de netto opbrengst en verhogen het benodigde bedrag bij de afsluiting.  
**Hoe dit model het oplost:** De werkmap berekent netto financiering, voorafgaande aftrekposten en de totale Cash-to-Close op dag één. Kredietnemers kennen hun echte geldbehoefte direct, wat laat afvallende deals vermindert.

### 4. De blinde vlek van prijslekkage (blootstelling van propriëtaire inkooprentes)

**Objectief feit:** Een ontgrendeld prijsspreadsheet aan externe bemiddelaars of junior medewerkers geven legt uw wholesale-inkooprentes, kapitaalkosten en interne margegegevens bloot.  
**Hoe dit model het oplost:** Prijstabellen en spreadformules staan op een apart assumptions-tabblad, vergrendelbaar en verbergbaar in versies voor leninginitiators, zodat gevoelige economie privé blijft terwijl snelle selfservice-offertes behouden blijven.

### Verschil in de dagelijkse praktijk: voor en na

**Voor (handmatig offreren)**
1. De initiator controleert de As-Is-LTV in een snelle calculator en geeft een mondelinge offerte aan de kredietnemer.
2. De kredietbeoordeling ontdekt later een LTARV-overschrijding en een spreadtekort onder de inkooprente van de geldgever.
3. Het team herziet de offerte naar beneden en verhoogt de vereiste Cash-to-Close van de kredietnemer.
4. Het vertrouwen van de kredietnemer daalt, afsluitingsvertragingen stapelen zich op en medewerkers besteden uren aan één dossier.

**Na (geautomatiseerde RTL Loan Sizer-workflow)**
1. De initiator voert pandcijfers, renovatiebudget en FICO van de kredietnemer eenmaal in.
2. De werkmap controleert beleningslimieten, spreadvloer, afsluitingsaftrekposten en liquiditeitsreserves tegelijk, in seconden.
3. Het team weet direct of de deal doorgaat, een management-exception vereist of afgewezen moet worden vóór het versturen van een offerte.

---

## Handmatig hard money-offreren vs. geautomatiseerde RTL Loan Sizer: operationele vergelijking

| Knelpunt bij leningen voor residentiële transities | Risico van ad-hoc spreadsheets & handmatig offreren | Gestandaardiseerde RTL Loan Sizer-workflow |
| :--- | :--- | :--- |
| **Dimensionering op één ratio** | Goedkeuren op LTV alleen mist LTC-, LTP- of LTARV-limieten tot de kredietcommissie | Evalueert LTV, LTC, LTP en LTARV tegelijk en dwingt de bepalende leninglimiet af vóór het offreren |
| **Handmatige rentekaart-opslagen** | Verschillende adviseurs offreren conflicterende rentes en punten voor identieke FICO- en beleningsprofielen | Haalt uniforme rentes en aanpassingen uit één gecentraliseerd FICO- en beleningsprijsraster |
| **Onopgemerkte margecompressie** | Leningen passeren beleningschecks terwijl ze onder de interne inkooprente en yield spread-vloeren worden geprijsd | Ingebouwde spreadvalidatie markeert offertes onder de minimale margevereisten direct |
| **Onverwachte Cash-to-Close voor de kredietnemer** | Vooruitbetaalde rente, afsluitprovisie en servicekosten komen laat boven water, vlak bij de afsluiting | Berekent netto opbrengst, aftrekposten en Cash-to-Close tijdens de initiële structurering |
| **Late ontdekking van beoordelings-excepties** | Meerdere term sheet-revisies stallen pipelines en frustreren bemiddelaars | Brengt beleidsexcepties meteen onder de aandacht voor managementgoedkeuring |
| **Blootgestelde wholesale-prijslogica** | Gedeelde handmatige werkmappen lekken interne inkooprentes en marges naar buitenstaanders | Scheidt beschermde prijsaannames van invoer- en offertesamenvattingsbladen |

---

## Wie gebruikt deze RTL-leningcalculator: rolgebaseerde use cases voor private geldgevers, bemiddelaars en hard money-teams

Deze tool past in specifieke dagelijkse workflows binnen de industrie voor residentiële transitieleningen, zonder spreadsheetmodelleervaardigheden of zware enterprise-software:

| Rol / functietitel | Primaire zoek- & workflowbehoefte | Hoe ze RTL Loan Sizer & Pricer gebruiken |
| :--- | :--- | :--- |
| **Hard money- & private money-geldgevers** | Prijsspreadsheet voor hard money-leningen & dealdimensioneringsengine | Dwingt consistente LTV/LTC/LTARV-limieten af en beschermt de minimale spread van de geldgever bij elke offerte |
| **Hypothecaire bemiddelaars & leninginitiators (LO's)** | Fix-and-Flip-offertegenerator & pre-kwalificatietool voor kredietnemers | Zet ruwe pandcijfers en renovatiebudgetten om in heldere klantklare term sheets in minder dan één minuut |
| **Leningverwerkers & transactiecoördinatoren** | Cash-to-Close- & netto financieringscalculator voor Bridgeleningen | Verifieert vooruitbetaalde rente, servicekosten, liquiditeit en netto opbrengst vóór het opvragen van afsluitingsdocumenten |
| **Kredietanalisten & kredietbeoordelaars** | RTL-geschiktheidschecker & exception-screeningssjabloon | Auditeert multi-ratio beleningslimieten en markeert uitzonderlijke deals vóór de kredietcommissie |
| **Capital markets- & secundaire desk-teams** | Validatie van inkooprente & model voor yield spread van de geldgever | Beheert gecentraliseerde prijsrasters en bevestigt dat leningprijzen de secundaire verkoopdrempels halen |
| **Kleine private leningsfirma's & boutique debt funds** | Lichtgewicht LOS-alternatief in Excel-werkmap | Standaardiseert Bridge-, lichte renovatie-, zware renovatie- en nieuwbouwkredietbeoordeling zonder enterprise SaaS-kosten |
| **Vastgoedinvesteerders & house flippers** | Beginnersvriendelijke hard money-dealanalyse | Schat het maximale leningbedrag en het totale benodigde geld bij de afsluiting in vóór het indienen van een leningsaanvraag |

**Reikwijdte-opmerking:** Deze werkmap is gebouwd voor front-end leningsdimensionering, geschiktheidsvalidatie, prijscontroles en offertegeneratie. Leningbeheer, trekkingsboekhouding en compliancebeheer blijven in aparte servicing- en complianceplatformen.

---

## Veelgestelde vragen (RTL-dimensionering & Excel-sjabloon)

<details>
<summary><strong>Wat is het verschil tussen LTV, LTC, LTP en LTARV bij een residentiële transitielening?</strong></summary>

- **LTV (Loan-to-Value):** Leningbedrag gedeeld door de huidige As-Is-getaxeerde waarde van het pand.
- **LTP (Loan-to-Purchase):** Initiële acquisitie-uitkering gedeeld door de contractuele aankoopprijs.
- **LTC (Loan-to-Cost):** Totale lening gedeeld door de totale projectkosten (aankoopprijs plus renovatiebudget).
- **LTARV (Loan-to-After-Repair-Value):** Totale lening gedeeld door de verwachte waarde na renovatie (ARV) zodra de verbouwing klaar is.

Omdat hard money-geldgevers alle vier ratio's tegelijk begrenzen, bepaalt het laagste leningbedrag uw maximale toegestane leningomvang.
</details>

<details>
<summary><strong>Heb ik geavanceerde Excel-vaardigheden nodig om de offline sjabloon te gebruiken?</strong></summary>

Nee. Alle prijsrasters, beleningsformules en voorwaardelijke controles zijn vooraf geconfigureerd. U plakt alleen dealinvoer in de invoercellen op het tabblad **Inputs** en leest uw resultaten op het tabblad **Quote Summary**.
</details>

<details>
<summary><strong>Wat is het verschil tussen de gratis browserversie en de betaalde Excel-versie?</strong></summary>

De [gratis browsergebaseerde RTL-leningcalculator](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) laat u de kredietbeoordelingslogica direct online testen zonder account. De [betaalde offline Excel-werkmap](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan) geeft u een permanent lokaal bestand: aanpasbaar met eigen prijsrasters, per deal op te slaan, onbeperkt herbruikbaar voor een eenmalige betaling (met 30-daagse geld-terug-garantie) en volledig vrij van cloudservers van derden.
</details>

---

## Over Theseus Workshop

**Theseus Workshop** bouwt lichtgewicht, herbruikbare analytische werkmappen voor zakelijke en leningsbeslissingen waarbij te veel financiële variabelen tegelijk spelen. Elk sjabloon verpakt bewezen kredietbeoordelings- en commerciële analyselogica in een heldere offline Excel-workflow zodat kleine teams en solo-ondernemers in minuten tot consistente, verdedigbare beslissingen komen.

De **RTL Loan Sizer & Pricer** zet kredietbeoordelingslimieten, inkooprenteprijsregels, beleningsvalidatie, afwikkelingsaftrekposten en klantofferte-output op één scherm zodat u altijd weet of een deal werkt vóór het committeren van kapitaal.

Zoekt u meer kant-en-klare offline Excel-financiële modellen, prijsengines en operationele beslissingsondersteunende tools?  
[Verken de volledige catalogus met offline zakelijke & financiële Excel-sjablonen op Theseus Workshop (theseusworkshop.com)](https://www.theseusworkshop.com)

## Technische details

<details>
<summary><strong>Voor technische reviewers, Excel-practitioners en medewerkers</strong></summary>

---

## Werkmaparchitectuur

De werkmap volgt een gelaagde architectuur die gebruikersinteractie, bedrijfsregels, berekeningen en presentatie scheidt. Dit voorkomt accidentele wijziging van prijslogica terwijl de dagelijkse bediening eenvoudig blijft voor initiators.

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

## Verantwoordelijkheden per werkblad

| Werkblad | Doel | Bewerkbaar |
|------------|---------|----------|
| 01_ReadMe | Instructies, versiegeschiedenis, beheerdersdocumentatie | Ja |
| 02_Inputs | Informatie over de kredietnemer en gevraagde leningsvoorwaarden | Ja |
| 03_Pricing_&_Assumptions | Inkooprenterasters, beleningsregels, prijsaannames | Alleen beheerders |
| 04_Calc_Engine | Kredietbeoordelingsberekeningen, prijsengine en validatie | Nee |
| 05_Quote_Summary | Klantgericht, afdrukbaar term sheet | Nee |

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

Elke getoonde output komt uit de berekeningsengine; er worden geen waarden handmatig in de offerte ingevoerd.

---

## Beveiligingsstrategie

De werkmap is opzettelijk gecompileerd in twee distributieformaten.

| Versie | Beoogde gebruikers | Beveiligde componenten |
|---------|----------------|----------------------|
| Interne versie | Principals, kredietbeoordelaars, operations | Alle werkbladen zichtbaar met beheerderswachtwoord |
| Initiatorversie | Leninginitiators | Prijstabellen en berekeningsengine verborgen via xlSheetVeryHidden |

Aanvullende beveiligingsmaatregelen omvatten:

- Bescherming van de werkmapstructuur
- Verborgen formules
- Vergrendelde berekencellen
- Beveiligde prijsrasters
- Verborgen formulebalk (initiatorversie)
- Met wachtwoord beveiligde werkbladstructuur

Deze aanpak beschermt de propriëtaire prijzen van de geldgever zonder twee onafhankelijke werkmappen te onderhouden.

---

## Drie valkuilen die zelfs ervaren leninginitiators vangen

---

## Valkuil 1 — Alleen naar LTV kijken

Veel geldgevers richten zich instinctief op Loan-to-Value omdat dit de meest bekende kredietbeoordelingsmetric is.

Helaas vertrouwt transitielening zelden op slechts één beleningsratio.

### Verkeerde beslissing

Aankoopprijs

```
$400,000
```

Gevraagde lening

```
$320,000
```

As-Is-waarde

```
$420,000
```

Berekende LTV

```
76.2%
```

De initiator concludeert:

> "De lening valt binnen het beleid."

Maar...

Renovatiebudget

```
$160,000
```

Totale projectkosten

```
$560,000
```

Feitelijke LTC

```
57.1%
```

Feitelijke LTARV

```
88%
```

De LTARV overschrijdt het interne beleid.

De lening valt feitelijk buiten de leningsrichtlijnen.

### Juiste aanpak

Evalueer:

- LTV
- LTC
- LTARV
- LTP

vóór het bepalen van de geschiktheid.

<details>

<summary>Formuleverwijzing</summary>

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

De werkmap evalueert elke beleningsratio samen vóór toekenning van Pass-, Exception- of Fail-status.

---

## Valkuil 2 — Offreren vóór het controleren van de marge

Een kredietnemer vraagt een aantrekkelijke rente.

De initiator verlaagt de nominale rente om concurrerend te blijven.

Alles lijkt acceptabel.

Later...

Secundaire marketing ontdekt dat de spread onder de interne minima is gezakt.

De offerte moet worden herzien.

### Verkeerde beslissing

Rente kredietnemer

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

De transactie ligt feitelijk onder de winstgevendheidseisen van de geldgever.

### Juiste aanpak

Elke offerte moet op prijzen worden gevalideerd voordat deze wordt gepresenteerd.

<details>

<summary>Formuleverwijzing</summary>

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

In plaats van het probleem te ontdekken tijdens de eindreview, markeert de werkmap onmiddellijk:

```
Below Margin
```

zodat de prijzen kunnen worden gecorrigeerd voordat de kredietnemer een offerte ontvangt.

---

## Valkuil 3 — Het onderschatten van het geld dat bij de afsluiting nodig is

Veel kredietnemers beoordelen alleen het gevraagde leningbedrag.

Afwikkelingskosten verminderen de feitelijke opbrengst.

Het negeren van deze aftrekposten levert vaak onrealistische verwachtingen bij kredietnemers op.

### Voorbeeld

Gevraagde lening

```
$450,000
```

Short Interest

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

Feitelijke Cash-to-Close

```
$26,500
```

Als de liquiditeit van de kredietnemer slechts gelijk is aan

```
$18,000
```

kan de lening niet worden afgesloten zonder aanvullende middelen.

### Juiste aanpak

Bereken de afwikkelingsopbrengst in plaats van aan te nemen dat het bruto leningbedrag de beschikbare financiering is.

<details>

<summary>Formuleverwijzing</summary>

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

De werkmap identificeert liquiditeitstekorten voordat de afsluitingsdocumenten worden opgesteld.

---

## Voorbeeldscenario

Beschouw de volgende Fix-and-Flip-transactie.

| Onderdeel | Waarde |
|------|------:|
| Aankoopprijs | $300,000 |
| Renovatiebudget | $70,000 |
| As-Is-waarde | $310,000 |
| ARV | $465,000 |
| Gevraagde lening | $340,000 |
| FICO | 726 |
| Ervaring | 6+ projecten |
| Nominale rente | 11.25% |
| Looptijd | 12 maanden |

De prijsengine haalt de bijbehorende inkooprente op basis van FICO-tier en berekende belening op.

De berekeningsengine bepaalt vervolgens:

- Feitelijke LTV
- Feitelijke LTC
- Feitelijke LTP
- Feitelijke LTARV
- Spread
- Netto financiering
- Cash-to-Close
- Geschatte winst geldgever

Stel dat de resulterende metrics zijn:

| Metric | Resultaat |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Geschiktheid | Exception Needed |

Hoewel de prijzen winstgevend blijven, overschrijdt de belening de gewenste LTV-drempel.

In plaats van de lening direct af te wijzen, classificeert de werkmap deze als **Exception Needed**, zodat het management verzachtende factoren kan beoordelen: kredietnemerervaring, liquiditeit of aanvullend onderpand.

Deze gestructureerde workflow creëert een consistent beoordelingsproces waarin prijzen, belening, afwikkeling en winstgevendheid samen worden beoordeeld in plaats van afzonderlijk.

---

## Formuleverwijzing

<details>

<summary>Beleningsberekeningen</summary>

| Berekening | Formule |
|-------------|---------|
| Feitelijke LTV | `Loan Amount ÷ As-Is Value` |
| Feitelijke LTC | `Loan Amount ÷ (Purchase + Rehab)` |
| Feitelijke LTP | `Loan Amount ÷ Purchase Price` |
| Feitelijke LTARV | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Prijsengine</summary>

| Formule | Doel |
|----------|----------|
| XLOOKUP | Inkooprente ophalen |
| INDEX + MATCH | Verouderde prijsopslag |
| Spread | Nominale rente − Inkooprente |
| Spread Status | Margevalidatie |

Prijzen gebruiken altijd exacte opslag met standaard foutafhandeling om ongeldige output te voorkomen.

</details>

<details>

<summary>Afwikkelingsberekeningen</summary>

| Berekening | Doel |
|-------------|----------|
| Short Interest | Rente geïncasseerd bij de afsluiting |
| Servicevergoeding | Vergoeding ingehouden over de looptijd |
| Netto financiering | Middelen beschikbaar voor de kredietnemer |
| Cash-to-Close | Aanvullende bijdrage van de kredietnemer |
| Liquiditeitstekort | Financieringstekort |

</details>

<details>

<summary>Geschiktheidsregels</summary>

De kredietbeoordelingsengine evalueert:

- Maximale LTV
- Maximale LTC
- Maximale LTARV
- Prijsmarge
- Liquiditeit kredietnemer

Mogelijke uitkomsten:

- PASS
- EXCEPTION NEEDED
- FAIL

De algemene geschiktheid weerspiegelt altijd het strengste kredietbeoordelingsresultaat.

</details>

## Validatieregels

| Veld | Validatieregel | Foutgedrag |
|------|-----------------|----------------|
| Leningtype | Alleen dropdown | Ongeldige waarden afwijzen |
| Aankoopprijs | Groter dan nul | Nulberekeningen retourneren |
| As-Is-waarde | Groter dan nul | Delen-door-nul voorkomen |
| Renovatiebudget | Nul bij Bridgeleningen | Veld automatisch grijs |
| ARV | Vereist voor renovatieproducten | N/A tonen waar van toepassing |
| Gevraagde lening | Positief valutabedrag | Negatieve waarden afwijzen |
| FICO | 300–850 | Ongeldige score afwijzen |
| Ervaringstier | Alleen dropdown | Opslagfouten voorkomen |
| Looptijd | 12 / 18 / 24 maanden | Andere waarden afwijzen |
| Short Interest-dagen | 0–30 | Ongeldige invoer afwijzen |
| Inkooprente-opslag | XLOOKUP met terugvalwaarde | "Check Risk Rules" |
| Delingsoperaties | IFERROR-wrapper | 0 retourneren in plaats van Excel-fouten |
| Tekstopslagen | TRIM + UPPER | Spatie- en hoofdletterverschillen voorkomen |
| Margecontrole | Vergelijken met minimale spread | "Below Margin" retourneren |
| Geschiktheid | Alle kredietbeoordelingsvlaggen evalueren | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Andere tools in deze reeks

De **RTL Loan Sizer / Pricer** maakt deel uit van een groeiende verzameling lichtgewicht operationele beslissingsondersteunende tools voor professionals die betrouwbare analyse nodig hebben zonder enterprise-software.

Elke tool volgt dezelfde principes:

- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Waarom is geld altijd krap? — Prognosticeer toekomstige liquiditeit onder veranderende operationele en financiële aannames.
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Welke handelsstromen zijn daadwerkelijk winstgevend na valutaeffecten? — Meet de winstgevendheid van multivalutahandel over grensoverschrijdende operaties.
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Waar wordt persoonlijk en zakelijk geld gemengd of verkeerd toegewezen? — Splits persoonlijke en zakelijke geldstromen in onafhankelijk bijgehouden budgetsporen.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Creëert deze vastgoedaanwerving nog equity-waarde na renovatie- en exploitatieaannames? — Evalueer meergezinswoning-acquisitierendementen onder renovatiefinanciering en exploitscenario's.
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — Wat is een pand waard onder verschillende waarderingsmethoden? — Bereken pandwaarde volgens meerdere waarderingsmethoden, inclusief belasting- en kapitaaluitgavenmodellering.
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Worden gedeelde kosten eerlijk toegewezen, of dragen sommige activa niet hun werkelijke kosten? — Verdeel leveranciersfacturen over rechtspersonen en operationele activa met configureerbare toewijzingsmethoden.
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — Wat is elke deelnemer daadwerkelijk verschuldigd op basis van zijn instaptijdstip en de huidige poolwaarde? — Volg het eigendom van een beleggingspool continu op basis van NAV-eenhedenboekhouding.
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Welke operationele verplichtingen veroorzaken de komende twaalf weken een geldprobleem? — Verbind Shopify-verkopen, banktransacties, advertentie-uitgaven en voorraadaankopen tot één beslissingskader voor cashflow.
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — Heeft er voldoende relevante informatie veranderd om een prijsaanpassing te rechtvaardigen? — Stuur prijsaanbevelingen via configureerbare vangrails die onnodige omzetvolatiliteit voorkomen.
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — Wat veranderde deze periode werkelijk in de business en welke producten of zoekwoorden dreef dat? — Transformeer Amazon Seller Central SQP- en Sellerboard-exports naar gestandaardiseerde executive business reviews.
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Welke producten zijn winstgevend nadat alle productiekosten zijn toegewezen en welke vernietigen de marge? — Wijs fabrieksarbeid, nutsvoorzieningen, overhead en materiaalkosten per SKU toe voor echte unit economics.
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Welke orders zijn winstgevend na alle verborgen kosten en waar lekt geld weg? — Reconstrueer winstgevendheid per order door uitkeringen, verzend- en betalingskosten en marktplaatscommissies af te stemmen over multikanaal-e-commerce.
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Welke aannemersprojecten en klanten zijn daadwerkelijk winstgevend na alle projectkosten? — Verbind offerte-estimatie, projectuitvoering en actuele kostenregistratie tot één raamwerk voor aannemerswinstgevendheid.
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — Is de zaak echt winstgevend na alle ingrediënt-, arbeids- en exploitatiekosten? — Verbind receptkostprijs, verkoop, voorraadverbruik en exploitatiekosten tot één raamwerk voor winstgevendheid en cashflow.
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Welke vrachtboekingen zijn daadwerkelijk winstgevend na alle kosten, vergoedingen en valutaconversie? — Meet winstgevendheid per boeking door omzet, COGS, bank- en containerkosten af te stemmen over gemengde-valutatransacties.
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Welke containers en klanten zijn daadwerkelijk winstgevend over douane- en vlootoperaties heen? — Consolideer douaneafhandeling en vlootuitvoering tot één winstgevendheidsweergave op containerniveau.
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — Wat is er vandaag werkelijk verschuldigd na jaren transfers en opgelopen rente? — Stem langetermijnfondsoverdrachten en renteopbouw af tot een actueel openstaand saldo.
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — Hoe zien onze financiële overzichten eruit onder verschillende exploitatie- en financieringsscenario's? — Prognosticeer geïntegreerde financiële overzichten door omzet, kosten, werkkapitaal en schulden te koppelen in één model.
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — Hoeveel van de gerapporteerde marge komt werkelijk uit het gebouw zelf versus de toewijzing van zakelijke kosten? — Wijs gedeelde kosten toe over operationele eenheden, behoud brontransacties en stem resultaatenheden af op bedrijfstotalen.
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — Bij welke maximale grondverwervingsprijs wordt dit ontwikkelproject een bankbare investering? — Evalueer woningbouwontwikkelkansen door grondcomparables te screenen, bouwkosten te ramen en winst-op-kosten-drempels te berekenen.
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Behaalt dit bouwproject zijn doelmarge zodra sitelogistiek, verspillingsfactoren en gewijzigde vakmanstarieven zijn verwerkt? — Splits bouwhoeveelheden van volatiele vakmanstarieven en site-preliminaries om opslagen te cascaderen over inschrijvingsbudgetten en klantoffertes.
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Welke groothandelsprijzen en klantsegmenten behouden marge zodra vracht, rechten, betaaltermijnen en FX volledig zijn doorgerekend? — Bereken SKU-niveau landed costs, cost-to-serve en pocket-margin-prijsvallen om grensoverschrijdende groothandelswinstgevendheid te simuleren.
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — Wat te rekenen voor een custom-labelorder per hoeveelheidstier om concurrerend en winstgevend te blijven? — Bereken parametrische labelprijzen door substraatkosten per vierkante inch, setup-kosten en kwantumtier-kortingen te modelleren tegen concurrentbenchmarks.
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — Wat is de echte nettomarge per SKU zodra werkelijke landed costs en retailer-aftrekposten zijn verwerkt? — Stem PO-gebaseerde landed costs af op werkelijke vracht-, duty-, valuta- en drayagekosten en audit retailer-aftrekposten voor de nettomarge per SKU.
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Kunnen we deze week de aanstellingen, marketing en leveranciers doen zonder geld tekort te komen vóór de maandafsluiting? — Volg wekelijkse cash burn-pacing, MRR/ARR-waterfall-afwijkingen, retentiemetrics en salariskosten tegen budget vóór de maandafsluiting.
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — Raakt ons groeiplan zonder geld te zitten vóórdat cohortmonetisatie bijtrekt? — Prognosticeer meerjarige cash burn, runway, unit economics en fondsenwervingsverwatering vanuit bottom-up cohort- en bezettingsaannames.
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Is elke Shopify-winkel winstgevend zodra echte SKU-kosten, gedeelde kosten en bankkosten zijn afgestemd? — Stem multishop Shopify-exports af op SKU-COGS, toegewezen multivaluta-OPEX en bankafschriften voor een betrouwbare maandelijkse P&L.
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Welke toerboekingen genereren werkelijke nettowinst en positieve cashflow na leverancierskosten en B2B-incasso's? — Bereken tourprojectkosten per boeking, brutomarges, AR/AP-afwikkeling en operationele cashflow over meerdere valuta's.

| Tool | Doel |
|------|---------|
| Bouwkostencalculatiesysteem | Standaardiseer projectschattingen, assemblages, inschrijvingsprijzen en kostenregistratie. |
| Voorraadprognose & herbevoorrading-planner | Prognosticeer voorraadvraag, identificeer aanvultijdstippen en bewaak voorraadrisico. |
| Retail & maquila voorraadgrootboek | Volg stuksgewijze voorraadbewegingen, productie, defecten en distributie. |
| Geünificeerd persoonlijk & zakelijk budgetkader | Consolidieer persoonlijke en zakelijke cashflow tot één financieel planningsmodel. |
| Grensoverschrijdend BTW-compliantiedashboard | Bewaak BTW-verplichtingen over meerdere landen en verkoopkanalen. |
| Dashboard financiële projectcontrole | Vergelijk budget, verbintenissen, facturen, voortgangsfacturering en projectwinstgevendheid. |
| Audit-toolkit coffeeshopexploitatie | Evalueer operationele prestaties van cafés met gestandaardiseerde auditscores en KPI-analyse. |

---

## Disclaimer

Deze werkmap is bedoeld als analytisch beslissingsondersteunend instrument.

Het vormt **geen**:

- juridisch advies,
- leningsadvies,
- goedkeuring van kredietbeoordeling,
- boekhoudkundige leidraad,
- certificering van regelgevingsnaleving,
- beleggingsaanbeveling.

Alle leningsbeslissingen blijven onderworpen aan het beoordelingsbeleid van de leningsinstelling, toepasselijke regelgeving, investeerderseisen en definitieve kredietgoedkeuring.

Gebruikers zijn verantwoordelijk voor het verifiëren van alle aannames, prijsparameters, tariefstellingen en beoordelingsregels vóór het gebruiken van de gegenereerde output.

---

## Dankwoord

Dit project weerspiegelt gangbare kredietbeoordelingspraktijken in residentiële transitieleningen, waaronder Bridgeleningen, Fix-and-Flip-financiering, renovatieleningen en residentiële bouwfinanciering.

De architectuur benadrukt transparantie, herhaalbaarheid en operationele consistentie zodat prijsbeslissingen reproduceerbaar, herzienbaar en auditbaar zijn in plaats van afhankelijk van individuele spreadsheetkennis.

---

**Apache License 2.0 © 2026**

Gebouwd als onderdeel van een bredere verzameling lichtgewicht operationele beslissingsondersteunende tools voor financiën, bouw, voorraadbeheer en bedrijfsoperaties.
