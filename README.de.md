[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# RTL Loan Sizer & Pricer: Kostenloser Darlehensrechner für Residential Transitional Loans & Fix-and-Flip Excel-Kreditprüfungsvorlage
<img width="1245" height="1209" alt="image" src="https://github.com/user-attachments/assets/856c2ddf-16a5-4212-a162-b3e82ab67dcc" />


![Lizenz: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Plattform: Browser-Web-App und Offline-Excel-Arbeitsmappe](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Kategorie: RTL-Kreditprüfungs- und Darlehenspreis-Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Release-Status: Produktiv und stabil](https://img.shields.io/badge/Version-Stable-brightgreen)

**RTL Loan Sizer & Pricer** ist ein sofort einsatzbereiter **Darlehensrechner für Residential Transitional Loans (RTL)**, eine **Preis-Engine für Fix-and-Flip-Darlehen** und eine **Excel-Vorlage für die Hard-Money-Kreditprüfung**. Damit bemessen Sie Bridge-, Light-Rehab-, Heavy-Rehab- und Ground-Up-Construction-Darlehen, prüfen LTV-, LTC-, LTP- und LTARV-Grenzen, verifizieren den Spread des Darlehensgebers gegen Ihren Einkaufszins und berechnen den Cash-to-Close des Kreditnehmers – alles in unter einer Minute. Testen Sie das Browser-Tool kostenlos online ohne Registrierung, oder kaufen Sie die wiederverwendbare Offline-Excel-Arbeitsmappe einmalig mit 30-tägiger, bedingungsloser Geld-zurück-Garantie.

> **Kostenloses Online-Tool (sofort im Browser ausprobieren)**  
> [Starten Sie den kostenlosen browserbasierten RTL-Darlehensrechner (sofortiger Fix-and-Flip- & Bridge-Darlehensrechner)](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> **Wiederverwendbare Offline-Tabelle (Einmalkauf, 30 Tage Geld-zurück-Garantie)**  
> [Holen Sie sich die wiederverwendbare Offline-Excel-Vorlage RTL Loan Sizer & Pricer auf Theseus Workshop](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Kreditprüfungs-Herausforderungen bei Residential Transitional Loans & automatisierte Lösungen

Private Kreditgeschäfte stocken, wenn Beleihungsgrenzen, Zinsanpassungen nach Kreditstufen und Closing-Abzüge in getrennten Tabellen geprüft werden. Dieses RTL-Kreditprüfungstool ordnet jede typische Rechenlücke direkt einer automatisierten Ausgabe zu:

| Pain Point im Hard-Money- & RTL-Kreditgeschäft | Automatisierte Lösung in diesem RTL Loan Sizer | Zentrale Kreditprüfungs-Kennzahlen & Ausgaben |
| :--- | :--- | :--- |
| **Angebot unpassender Deals vor der Kreditprüfung** | Prüft jeden Deal automatisch gegen Ihre konfigurierten Programm-Obergrenzen, bevor ein Term Sheet rausgeht | Pass / Exception / Decline-Status über Bridge-, Rehab- und Construction-Programme hinweg |
| **Berechnung nur einer einzigen Beleihungskennzahl von Hand** | Bewertet alle vier Größenbestimmungs-Constraints für Residential Transitional Loans gleichzeitig und bindet das Darlehen an den strengsten Grenzwert | **LTV** (Loan-to-Value), **LTC** (Loan-to-Cost), **LTP** (Loan-to-Purchase) und **LTARV** (Loan-to-After-Repair-Value) |
| **Späte Überraschungen beim Cash-to-Close des Kreditnehmers** | Zieht Origination Points, vorausbezahlte Zinsen und Servicing-Gebühren bereits bei der ersten Deal-Kalkulation ab | **Netto-Auszahlbetrag**, Gesamt-**Cash-to-Close**, Rehab-Holdback-Struktur und Liquiditätsreserve-Prüfung |
| **Uneinheitliche Konditionen zwischen Kreditvermittlern** | Zieht Preisanpassungen aus einer zentralen Zinsmatrix, die an FICO- und Beleihungsstufen gekoppelt ist | **FICO-Stufen-Preisgestaltung**, Anpassungen nach Kreditnehmererfahrung und standardisierter Nominalzinssatz |
| **Verdeckte Margenerosion unterhalb des Einkaufszinses** | Markiert jeden angeforderten Nominalzinssatz, der unter Ihre interne Spread-Untergrenze fällt, sofort | **Einkaufszins des Darlehensgebers**, **Mindest-Spread-Validierung** und Schutzstatus der Nettomarge |
| **Langsame manuelle Angebotserstellung bei hohem Aufkommen** | Führt Eingaben, Kreditprüfungsregeln und Closing-Mathematik in einer formatierten, kundenfertigen Ansicht zusammen | Versandfertige **Quote Summary** und vorläufige Aufschlüsselung der Darlehenskonditionen |

---

## Schnellstart-Anleitung: Ein Fix-and-Flip- oder Bridge-Darlehen in 4 Schritten bemessen und bepreisen

Sie können ein Testszenario sofort in der [kostenlosen Online-RTL-Loan-Sizer-Web-App](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) durchführen und anschließend Ihr tägliches Geschäft in die Offline-Excel-Arbeitsmappe überführen, sobald Sie bestätigt haben, dass sie zu Ihren Darlehensrichtlinien passt.

### Schritt 1. Kreditprüfungsregeln und Preisraster einmal festlegen

Konfigurieren Sie Ihre Kreditgebensparameter auf dem Arbeitsblatt **Pricing & Assumptions**. Geben Sie Ihre maximalen Beleihungsgrenzen (LTV, LTC, LTP, LTARV), FICO-Preisraster, Origination Points, Servicing-Gebühren, Mindest-Spread-Anforderungen des Darlehensgebers und unterstützte Darlehensprogramme ein. Nach der Ersteinrichtung aktualisieren Sie diesen Tab nur noch, wenn Ihr Kapitalpartner oder Kreditausschuss die Richtlinien ändert.

### Schritt 2. Kreditnehmer- und Immo-Deal-Zahlen in Inputs einfügen

Öffnen Sie das Arbeitsblatt **Inputs** und erfassen Sie die Eckdaten des Deals:

- Kaufpreis und As-Is-Immobilienwert
- Sanierungs-/Baubudget und After Repair Value (ARV)
- Beantragter Darlehensbetrag und Darlehenslaufzeit
- FICO-Score des Kreditnehmers, frühere Flip-Erfahrung und nachgewiesene flüssige Mittel
- Beantragter Nominalzinssatz und gewähltes Darlehensprogramm (Bridge, Light Rehab, Heavy Rehab oder Construction)

Integrierte Dropdown-Menüs und Datenvalidierung blockieren ungültige Eingaben. Bedingte Formatierung graut Felder aus, die für das gewählte Darlehensprogramm nicht zutreffen.

### Schritt 3. Automatisierte Kreditprüfung, Preisgestaltung und Cash-to-Close-Ergebnisse ablesen

Öffnen Sie das Arbeitsblatt **Quote Summary**, um die vollständige Deal-Aufschlüsselung an einem Ort zu prüfen:

- Freigabeentscheid für das Darlehen und Exception-Markierungen
- Bindende Beleihungskennzahlen (LTV, LTC, LTP und LTARV)
- Zinsvalidierung gegen Einkaufszins und Mindest-Spread-Regeln
- Vorauszinsen, Settlement-Schätzungen, Netto-Auszahlbetrag und Cash-to-Close des Kreditnehmers

### Schritt 4. Wechsel zur wiederverwendbaren Offline-Excel-Arbeitsmappe für Deals im täglichen Geschäft

Die Preisgestaltung von Residential Transitional Loans umfasst mehrschichtige Kreditprüfungslogik, doch Sie müssen nie eine einzige Formel schreiben, fehlerhafte Zellbezüge debuggen oder Gleichungen per Doppelklick eine Spalte hinunterziehen. Jede passende Regel und jede automatisch aktualisierende Formel ist in der Excel-Vorlage bereits vorgebaut.

Laden Sie die Arbeitsmappe auf Ihren Rechner, fügen Sie Ihre eigenen Deal-Zahlen in die Eingabezellen ein und erhalten Sie saubere Kreditprüfungsentscheidungen in unter einer Minute. Auch Einsteiger ohne jegliche Tabellen-Modellierungserfahrung erhalten sofort strukturierte kaufmännische Analyse – und gewinnen in der Hochsaison Stunden für Makleranrufe, Kreditnehmerverhandlungen und Deal-Abschlüsse.

**Warum Kreditteams vom kostenlosen Browser-Test zur bezahlten Offline-Excel-Arbeitsmappe wechseln:**

- **Einmalkauf, unbegrenzte Wiedernutzung:** Bezahlen Sie einmal statt wiederkehrende monatliche SaaS-Abos für Enterprise-Loan-Origination-Systeme (LOS) oder Cloud-Preis-Engines. Tauschen Sie die Eingaben aus und nutzen Sie denselben festen Workflow für jeden Bridge-, Fix-and-Flip-, Rehab- und Construction-Deal.
- **100 % lokale Datenhoheit:** Speichern und führen Sie die Datei offline auf Ihrem eigenen Rechner aus. Sensible Kreditnehmer-Finanzdaten, interne Einkaufszinsen und Spread-Untergrenzen des Darlehensgebers landen nie auf Cloud-Servern Dritter.
- **Risikofreie Garantie:** Die Browserversion ist kostenlos online testbar. Die herunterladbare Excel-Arbeitsmappe ist ein bezahltes Produkt mit **30-tägiger, bedingungsloser Geld-zurück-Garantie**.

> **Bereit, Ihren Kreditprüfungs-Workflow offline zu standardisieren?**  
> [Laden Sie die wiederverwendbare Offline-Excel-Vorlage RTL Loan Sizer & Pricer herunter (Einmalkauf, 30 Tage Geld-zurück-Garantie)](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Geschäftslogik & Methodik: Wie automatisierte RTL-Kreditprüfung versteckte blinde Flecken in Entscheidungen verhindert

Die meisten Preisfehler im privaten Immobilienkreditgeschäft entstehen lange, bevor eine Kreditakte den Kreditausschuss erreicht. Selbst erfahrene Kreditvermittler machen teure Angebotsfehler, wenn sie Kennzahlen einzeln in getrennten Tabellen berechnen. Für Neulinge im Hard-Money- oder Fix-and-Flip-Geschäft töten vier bestimmte kaufmännische blinde Flecken still und leise Deals oder vernichten die Marge des Darlehensgebers.

### 1. Der blinde Fleck der Ein-Kennzahlen-Kalkulation (Warum ein bestandenes LTV trotzdem an der Kreditprüfung scheitern kann)

**Objektiver Fakt:** Ein Fix-and-Flip-Darlehen, das bei 75 % As-Is-LTV sicher aussieht, kann dennoch eine 90-%-LTC-Obergrenze oder eine 70-%-LTARV-Obergrenze verletzen, sobald ein großes Sanierungsbudget einbezogen wird.  
**So löst es dieses Modell:** Die Größenbestimmungs-Engine berechnet LTV, LTC, LTP und LTARV parallel und erzwingt den niedrigsten zulässigen Darlehensbetrag über alle vier Kennzahlen. Sie sehen die exakt bindende Constraint, bevor Sie einem Kreditnehmer Konditionen anbieten.

### 2. Der blinde Fleck Zins gegen Spread (Ein Deal gewonnen, die Marge verloren)

**Objektiver Fakt:** Wer den Nominalzinssatz eines Wettbewerbers anpasst, um einen Kreditnehmer zu gewinnen, drückt das Darlehen oft unter den internen Einkaufszins oder die Mindest-Ertragsspanne, sobald FICO- und Beleihungs-Preisabschläge eingerechnet sind.  
**So löst es dieses Modell:** Jeder angebotene Nominalzinssatz wird automatisch gegen Ihre zentrale Einkaufszins-Matrix und die Mindest-Spread-Anforderung geprüft. Verletzt ein Deal Ihre Gewinnschwelle, markiert das Blatt das sofort, damit Sie neu bepreisen oder Origination Points ergänzen können, bevor ein Term Sheet rausgeht.

### 3. Der blinde Fleck Cash-to-Close (Deals sterben Tage vor dem Settlement)

**Objektiver Fakt:** Erstzeit-Kreditnehmer und Junior-Sachbearbeiter gehen häufig davon aus, dass die Anzahlung dem gesamten Kapitalbedarf entspricht. Vorauszinsen, Origination-Gebühren, Servicing-Gebühren und Liquiditätsreserve-Regeln mindern den Netto-Auszahlbetrag und erhöhen das beim Closing benötigte Kapital.  
**So löst es dieses Modell:** Die Arbeitsmappe berechnet Netto-Darlehensauszahlung, vorgelagerte Abzüge und den Gesamt-Cash-to-Close des Kreditnehmers ab Tag eins. Kreditnehmer kennen ihren realen Kapitalbedarf sofort – das reduziert spätes Ausscheiden aus Deals.

### 4. Der blinde Fleck Preisabflüsse (Exponierte interne Einkaufszinsen)

**Objektiver Fakt:** Wer eine ungeschützte Preistabelle an externe Makler oder Junior-Mitarbeiter weitergibt, exponiert seine Wholesale-Einkaufszinsen, Kapitalkosten und internen Margenregeln.  
**So löst es dieses Modell:** Preistabellen und Spread-Formeln liegen auf einem dedizierten Assumptions-Tab, der in Versionen für Kreditvermittler gesperrt und versteckt werden kann – die sensible Preisökonomie bleibt privat, während schnelles Self-Service-Quoting erhalten bleibt.

### Workflow-Wechsel in der Praxis: Vorher vs. Nachher

**Vorher (Manuelles Quoting)**
1. Der Kreditvermittler prüft den As-Is-LTV in einem schnellen Taschenrechner und gibt dem Kreditnehmer ein mündliches Angebot.
2. Die Kreditprüfung entdeckt später eine LTARV-Überschreitung und ein Spread-Defizit unter dem Einkaufszins des Darlehensgebers.
3. Das Team korrigiert das Angebot nach unten und erhöht den erforderlichen Cash-to-Close des Kreditnehmers.
4. Das Vertrauen des Kreditnehmers sinkt, Closing-Verzögerungen stapeln sich, und interne Mitarbeiter verbringen Stunden mit der Überarbeitung einer einzigen Akte.

**Nachher (Automatisierter RTL-Loan-Sizer-Workflow)**
1. Der Kreditvermittler erfasst Immobilienzahlen, Sanierungsbudget und FICO des Kreditnehmers einmalig.
2. Die Arbeitsmappe prüft Beleihungsgrenzen, Spread-Untergrenze, Settlement-Abzüge und Liquiditätsreserven gleichzeitig – in Sekunden.
3. Das Team weiß sofort, ob der Deal sauber durchgeht, eine Management-Exception erfordert oder vor dem Angebot abgelehnt werden sollte.

---

## Manueller Hard-Money-Quote vs. automatisierter RTL Loan Sizer: Betriebsvergleich

| Engpass im Residential-Transitional-Lending | Risiko von Ad-hoc-Tabellen & manuellem Quoting | Standardisierter RTL-Loan-Sizer-Workflow |
| :--- | :--- | :--- |
| **Größenbestimmung über nur eine Kennzahl** | Wer nur nach LTV freigibt, übersieht LTC-, LTP- oder LTARV-Grenzwerte bis zur Kreditausschuss-Prüfung | Bewertet LTV, LTC, LTP und LTARV gleichzeitig und erzwingt die bindende Darlehensgrenze vor dem Quoting |
| **Manuelle Rate-Sheet-Lookups** | Verschiedene Kreditoffiziere bieten widersprüchliche Zinsen und Points für identische FICO- und Beleihungsprofile | Zieht einheitliche Zinsen und Anpassungen aus einem zentralen FICO- und Beleihungspreisraster |
| **Unbemerkte Margenkompression** | Darlehen passieren Beleihungschecks und liegen still unter internem Einkaufszins und Spread-Untergrenzen | Eingebaute Spread-Validierung markiert jedes Angebot unter den Mindest-Margenanforderungen sofort |
| **Unerwarteter Cash-to-Close des Kreditnehmers** | Vorauszinsen, Origination Points und Servicing-Abzüge tauchen spät am Verhandlungstisch auf | Berechnet Netto-Auszahlbetrag, Settlement-Abzüge und Cash-to-Close bereits bei der Strukturierung |
| **Späte Entdeckung von Kreditprüfungs-Exceptions** | Mehrfache Term-Sheet-Revisionen blockieren Pipelines und frustrieren Makler | Hebt Richtlinien-Exceptions sofort hervor für strukturierte Management-Freigabe |
| **Exponierte Wholesale-Preislogik** | Geteilte manuelle Arbeitsmappen lassen interne Einkaufszinsen und Gewinnmargen nach außen durchsickern | Trennt geschützte Preisannahmen von Kreditvermittler-Eingabe- und Quote-Summary-Blättern |

---

## Wer diesen RTL-Darlehensrechner nutzt: Rollenbasierte Anwendungsfälle für Private Lender, Makler und Hard-Money-Teams

Dieses Tool passt in konkrete Tagesworkflows der Residential-Transitional-Lending-Branche – ohne Tabellen-Modellierungskenntnisse oder schwerfällige Enterprise-Software-Rollouts:

| Rolle / Jobtitel | Primärer Such- & Workflow-Bedarf | So nutzen sie den RTL Loan Sizer & Pricer |
| :--- | :--- | :--- |
| **Hard-Money- & Private-Money-Lender** | Hard-Money-Kreditpreis-Tabelle & Deal-Größenbestimmungs-Engine | Erzwingt konsistente LTV/LTC/LTARV-Obergrenzen und schützt die Mindest-Spread-Marge des Darlehensgebers bei jedem Angebot |
| **Hypothekenmakler & Kreditvermittler (LOs)** | Fix-and-Flip-Angebotsgenerator & Kreditnehmer-Vorqualifizierungstool | Verwandelt rohe Immobilienzahlen und Sanierungsbudgets in unter einer Minute in saubere Kreditnehmer-Term-Sheets |
| **Kreditsachbearbeiter & Transaktionskoordinatoren** | Bridge-Darlehen-Cash-to-Close- & Netto-Auszahlungsrechner | Verifiziert vorausbezahlte Zinsen, Servicing-Gebühren, Kreditnehmer-Liquidität und Nettoerlöse, bevor Closing-Unterlagen bestellt werden |
| **Kreditanalysten & Underwriter** | RTL-Darlehens-Fähigkeitsprüfung & Exception-Screening-Vorlage | Prüft Multi-Kennzahlen-Beleihungsgrenzen und markiert unpassende Deals vor der Kreditausschuss-Prüfung |
| **Capital-Markets- & Sekundärmarkt-Desks** | Einkaufszins-Validierung & Ertrags-Spread-Modell | Pflegt zentrale Preisraster und bestätigt, dass die Preise auf Darlehensebene die Schwellen für Sekundärmarktverkäufe klarieren |
| **Kleine Private-Lending-Firmen & Boutique-Darfonds** | Leichte LOS-Alternative als Excel-Arbeitsmappe | Standardisiert Bridge-, Light-Rehab-, Heavy-Rehab- und Ground-Up-Construction-Kreditprüfung ohne Enterprise-SaaS-Gebühren |
| **Immobilieninvestoren & House-Flippers** | Einsteigerfreundlicher Hard-Money-Deal-Analysator | Schätzt maximalen Darlehensauszahlungsbetrag und Gesamt-Kapitalbedarf beim Closing, bevor ein Kreditantrag eingereicht wird |

**Geltungsbereich:** Diese Arbeitsmappe ist speziell für die vorgelagerte Größenbestimmung von Darlehen, die Fähigkeitsvalidierung, die Preisprüfung und die Angebotserstellung gebaut. Darlehensservicing, Draw-Auszahlungsabrechnung und regulatorisches Compliance-Management bleiben dedizierten Servicing- und Compliance-Plattformen vorbehalten.

---

## Häufig gestellte Fragen (RTL-Größenbestimmung & Excel-Vorlage)

<details>
<summary><strong>Was ist der Unterschied zwischen LTV, LTC, LTP und LTARV bei einem Residential Transitional Loan?</strong></summary>

- **LTV (Loan-to-Value):** Darlehensbetrag geteilt durch den aktuellen As-Is-Beleihungswert der Immobilie.
- **LTP (Loan-to-Purchase):** Anfängliche Erwerbsauszahlung geteilt durch den vertraglichen Kaufpreis.
- **LTC (Loan-to-Cost):** Gesamtdarlehensbetrag geteilt durch die Gesamtprojektkosten (Kaufpreis plus Sanierungsbudget).
- **LTARV (Loan-to-After-Repair-Value):** Gesamtdarlehensbetrag geteilt durch den projizierten After Repair Value (ARV) nach Abschluss der Sanierung.

Da Hard-Money-Lender alle vier Kennzahlen gleichzeitig begrenzen, legt der niedrigste resultierende Darlehensbetrag Ihre maximal förderfähige Darlehensgröße fest.
</details>

<details>
<summary><strong>Brauche ich fortgeschrittene Excel-Kenntnisse für die Offline-Vorlage?</strong></summary>

Nein. Alle Preisraster, Beleihungsformeln und bedingten Prüfungen sind vorkonfiguriert. Sie fügen lediglich Deal-Eingaben in die dafür vorgesehenen Zellen auf dem Tab **Inputs** ein und lesen die Ergebnisse auf dem Tab **Quote Summary** ab.
</details>

<details>
<summary><strong>Was ist der Unterschied zwischen der kostenlosen Browserversion und der bezahlten Excel-Version?</strong></summary>

Mit dem [kostenlosen browserbasierten RTL-Darlehensrechner](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) testen Sie die Kreditprüfungslogik sofort online – ganz ohne Konto. Die [bezahlte Offline-Excel-Arbeitsmappe](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan) gibt Ihnen eine dauerhafte lokale Datei: Sie passen sie mit eigenen Preisrastern an, speichern sie pro Deal, nutzen sie nach einmaliger Zahlung unbegrenzt wieder (mit 30-tägiger Geld-zurück-Garantie) und halten sie komplett von Cloud-Servern Dritter fern.
</details>

---

## Über Theseus Workshop

**Theseus Workshop** entwickelt leichte, wiederverwendbare Analyse-Arbeitsmappen für Geschäfts- und Kreditentscheidungen, bei denen zu viele Finanzvariablen gleichzeitig interagieren. Jede Vorlage verpackt bewährte Kreditprüfungs- und kaufmännische Analyselogik in einen sauberen Offline-Excel-Workflow, damit kleine Teams und Solo-Operatoren in Minuten zu konsistenten, belastbaren Entscheidungen kommen.

Der **RTL Loan Sizer & Pricer** legt Kreditprüfungsgrenzen, Einkaufszins-Preisregeln, Beleihungsvalidierung, Settlement-Abzüge und Kundenangebot-Ausgaben auf einen Bildschirm – so wissen Sie immer, ob ein Deal funktioniert, bevor Sie Kapital binden.

Sie suchen weitere einsatzbereite Offline-Excel-Finanzmodelle, Preis-Engines und operative Entscheidungsunterstützungs-Tools?  
[Erkunden Sie den vollständigen Katalog der Offline-Business- & Finance-Excel-Vorlagen auf Theseus Workshop (theseusworkshop.com)](https://www.theseusworkshop.com)

## Technische Details

<details>
<summary><strong>Für technische Reviewer, Excel-Praktiker und Mitwirkende</strong></summary>

---

## Arbeitsmappen-Architektur

Die Arbeitsmappe folgt einer geschichteten Architektur, die Benutzerinteraktion, Geschäftsregeln, analytische Berechnungen und Darstellung trennt. Das verhindert versehentliche Änderungen an der Preislogik und hält den Tagesbetrieb für Kreditvermittler einfach.

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

## Zuständigkeiten der Arbeitsblätter

| Arbeitsblatt | Zweck | Editierbar |
|------------|---------|----------|
| 01_ReadMe | Anleitungen, Versionshistorie, Administrator-Dokumentation | Ja |
| 02_Inputs | Kreditnehmerinformationen und beantragte Darlehenskonditionen | Ja |
| 03_Pricing_&_Assumptions | Einkaufszins-Raster, Beleihungsregeln, Preisannahmen | Nur Administratoren |
| 04_Calc_Engine | Kreditprüfungsberechnungen, Preis-Engine und Validierung | Nein |
| 05_Quote_Summary | Kundenorientiertes, druckbares Term Sheet | Nein |

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

Jede für den Benutzer angezeigte Ausgabe stammt aus der Berechnungs-Engine. In das finale Angebot wird kein Wert manuell eingegeben.

---

## Sicherheitsstrategie

Die Arbeitsmappe ist bewusst in zwei Vertriebsformate kompiliert.

| Version | Zielbenutzer | Geschützte Komponenten |
|---------|----------------|----------------------|
| Interne Version | Geschäftsinhaber, Underwriter, Operations | Alle Arbeitsblätter sichtbar, mit Administrator-Passwort |
| Vermittler-Version | Kreditvermittler (Loan Originators) | Preistabellen und Berechnungs-Engine per xlSheetVeryHidden versteckt |

Weitere Schutzmaßnahmen umfassen:

- Schutz der Arbeitsmappenstruktur
- Versteckte Formeln
- Gesperrte Berechnungszellen
- Geschützte Preisraster
- Versteckte Formelleiste (Vermittler-Version)
- Passwortgeschützte Arbeitsblattstruktur

Dieser Ansatz schützt die proprietäre Preisgestaltung des Darlehensgebers, ohne zwei unabhängige Arbeitsmappen pflegen zu müssen.

---

## Drei Fallen, die selbst erfahrene Kreditvermittler erwischen

---

## Falle 1 — Nur auf das LTV schauen

Viele Lender fokussieren sich instinktiv auf den Loan-to-Value, weil er die vertrauteste Kreditprüfungskennzahl ist.

Leider stützt sich Transitional Lending selten auf nur eine einzige Beleihungskennzahl.

### Falsche Entscheidung

Kaufpreis

```
$400,000
```

Beantragtes Darlehen

```
$320,000
```

As-Is-Wert

```
$420,000
```

Berechnetes LTV

```
76.2%
```

Der Kreditvermittler folgert:

> "Das Darlehen liegt im Rahmen der Richtlinien."

Allerdings ...

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

Das Darlehen liegt tatsächlich außerhalb der Kreditrichtlinien.

### Richtiger Ansatz

Prüfen Sie:

- LTV
- LTC
- LTARV
- LTP

bevor Sie über die Freigabe entscheiden.

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

Die Arbeitsmappe bewertet automatisch alle Beleihungskennzahlen gemeinsam, bevor sie den Status Pass, Exception oder Fail vergibt.

---

## Falle 2 — Angebot abgeben, bevor die Marge geprüft ist

Ein Kreditnehmer beantragt einen attraktiven Zins.

Der Kreditvermittler senkt den Nominalzinssatz, um wettbewerbsfähig zu bleiben.

Alles scheint in Ordnung.

Später ...

Das Sekundärmarkt-Team entdeckt, dass der Spread des Darlehensgebers unter das interne Minimum gefallen ist.

Das Angebot muss überarbeitet werden.

### Falsche Entscheidung

Kreditnehmerzins

```
10.00%
```

Einkaufszins

```
8.20%
```

Spread

```
1.80%
```

Erforderlicher Mindest-Spread

```
2.50%
```

Das Geschäft liegt tatsächlich unter den Rentabilitätsanforderungen des Darlehensgebers.

### Richtiger Ansatz

Jedes Angebot sollte die Preisgestaltung validieren, bevor es präsentiert wird.

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

Statt das Problem erst in der finalen Prüfung zu entdecken, markiert die Arbeitsmappe sofort:

```
Below Margin
```

und ermöglicht so eine Korrektur der Preisgestaltung, bevor der Kreditnehmer ein Angebot erhält.

---

## Falle 3 — Das beim Closing benötigte Kapital unterschätzen

Viele Kreditnehmer betrachten nur den beantragten Darlehensbetrag.

Settlement-Kosten mindern die tatsächlichen Erlöse.

Wer diese Abzüge ignoriert, erzeugt häufig unrealistische Erwartungen bei Kreditnehmern.

### Beispiel

Beantragtes Darlehen

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

Erforderliches Kapital

```
$468,000
```

Tatsächlicher Cash-to-Close

```
$26,500
```

Betragen die flüssigen Mittel des Kreditnehmers nur

```
$18,000
```

kann das Closing ohne zusätzliche Mittel nicht erfolgen.

### Richtiger Ansatz

Berechnen Sie die Settlement-Erlöse, statt anzunehmen, dass der Brutto-Darlehensbetrag der verfügbaren Finanzierung entspricht.

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

Die Arbeitsmappe erkennt Liquiditätslücken, bevor Closing-Unterlagen erstellt werden.

---

## Beispielszenario

Betrachten Sie das folgende Fix-and-Flip-Geschäft.

| Posten | Wert |
|------|------:|
| Kaufpreis | $300,000 |
| Sanierungsbudget | $70,000 |
| As-Is-Wert | $310,000 |
| ARV | $465,000 |
| Beantragtes Darlehen | $340,000 |
| FICO | 726 |
| Erfahrung | 6+ Projekte |
| Nominalzinssatz | 11.25% |
| Darlehenslaufzeit | 12 Monate |

Die Preis-Engine ruft den entsprechenden Einkaufszins anhand der FICO-Stufe und der berechneten Beleihung des Kreditnehmers ab.

Die Berechnungs-Engine ermittelt dann:

- Tatsächliches LTV
- Tatsächliches LTC
- Tatsächliches LTP
- Tatsächliches LTARV
- Spread
- Net Funding
- Cash-to-Close
- Geschätzter Gewinn des Darlehensgebers

Angenommen, die resultierenden Kennzahlen sind:

| Kennzahl | Ergebnis |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Freigabe | Exception erforderlich |

Obwohl die Preisgestaltung weiterhin profitabel bleibt, überschreitet die Beleihung die bevorzugte LTV-Schwelle.

Statt das Darlehen sofort abzulehnen, stuft die Arbeitsmappe es als **Exception erforderlich** ein und gibt dem Management Gelegenheit, kompensierende Faktoren wie Kreditnehmererfahrung, Liquidität oder zusätzliche Sicherheiten zu prüfen.

Dieser strukturierte Workflow schafft einen konsistenten Kreditprüfungsprozess, bei dem Preisgestaltung, Beleihung, Settlement und Rentabilität gemeinsam statt isoliert bewertet werden.

---

## Formelreferenz

<details>

<summary>Beleihungsberechnungen</summary>

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
| XLOOKUP | Einkaufszins abrufen |
| INDEX + MATCH | Legacy-Preis-Lookup |
| Spread | Nominalzinssatz − Einkaufszins |
| Spread Status | Margenvalidierung |

Die Preisgestaltung verwendet immer exaktes Lookup-Verhalten mit Standard-Fehlerbehandlung, um ungültige Preisangaben zu verhindern.

</details>

<details>

<summary>Settlement-Berechnungen</summary>

| Berechnung | Zweck |
|-------------|----------|
| Short Interest | Beim Closing erhobene Zinsen |
| Servicing Fee | Über die Darlehenslaufzeit abgezogene Gebühr |
| Net Funding | Dem Kreditnehmer zur Verfügung stehende Mittel |
| Cash to Close | Zusätzlicher Beitrag des Kreditnehmers |
| Liquidity Shortfall | Finanzierungsdefizit |

</details>

<details>

<summary>Freigaberegeln</summary>

Die Kreditprüfungs-Engine bewertet:

- Maximales LTV
- Maximales LTC
- Maximales LTARV
- Preis-Marge
- Kreditnehmer-Liquidität

Mögliche Ergebnisse:

- PASS
- EXCEPTION NEEDED
- FAIL

Die Gesamtfreigabe spiegelt immer das restriktivste Kreditprüfungsergebnis wider.

</details>

## Validierungsregeln

| Feld | Validierungsregel | Fehlerverhalten |
|------|-----------------|----------------|
| Darlehensart | Nur Dropdown | Ungültige Werte ablehnen |
| Kaufpreis | Größer als null | Null-Berechnungen zurückgeben |
| As-Is-Wert | Größer als null | Division durch null verhindern |
| Sanierungsbudget | Null bei Bridge-Darlehen | Feld automatisch ausgegraut |
| ARV | Für Rehab-Produkte erforderlich | N/A anzeigen, wo zutreffend |
| Beantragtes Darlehen | Positiver Währungsbetrag | Negative Werte ablehnen |
| FICO | 300–850 | Ungültigen Score ablehnen |
| Erfahrungsstufe | Nur Dropdown | Lookup-Fehler verhindern |
| Darlehenslaufzeit | 12 / 18 / 24 Monate | Andere Werte ablehnen |
| Short-Interest-Tage | 0–30 | Ungültige Eingabe ablehnen |
| Einkaufszins-Lookup | XLOOKUP mit Fallback-Wert | "Check Risk Rules" |
| Divisionen | IFERROR-Wrapper | 0 statt Excel-Fehlern zurückgeben |
| Text-Lookups | TRIM + UPPER | Abweichungen bei Leerzeichen und Groß-/Kleinschreibung verhindern |
| Margenprüfung | Vergleich mit Mindest-Spread | "Below Margin" zurückgeben |
| Freigabe | Alle Kreditprüfungs-Flags auswerten | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Weitere Tools dieser Serie

Der **RTL Loan Sizer / Pricer** ist Teil einer wachsenden Sammlung leichter operativer Entscheidungsunterstützungs-Tools für Profis, die verlässliche Analysen benötigen, ohne Enterprise-Software einführen zu müssen.

Jedes Tool folgt denselben Prinzipien:

- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Warum ist Cash immer knapp? — Prognostiziert die künftige Liquidität unter veränderlichen operativen und finanziellen Annahmen.
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Welche Handelsströme sind nach Währungseffekten tatsächlich profitabel? — Misst die Multi-Währungs-Handelsrentabilität über grenzüberschreitende Geschäfte hinweg.
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Wo vermischen oder fehlallokieren sich private und geschäftliche Mittel? — Trennt private und geschäftliche Geldflüsse in unabhängig verfolgte Budgetstränge.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Schafft diese Immobilienakquisition nach Sanierungs- und Betriebsannahmen noch Eigenkapitalwert? — Bewertet Multifamily-Akquisitionsrenditen unter Sanierungsfinanzierungs- und Betriebsszenarien.
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — Was ist eine Immobilie unter verschiedenen Bewertungsmethoden wert? — Berechnet Immobilienwerte über mehrere Bewertungsmethoden mit Steuer- und Investitionsausgaben-Modellierung.
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Werden Gemeinkosten fair auf die Gesellschaften verteilt, oder tragen manche Assets eine Überlast, während andere ihrer wahren Kostenbasis entgehen? — Verteilt Lieferantenrechnungen auf mehrere Rechtsträger und Betriebs-Assets mithilfe konfigurierbarer Allokationsmethoden.
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — Was wird jedem Teilnehmer basierend auf seinem Einstiegszeitpunkt und dem aktuellen Poolwert tatsächlich geschuldet? — Verfolgt Poolbeteiligungen kontinuierlich über NAV-basiertes Anteilseinheits-Accounting.
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Welche operativen Verpflichtungen erzeugen in den nächsten zwölf Wochen ein Cash-Problem? — Verknüpft Shopify-Umsätze, Banktransaktionen, Werbeausgaben und Wareneinkauf in einen einheitlichen Cashflow-Entscheidungsrahmen.
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — Hat sich genug Bedeutendes verändert, um eine Preisanpassung zu rechtfertigen? — Steuert Preisempfehlungen über konfigurierbare Leitschienen, die unnötige Umsatzvolatilität verhindern.
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — Was hat sich im Berichtszeitraum tatsächlich verändert, und welche Produkte oder Keywords haben den Wandel getrieben? — Wandelt Amazon-Seller-Central-SQP- und Sellerboard-Exporte in standardisierte Executive Business Reviews um.
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Welche Produkte sind nach Allokation aller Herstellungskosten tatsächlich profitabel, und welche vernichten Marge? — Allokiert Fabrik-Lohn-, Energie-, Overhead- und Materialkosten auf jede SKU für echte Einheitsökonomie.
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Welche Bestellungen sind nach allen versteckten Kosten tatsächlich profitabel, und wo leckt Geld über Kanäle und Währungen hinweg? — Rekonstruiert die echte Rentabilität auf Bestellungsebene, indem Auszahlungen, Versandkosten, Zahlungsgebühren und Marketplace-Provisionen über multikanalige E-Commerce-Operationen abgeglichen werden.
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Welche Bauunternehmer-Projekte und Kunden sind nach allen Projektkosten tatsächlich profitabel? — Verknüpft Lead-Kalkulation, Projektausführung und Ist-Kostenverfolgung in einen einheitlichen Contractor-Rentabilitätsrahmen.
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — Ist der Laden nach allen Zutaten-, Arbeits- und Betriebskosten wirklich profitabel? — Verknüpft Rezeptur-Kalkulation, Umsatz, Lagerverbrauch und Betriebsausgaben in einen einheitlichen Rentabilitäts- und Cashflow-Rahmen.
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Welche Frachtbuchungen sind nach allen Kosten, Gebühren und Währungsumrechnungen tatsächlich profitabel? — Misst die Rentabilität auf Buchungsebene durch Abgleich von Umsatz, COGS, Bankgebühren und Containerkosten über gemischtwährige Transaktionen hinweg.
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Welche Container und Kunden sind über Zoll- und Flottenoperationen hinweg tatsächlich profitabel? — Konsolidiert Zollabwicklung und Flottenausführung in einer einzigen Rentabilitätsansicht auf Container-Ebene.
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — Was ist nach Jahren von Überweisungen und aufgelaufenen Zinsen heute tatsächlich geschuldet? — Führt langfristige Mittelüberweisungen und Zinsansammlungen zu einem aktuellen Restsaldo zusammen.
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — Wie werden unsere Abschlüsse unter verschiedenen Betriebs- und Finanzierungsszenarien aussehen? — Prognostiziert integrierte Abschlüsse, indem Umsatz, Aufwendungen, Working Capital und Schulden in ein einheitliches Modell verknüpft werden.
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — Wie viel der ausgewiesenen Marge jedes Hauses entstammt tatsächlich dem Haus selbst, und wie viel der Art, wie Unternehmenskosten allokiert wurden? — Allokiert Gemeinkosten auf Betriebseinheiten, wahrt Quelltransaktionen und gleicht Ergebnisse auf Einheitsebene mit Unternehmenssummen ab.
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — Bei welchem maximalen Grunderwerbspreis wird dieses Entwicklungsprojekt zu einer bankfähigen Investition? — Bewertet Wohnbauentwicklungschancen durch Sichtung von Land-Vergleichswerten, Schätzung der Baukosten und Berechnung der Profit-on-Cost-Schwellen.
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Erreicht dieses Bauvorhaben tatsächlich seine Zielmarge, sobald Baustellenlogistik, Abfallfaktoren und Gewerke-Raten-Änderungen eingerechnet sind? — Trennt physische Baumengen von volatilen Gewerke-Raten und Baustellen-Pauschalkosten, um kaufmännische Aufschläge über Ausschreibungsbudgets und Kundenangebote zu kaskadieren.
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Welche Großhandelspreise und Kundensegmente sichern die Marge tatsächlich, sobald Fracht, Zölle, Zahlungsziele und FX vollständig kostiert sind? — Berechnet Landed Costs, Cost-to-Serve und Pocket-Margin-Preiswasserfälle auf SKU-Ebene, um grenzüberschreitende Wholesale-Rentabilität zu simulieren.
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — Was sollten wir für einen Etiketten-Auftrag je Mengenstufe berechnen, um wettbewerbsfähig und profitabel zu bleiben? — Berechnet parametrische Etikettenpreise durch Modellierung von Substrat-Quadratzollkosten, Rüstkosten und Mengenstaffel-Rabattgrenzen gegen Wettbewerber-Benchmarks.
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — Wie hoch ist die echte Nettomarge je SKU, sobald tatsächliche Landed Costs und Händlerabzüge eingerechnet sind? — Gleicht PO-geschätzte Landed Costs gegen tatsächliche Fracht-, Zoll-, FX- und Drayage-Gebühren ab und prüft Händler-Rückzahlungsabzüge, um Nettomargen auf SKU-Ebene aufzudecken.
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Können wir die Einstellungs-, Marketing- und Lieferantenverpflichtungen dieser Woche tragen, ohne vor dem Monatsabschluss das Cash zu verlieren? — Verfolgt wöchentliches Cash-Burn-Tempo, MRR/ARR-Waterfall-Abweichungen, Retention-Kennzahlen und Lohnkosten gegen das Budget bis zum Monatsabschluss.
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — Gehen unserem Wachstumsplan die Mittel aus, bevor die Kohorten-Monetarisierung aufholt? — Prognostiziert mehrjährigen Cash Burn, Runway, Unit Economics und Fundraising-Verwässerung aus Bottom-up-Kohorten- und Headcount-Annahmen.
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Ist jeder Shopify-Storefront tatsächlich profitabel, sobald echte SKU-Ebene-Kosten, Gemeinkosten und Bankgebühren abgeglichen sind? — Gleicht Multi-Store-Shopify-Umsatzexporte gegen SKU-Ebene-COGS, allokierte Multi-Währungs-OPEX und Bankauszüge ab und erzeugt eine vertrauenswürdige Monats-GuV.
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Welche Tour-Buchungen erzeugen nach Lieferantenkosten und B2B-Einzügen tatsächlich Nettogewinn und positiven Cashflow? — Berechnet Projektkosten je Tour-Buchung, Bruttomargen, AR/AP-Settlement und operativen Cashflow über mehrere Währungen hinweg.

| Tool | Zweck |
|------|---------|
| Construction Estimating System | Standardisiert Projektkalkulation, Baugruppen, Ausschreibungspreise und Kostenverfolgung. |
| Inventory Forecasting & Reorder Planner | Prognostiziert Lagerbedarf, erkennt Nachbestellungszeitpunkte und überwacht Bestandsrisiken. |
| Retail & Maquila Inventory Ledger | Verfolgt Bestandsbewegungen auf Stückebene, Produktion, Defekte und Distribution. |
| Unified Personal & Business Budget Framework | Führt private und geschäftliche Geldflüsse in einem Finanzplanungsmodell zusammen. |
| Cross-Border VAT Compliance Dashboard | Überwacht USt-Pflichten über mehrere Länder und Vertriebskanäle hinweg. |
| Project Financial Control Dashboard | Vergleicht Budget, Verpflichtungen, Rechnungen, Baufortschrittsabrechnung und Projektrentabilität. |
| Coffee Shop Operations Audit Toolkit | Bewertet die Café-Betriebsleistung mit standardisiertem Audit-Scoring und KPI-Analyse. |

---

## Haftungsausschluss

Diese Arbeitsmappe ist als analytisches Entscheidungsunterstützungstool gedacht.

Sie stellt **keine** der folgenden Leistungen dar:

- Rechtsberatung,
- Kreditberatung,
- Freigabeentscheid der Kreditprüfung,
- Buchführungsleitlinien,
- regulatorische Compliance-Zertifizierung,
- Anlageempfehlung.

Alle Kreditentscheidungen unterliegen weiterhin den Kreditprüfungsrichtlinien des Kreditinstituts, geltenden Vorschriften, Investor-Anforderungen und der finalen Kreditfreigabe.

Die Nutzer sind dafür verantwortlich, alle Annahmen, Preisparameter, Gebührenschemata und Kreditprüfungsregeln zu verifizieren, bevor sie sich auf die erzeugten Ausgaben verlassen.

---

## Danksagungen

Dieses Projekt spiegelt gängige Kreditprüfungspraktiken im Residential Transitional Lending wider, darunter Bridge-Darlehen, Fix-and-Flip-Finanzierung, Rehabilitationsdarlehen und wohnbauliches Construction Lending.

Seine Architektur betont Transparenz, Wiederholbarkeit und operative Konsistenz, damit Preisentscheidungen reproduziert, nachvollzogen und auditiert werden können, statt von individuellem Tabellenwissen abzuhängen.

---

**Apache License 2.0 © 2026**

Entstanden als Teil einer breiteren Sammlung leichter operativer Entscheidungsunterstützungs-Tools für Finanzwesen, Bauwesen, Bestandsmanagement und Geschäftsbetrieb.
