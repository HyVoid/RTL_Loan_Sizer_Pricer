[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# RTL Loan Sizer & Pricer : Calculateur de prêts Fix-and-Flip, crédit relais et prêt construction — Modèle Excel

<img width="1245" height="1209" alt="RTL Loan Sizer and Pricer Excel Dashboard Preview" src="https://github.com/user-attachments/assets/856c2ddf-16a5-4212-a162-b3e82ab67dcc" />

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
![Platform](https://img.shields.io/badge/Platform-Free%20Web%20App%20%2B%20Excel%20.XLSX-2ea44f.svg)
![Loan Types](https://img.shields.io/badge/Programs-Bridge%20%7C%20Rehab%20%7C%20Construction-3b82f6.svg)
![Automation](https://img.shields.io/badge/Formulas-100%25%20Automated%20%7C%20No%20Macros-brightgreen.svg)

> **Cessez de coter des dossiers qui échoueront en souscription — et cessez d'être pris de court par les surprises de Cash-to-Close de dernière minute.**
>
> **RTL Loan Sizer & Pricer** est un **calculateur de prêts résidentiels transitionnels (RTL)** prêt à l'emploi, un **moteur de tarification de prêts fix-and-flip** et un **modèle Excel de souscription hard money**. Collez la valeur du bien, le budget de réhabilitation et le score FICO de l'emprunteur pour valider simultanément les plafonds **LTV, LTC, LTP et LTARV** sur des prêts **crédit relais (Bridge), réhabilitation légère, réhabilitation lourde et construction à neuf (Ground-Up)** — contrôlez votre **marge de prêteur par rapport au buy rate**, et calculez le **financement net réel et le Cash-to-Close de l'emprunteur** en moins de 60 secondes.

### Essayez gratuitement dans votre navigateur — ou devenez propriétaire à vie du moteur Excel hors ligne privé

Testez un scénario en direct dès maintenant dans votre navigateur, inspectez les 5 onglets dans Google Sheets, ou débloquez le **classeur Excel 100% hors ligne** réutilisable grâce à un **achat unique** (zéro abonnement LOS mensuel, avec une **garantie de remboursement de 30 jours sans conditions**) :

- 🌐 **[Lancez le calculateur de prêts RTL gratuit dans le navigateur](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)**
  Sans inscription. Sans installation. Effectuez un contrôle instantané de dimensionnement de prêt fix-and-flip, crédit relais ou réhabilitation directement dans votre navigateur.
- 📥 **[Obtenez le modèle Excel RTL Loan Sizer & Pricer hors ligne réutilisable (.XLSX) — Achat unique](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)**
  Personnalisez vos propres grilles buy rate FICO/levier, protégez vos règles de tarification confidentielles hors ligne, enregistrez un nombre illimité de cotations et imprimez des term sheets prêts pour vos clients. *Garantie de remboursement de 30 jours.*
- 👀 **[Inspectez la structure en 5 onglets sur Google Sheets](https://docs.google.com/spreadsheets/d/1n-H2iiCJEFqjxEVYOsrszDOUnHgPuGLR/edit?usp=sharing&ouid=108770714531989318327&rtpof=true&sd=true)**
  Prévisualisez chaque feuille de calcul, chaque règle de validation par liste déroulante et chaque sortie de cotation avant l'achat. *(Remarque : l'aperçu Google Sheets peut parfois afficher des avertissements de compatibilité `#NAME?` qui n'apparaissent pas dans Microsoft Excel.)*

> 💡 *Vous présélectionnez un lotissement résidentiel ou un projet de maisons en bande avant de rencontrer un prêteur hard money ? Vérifiez d'abord la rentabilité du terrain et de la construction avec notre **[outil gratuit ($0+) de présélection de projets de promotion immobilière](https://github.com/HyVoid/real-estate-development-feasibility-excel)**, puis apportez ici vos dossiers `PASS` pour dimensionner votre crédit relais/prêt construction et vérifier le Cash-to-Close exact.*

---

## Calculateur navigateur gratuit vs classeur Excel hors ligne complet

Utilisez l'application web gratuite pour tester les calculs de souscription sur le moment. Passez au classeur `.xlsx` hors ligne lorsque vous souhaitez des grilles de tarification personnalisées, une confidentialité totale des données emprunteur/taux et un moteur de cotation permanent :

| Capacité | Calculateur navigateur gratuit | Classeur Excel hors ligne complet (.XLSX) |
| :--- | :--- | :--- |
| **Dimensionnement de prêt crédit relais / flip / réhabilitation en 60 secondes** | Inclus (instantané) | Inclus (flux copier-coller) |
| **Plafonds LTV, LTC, LTP & LTARV simultanés** | Règles standards | **Plafonds de programme 100% modifiables (crédit relais, réhabilitation légère/lourde, construction)** |
| **Matrice buy rate personnalisée par FICO et expérience** | Grille de démonstration prédéfinie | **Grille de tarification et planchers de marge entièrement personnalisables** |
| **100% de confidentialité locale des données (emprunteurs & buy rates)** | Session navigateur uniquement | **Enregistré hors ligne en privé — zéro exposition à un cloud tiers** |
| **Protection de la tarification (mode organisateur / Originator)** | Non inclus | **Configuration admin interne vs distribution Originator protégée** |
| **Financement net, intérêts prépayés & Cash-to-Close** | Aperçu rapide | **Décomposition complète du règlement + contrôle du déficit de liquidité** |
| **Résumé de cotation imprimable prêt pour le client** | Vue écran | **Term sheet `05_Quote_Summary` formaté + fichiers de dossiers enregistrés** |
| **Tarification & garantie** | 100% gratuit | **Paiement unique (sans SaaS LOS) + garantie de remboursement de 30 jours** |

---

## 6 erreurs coûteuses de cotation hard money et RTL, résolues automatiquement

Que vous soyez un chargé de prêt qui tarife des cotations d'emprunteurs, un prêteur privé de boutique qui protège sa marge, ou un investisseur en rénovation-revente qui vérifie combien de trésorerie il lui faut réellement à la clôture, ce classeur élimine toute approximation :

| Point de douleur courant en prêt / emprunt | Comment ce moteur Excel RTL automatisé le résout |
| :--- | :--- |
| **Le LTV passe tandis que le LTC ou le LTARV échoue silencieusement** | **Moteur de plafond à 4 ratios :** évalue simultanément **LTV, LTC, LTP et LTARV** et signale `PASS`, `EXCEPTION NEEDED` ou `FAIL` avant l'envoi d'une cotation. |
| **Gagner un dossier tout en perdant discrètement la marge du prêteur** | **Garde-fou instantané buy rate & marge :** compare chaque taux nominal coté à votre grille centralisée buy rate FICO/levier et signale `Below Margin` immédiatement dès que le plancher de marge est franchi. |
| **Dossiers qui tombent à l'eau à cause du Cash-to-Close de dernière minute** | **Contrôle du financement net et de la liquidité dès le jour 1 :** déduit d'emblée les points d'origination, les intérêts courts/prépayés et les frais de gestion afin que les emprunteurs voient le vrai Cash-to-Close et tout déficit de liquidité dès le premier jour. |
| **Des courtiers qui cotent des taux contradictoires** | **Grille centralisée FICO & expérience :** tire les taux standardisés et les ajustements d'un seul onglet maître de règles pour que chaque cotation reste cohérente. |
| **Fuite des buy rates de gros vers des représentants externes** | **Architecture tarifaire cloisonnée :** isole les buy rates propriétaires et le calcul de marge sur un onglet réservé aux administrateurs, verrouillable et masquable dans les copies destinées aux organisateurs. |
| **Assemblage manuel lent des cotations en période de forte activité** | **Résumé de cotation client en 1 clic :** consolide les données d'entrée, la validation du levier et le calcul du règlement en un term sheet préliminaire propre et prêt à partager en moins d'une minute. |

---

## 4 angles morts qui font échouer les dossiers de prêt privé

Même les organisateurs de prêts expérimentés et les investisseurs en rénovation-revente actifs commettent des erreurs coûteuses lorsqu'ils vérifient les ratios un par un dans des calculateurs dispersés :

1. **Le piège du ratio unique (le LTV semble correct, le LTARV tue le dossier) :** un dossier fix-and-flip peut afficher un **LTV As-Is confortable de 76.2%** et pourtant franchir la limite de politique de **88% LTARV** dès qu'un budget de réhabilitation lourde est ajouté. Tester les quatre plafonds de levier ensemble détecte les dossiers tueurs en quelques secondes.
2. **Le piège taux contre marge (gagner du volume, perdre du profit) :** réduire le taux nominal d'un emprunteur à **10.00%** face à un buy rate de **8.20%** ne laisse qu'une **marge de 1.80%** — franchissant silencieusement un **plancher de marge minimum de 2.50%**. La validation automatisée détecte l'érosion de marge *avant* que le term sheet ne quitte votre bureau.
3. **Le piège du Cash-to-Close (l'apport initial != la trésorerie totale nécessaire) :** sur un prêt de **$450,000**, **$6,250** d'intérêts courts prépayés et **$2,250** de frais de gestion ramènent le financement net à **$441,500** — transformant un écart attendu en un Cash-to-Close réel de **$26,500**. Si l'emprunteur ne détient que **$18,000** de liquidités, vous repérez immédiatement le **déficit de $8,500** au lieu de trois jours avant le règlement.
4. **Le piège de la fuite tarifaire :** partager une feuille de tarification non verrouillée expose vos coûts de capital de gros et vos règles de profit. Séparer les données d'entrée, les grilles tarifaires et les sorties client garde votre économie privée tout en permettant aux représentants de coter rapidement.

---

## Démarrage rapide : dimensionnez et tarifez tout prêt crédit relais ou réhabilitation en 4 étapes

Aucune écriture de formule Excel requise. Zéro macro VBA. **Zéro recopie de formule.**

1. **Testez la logique gratuitement en ligne (facultatif) :** ouvrez le [calculateur de prêts RTL gratuit dans le navigateur](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) pour effectuer un contrôle de cohérence rapide en 30 secondes.
2. **Définissez vos règles de prêt une fois (`03_Pricing_&_Assumptions`) :** dans le classeur `.xlsx`, saisissez vos limites de levier maximales (LTV, LTC, LTP, LTARV), votre grille buy rate FICO/expérience, vos points d'origination, vos frais de gestion et votre plancher de marge minimum.
3. **Collez les faits du dossier et de l'emprunteur (`02_Inputs`) :** saisissez le prix d'acquisition, la valeur As-Is, le budget de réhabilitation, l'ARV, le montant du prêt demandé, la durée du prêt, le FICO, l'expérience de rénovation-revente, les actifs liquides et le type de programme (**Bridge, Light Rehab, Heavy Rehab ou Ground-Up Construction**). Les menus déroulants empêchent les saisies invalides et grisent automatiquement les champs non applicables aux prêts Bridge.
4. **Livrez une cotation propre (`05_Quote_Summary`) :** examinez le verdict automatisé `PASS / EXCEPTION NEEDED / FAIL`, les métriques de levier déterminantes, le statut de la marge, le financement net et le vrai Cash-to-Close — prêt à enregistrer par dossier ou à exporter en term sheet préliminaire.

👉 **[Téléchargez le modèle Excel RTL Loan Sizer & Pricer hors ligne (.XLSX) — Achat unique avec garantie 30 jours](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)**

---

## Pour qui cette boîte à outils est conçue

Conçue pour les équipes de prêt opérationnelles, les courtiers et les investisseurs immobiliers qui veulent un **dimensionnement de dossier instantané et cohérent** sans payer de frais récurrents pour un système de montage de prêt (LOS) d'entreprise :

- **Prêteurs hard money & prêteurs privés / fonds de dette de boutique** : appliquez des règles uniformes LTV/LTC/LTP/LTARV et protégez le spread de rendement minimum du prêteur sur chaque cotation — sans frais SaaS d'entreprise.
- **Courtiers en crédit & organisateurs de prêts (LO)** : transformez des chiffres immobiliers bruts et des budgets de réhabilitation en cotations d'emprunteur propres et précises en moins de 60 secondes.
- **Assistants de traitement de prêt & coordinateurs de transaction** : auditez les intérêts prépayés, les frais d'origination, les fonds nets versés et les réserves de liquidité de l'emprunteur avant de commander les documents de clôture.
- **Analystes de crédit & souscripteurs** : présélectionnez les plafonds multi-ratios et remontez tôt les dossiers `EXCEPTION NEEDED` pour un examen de crédit structuré.
- **Investisseurs en rénovation-revente, réhabilitateurs & petits promoteurs** : vérifiez en sens inverse exactement combien un prêteur hard money financera — et votre vrai Cash-to-Close sortant de votre poche — *avant* de signer un compromis d'achat.

> **Note honnête de périmètre :** ce classeur est conçu spécifiquement pour le **dimensionnement de prêt en amont, la présélection d'éligibilité, la validation de marge et la génération de cotations préliminaires**. Il ne vise pas à remplacer la gestion de prêt post-clôture, la comptabilité des tirages de construction ou un logiciel de conformité réglementaire, et ne constitue ni un conseil en crédit ni un avis juridique.

---

## Foire aux questions

<details>
<summary><strong>Quelle est la différence entre LTV, LTC, LTP et LTARV ?</strong></summary>

- **LTV (Loan-to-Value) :** montant du prêt divisé par la valeur actuelle As-Is du bien telle qu'évaluée.
- **LTP (Loan-to-Purchase) :** avance d'acquisition divisée par le prix d'achat contractuel.
- **LTC (Loan-to-Cost) :** montant total du prêt divisé par le coût total du projet (prix d'achat + budget de réhabilitation).
- **LTARV (Loan-to-After-Repair-Value) :** montant total du prêt divisé par la valeur après travaux (ARV) prévue une fois les rénovations terminées.

Les prêteurs RTL plafonnant les quatre ratios simultanément, c'est le ratio le plus strict qui détermine le montant finançable maximal.
</details>

<details>
<summary><strong>Faut-il des compétences Excel avancées ou des macros pour utiliser le modèle hors ligne ?</strong></summary>

Non. Chaque grille de recherche, plafond de levier et formule de règlement est 100% préconstruite avec des formules Excel natives (zéro VBA/macro requis pour les calculs quotidiens). Collez simplement les chiffres du dossier dans `02_Inputs` et lisez vos résultats sur `05_Quote_Summary`. **Microsoft 365** ou **Excel 2021+** est recommandé pour une compatibilité native complète avec `XLOOKUP`.
</details>

<details>
<summary><strong>Puis-je masquer mes buy rates de gros avant de partager ce fichier avec des chargés de prêt ?</strong></summary>

Oui. Les règles de tarification et les tables de buy rates sont isolées sur `03_Pricing_&_Assumptions` et les calculs sur `04_Calc_Engine`, conçus pour prendre en charge une **Version Originator** protégée (verrouillage/masquage des onglets de tarification) en complément de votre **Version Admin interne** complète.
</details>

---

## Détails techniques & audit des formules

<details>
<summary><strong>Cliquez pour déplier : architecture en 5 onglets, modèle de sécurité, exemple détaillé de prêt fix-and-flip, formules & règles de validation</strong></summary>

### Architecture du classeur (5 feuilles de calcul en couches)

Le classeur sépare strictement les instructions, les saisies utilisateur, les grilles tarifaires confidentielles, les moteurs de calcul et les sorties de cotation destinées aux clients :

```text
01_ReadMe                 (Documentation, operating guide & version control)
        │
        ▼
02_Inputs                 (Borrower, property & requested loan terms — Editable)
        │
        ▼
03_Pricing_&_Assumptions  (Buy-rate grids, leverage caps & spread floors — Admin Only)
        │
        ▼
04_Calc_Engine            (Underwriting, pricing & settlement formulas — Locked)
        │
        ▼
05_Quote_Summary          (Printable client-ready preliminary term sheet — Locked)
```

| Feuille de calcul | Rôle | Droit de modification |
| :--- | :--- | :--- |
| **`01_ReadMe`** | Guide d'installation, historique des versions et documentation administrateur | Modifiable |
| **`02_Inputs`** | FICO de l'emprunteur, valeurs du bien, budget de réhabilitation et conditions de prêt demandées | Modifiable |
| **`03_Pricing_&_Assumptions`** | Grilles buy rate, plafonds LTV/LTC/LTP/LTARV, frais et planchers de marge | Administrateurs uniquement |
| **`04_Calc_Engine`** | Toutes les formules de levier, de recherche tarifaire, de règlement et d'éligibilité | Verrouillée |
| **`05_Quote_Summary`** | Cotation formatée destinée au client et résumé du dossier | Verrouillée |

### Conception de sécurité à double format

| Format de distribution | Public visé | Conception de protection |
| :--- | :--- | :--- |
| **Version Admin interne** | Dirigeants, souscripteurs, marchés de capitaux | Les 5 onglets visibles ; règles de tarification modifiables avec mot de passe admin |
| **Version Originator** | Chargés de prêt / représentants externes | `03_Pricing_&_Assumptions` et `04_Calc_Engine` masquées (`xlSheetVeryHidden`), barre de formule masquée, structure du classeur verrouillée |

---

### Scénario d'exemple détaillé (dimensionnement d'un prêt fix-and-flip)

| Donnée du dossier | Valeur |
| :--- | ---: |
| Prix d'acquisition | $300,000 |
| Budget de réhabilitation | $70,000 |
| Valeur As-Is du bien | $310,000 |
| Valeur après travaux (ARV) | $465,000 |
| Montant de prêt demandé | $340,000 |
| FICO / expérience de l'emprunteur | 726 / 6+ projets |
| Taux nominal / durée demandés | 11.25% / 12 mois |

**Sorties automatisées du moteur :**

| Métrique de souscription | Résultat calculé |
| :--- | ---: |
| LTV réel (`340k / 310k`) | **109.7%** *(dépasse le LTV préférentiel)* |
| LTC réel (`340k / 370k`) | **91.9%** |
| LTARV réel (`340k / 465k`) | **73.1%** |
| Spread de rendement du prêteur | **3.10%** *(valide — franchit le plancher de marge minimum)* |
| **Verdict global d'éligibilité** | **`EXCEPTION NEEDED`** |

Plutôt que d'approuver silencieusement un prêt surlevé ou de rejeter aveuglément un flippeur fidèle et rentable, le moteur classe le dossier comme **`EXCEPTION NEEDED`** afin que la direction du crédit puisse examiner immédiatement les facteurs compensatoires (expérience, liquidité ou garantie).

---

### Référence des formules principales

<details>
<summary>Formules de levier & de tarification</summary>

```excel
Actual_LTV   = IFERROR(LoanAmount / AsIsValue, 0)
Actual_LTC   = IFERROR(LoanAmount / (PurchasePrice + RehabBudget), 0)
Actual_LTP   = IFERROR(LoanAmount / PurchasePrice, 0)
Actual_LTARV = IF(ARV = 0, 0, IFERROR(LoanAmount / ARV, 0))

Spread       = NoteRate - BuyRate
SpreadStatus = IF(Spread < MinimumSpread, "Below Margin", "Valid")
```

*Les tables de tarification utilisent une correspondance exacte `XLOOKUP` (avec assainissement du texte via `TRIM` + `UPPER` et alertes de secours `"Check Risk Rules"`).*

</details>

<details>
<summary>Formules de règlement & de liquidité</summary>

```excel
NetFunding         = LoanAmount - ShortInterest - ServiceFee
CashToClose        = MAX(0, TotalProjectCost - NetFunding)
LiquidityShortfall = MAX(0, CashToClose - LiquidAssets)
```

</details>

---

### Règles intégrées de validation des entrées & de prévention des erreurs

| Champ | Règle de validation | Comportement de protection du modèle |
| :--- | :--- | :--- |
| **Programme de prêt** | Liste déroulante uniquement (Bridge / Light / Heavy / Construction) | Saisies invalides bloquées |
| **Prix d'acquisition & valeur As-Is** | Supérieur à `0` | Prévient les erreurs de division par zéro |
| **Budget de réhabilitation** | Mis à zéro pour les prêts Bridge | Champ automatiquement grisé par mise en forme conditionnelle |
| **ARV** | Requis pour les programmes Rehab/Construction | Affiche `N/A` là où non applicable |
| **Score FICO** | De `300` à `850` | Rejette les scores hors plage |
| **Durée du prêt** | `12` / `18` / `24` mois | Validation par liste déroulante appliquée |
| **Jours d'intérêts courts** | De `0` à `30` jours | Rejette les nombres de jours invalides |
| **Recherche buy rate** | `XLOOKUP` avec valeur de secours explicite | Renvoie `"Check Risk Rules"` au lieu de `#N/A` |
| **Validation de la marge** | Comparée au plancher de marge minimum | Signale `"Below Margin"` immédiatement |
| **Verdict global** | Évalue tous les indicateurs de levier, de marge & de liquidité | Renvoie le statut le plus strict : `PASS`, `EXCEPTION NEEDED` ou `FAIL` |

</details>

---

## À propos de Theseus Workshop

Je conçois des **boîtes à outils Excel décisionnelles prêtes à l'emploi** pour les décisions de crédit, d'immobilier et d'entreprise à forts enjeux, où trop de règles et de chiffres interagissent pour pouvoir être suivis de tête de manière fiable — sans abonnements SaaS récurrents.

Chaque classeur place vos lignes directrices, vos règles de tarification et vos contrôles de risque sur un seul écran hors ligne épuré, afin que vous puissiez coter et décider en toute confiance en moins d'une minute.

👉 **Explorez les 25+ modèles Excel hors ligne prêts à l'emploi :** [**Visitez Theseus Workshop**](https://www.theseusworkshop.com?utm_source=github&utm_medium=GitHub%20README_About&utm_content=residential-transitional-loan)

## Plus de boîtes à outils décisionnelles prêtes à l'emploi pour l'entreprise et le crédit

### Immobilier, crédit & construction
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** *(Gratuit / $0+)* — À quel prix maximum du terrain un lotissement résidentiel ou une construction de maisons en bande devient-il un investissement finançable par une banque ?
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — Évaluez locations, fix-and-flip, BRRRR, Airbnbs et constructions à neuf avec un radar de déficit de trésorerie sur 60 mois.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Une acquisition d'immeuble de 5+ logements crée-t-elle encore de la valeur après les rotations locatives unité par unité et les plafonds de prêt LTV/DSCR/Debt Yield ?
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Quels projets de contractors et quels clients sont réellement rentables après les vrais coûts de chantier ?
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Une construction résidentielle au Royaume-Uni atteint-elle sa marge cible lorsque les tarifs des corps de métier, les facteurs de gaspillage et la logistique de chantier varient ?

### Prêt privé, trésorerie & budgétisation
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — Que doit réellement l'emprunteur aujourd'hui, après des années de transferts informels et d'intérêts cumulés ?
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — Que doit réellement chaque investisseur, selon le moment de son entrée et la NAV actuelle ?
- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Pourquoi la trésorerie est-elle toujours tendue, et quand la liquidité baissera-t-elle à nouveau ?
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — Comment les choix opérationnels et de financement se répercutent-ils sur votre compte de résultat, votre bilan et votre flux de trésorerie intégrés ?
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Où les finances personnelles et professionnelles se mélangent-elles ?
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Pouvez-vous financer ce mois-ci les recrutements et le marketing sans griller votre runway ?
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — La croissance manquera-t-elle de cash avant que les cohortes de clients ne remboursent ?

### Rentabilité e-commerce, retail & marketplace
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Quelles commandes gagnent réellement de l'argent après la livraison, les frais de paiement et les commissions de marketplace ?
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Quels engagements d'inventaire et publicitaires déclencheront une crise de trésorerie dans les 12 prochaines semaines ?
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Chaque boutique Shopify est-elle réellement rentable une fois rapprochés le COGS par SKU, les frais bancaires et les OPEX partagés ?
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — Quels produits et mots-clés ont réellement motivé les variations de performance Amazon de cette semaine ?
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — Quelle est la vraie marge nette par SKU après le fret réel, les droits de douane et les retenues des distributeurs ?

### Tarification, manufacturing & allocation des coûts
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Quels prix de gros préservent la marge après fret, droits de douane, délais de paiement et change ?
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Quels SKUs sont rentables après main-d'œuvre d'usine, utilities, frais généraux et ingrédients ?
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — Que coter à chaque palier de quantité pour rester compétitif et rentable ?
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — La demande réelle a-t-elle suffisamment changé pour justifier un ajustement de prix ?
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Les factures fournisseurs partagées sont-elles réparties équitablement entre entités et actifs opérationnels ?
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — Quelle part de la marge de l'établissement est réelle, et quelle part est faussée par l'allocation des coûts du siège ?

### Logistique, commerce transfrontalier & opérations de services
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Quels flux commerciaux transfrontaliers restent rentables après les variations de change ?
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Quelles réservations de fret sont réellement bénéficiaires entre devises mixtes, frais et coûts de conteneurs ?
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Quels conteneurs et quels clients sont rentables, douanes et opérations de flotte comprises ?
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — Un café ou une boulangerie est-il réellement rentable après les coûts des recettes, la main-d'œuvre et les dépenses d'exploitation quotidiennes ?
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Quelles réservations de séjours génèrent un bénéfice net et un flux de trésorerie positif entre devises ?

---

## Questions, retours & mises à jour produit

Ce dépôt prend en charge **RTL Loan Sizer & Pricer**. Utilisez les canaux ci-dessous pour séparer les bugs techniques reproductibles des questions d'usage et des idées de flux de travail :

- **Questions & adéquation au flux de travail :** [Posez vos questions sur les programmes de prêt, les plafonds LTV/LTC/LTP/LTARV, les grilles tarifaires FICO ou le Cash-to-Close dans la Q&A communautaire](https://github.com/HyVoid/business-decision-toolbox/discussions/categories/questions)
- **Idées & améliorations :** [Suggérez de nouveaux programmes de prêt, règles de frais de clôture ou sorties de cotation](https://github.com/HyVoid/business-decision-toolbox/discussions/categories/ideas)
- **Mises à jour produit :** [Suivez les notes de maintenance & les nouvelles versions](https://github.com/HyVoid/business-decision-toolbox/discussions/categories/product-updates)
- **Signaler un bug technique :** [Ouvrez un rapport de bug](https://github.com/HyVoid/RTL_Loan_Sizer_Pricer/issues/new?template=bug-report.yml) avec votre version d'Excel, la feuille de calcul concernée et des étapes synthétiques de reproduction.

### Confidentialité & avertissement

**Ne publiez jamais de vrais noms d'emprunteurs, adresses de biens, numéros SSN/identifiants fiscaux, rapports de crédit, relevés bancaires, buy rates internes du prêteur, grilles tarifaires ou dossiers de prêt réels** dans les Issues ou Discussions publiques de GitHub. Utilisez toujours des identifiants fictifs et des chiffres d'exemple synthétiques.

Ce classeur est un outil analytique d'aide à la décision et ne constitue **pas** un avis juridique, un conseil en crédit, une approbation de souscription, une orientation comptable, une certification de conformité réglementaire ni une recommandation d'investissement. Les utilisateurs sont responsables de la vérification de toutes les hypothèses, barèmes de frais et lignes directrices de prêt avant de s'appuyer sur les résultats.

## Licence

Ce projet est publié sous la **licence Apache 2.0**.

Consultez le fichier `LICENSE` du dépôt pour les termes et conditions complets.
