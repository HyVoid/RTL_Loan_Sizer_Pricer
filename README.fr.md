[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# Dimensionnement et tarification des prêts RTL

## Outil léger d'aide à la décision pour les prêts résidentiels transitionnels, pour un dimensionnement, une tarification, une validation d'éligibilité et une génération de devis précis, prêts pour le client

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Status](https://img.shields.io/badge/Version-Stable-brightgreen)

**Dimensionnez, validez et tarifez les prêts résidentiels transitionnels de manière cohérente en quelques minutes—sans installation, sans codage et sans exposer la logique de tarification propriétaire. Disponible en version navigateur et en classeur Excel.**

**Aucune inscription. Aucune installation. Gratuit dans votre navigateur.**

Essayez la version navigateur gratuitement. Si vous avez besoin de la version Excel, vous pouvez l'acheter avec une garantie de remboursement de 30 jours, sans poser de questions.
>
> 🌐 **Ouvrir dans le navigateur**  
> [*Version HTML*](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> 📥 **Télécharger Excel**  
> [*Téléchargement Excel*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Ce que cela vous aide à suivre

- L'éligibilité du prêt par rapport aux limites d'effet de levier de souscription avant l'émission d'un devis.
- Le LTV, LTC, LTP et LTARV réels à travers différentes structures de prêts résidentiels transitionnels.
- Les besoins de financement de l'emprunteur, le produit net du financement et les liquidités estimées requises à la clôture.
- La cohérence de la tarification à travers les tranches FICO, les niveaux d'effet de levier et les hypothèses de tarification du prêteur.
- La protection de la marge en identifiant les prêts tarifés en dessous des exigences de spread interne.
- Des conditions de prêt prêtes pour le client générées à partir d'un seul flux de souscription au lieu de calculs assemblés manuellement.

---

## Flux de travail de démarrage rapide

### 1. Configurer les hypothèses de souscription

Les utilisateurs administratifs définissent les paramètres de prêt une seule fois sur la feuille dédiée Pricing & Assumptions. Ceux-ci comprennent les limites d'effet de levier, les grilles de tarification, les frais de service, les exigences de spread, les programmes de prêt et les seuils de souscription. Ces réglages ne nécessitent normalement qu'une maintenance périodique plutôt qu'un ajustement quotidien.

---

### 2. Saisir un nouveau scénario de prêt

Ouvrez la feuille **Inputs** et complétez les informations demandées.

Les informations typiques comprennent :

- Le prix d'achat
- La valeur en l'état
- Le budget de réhabilitation
- La valeur après réparation (ARV)
- Le montant de prêt demandé
- Le score FICO de l'emprunteur
- L'expérience de l'emprunteur
- Les actifs liquides
- La durée du prêt
- Le taux d'intérêt du prêt demandé

Les menus déroulants et les règles de validation réduisent les saisies incorrectes, tandis que la mise en forme conditionnelle désactive automatiquement les champs non applicables au programme de prêt sélectionné.

---

### 3. Examiner les résultats instantanément

Passez à la page Quote Summary.

Tous les calculs de souscription se mettent à jour automatiquement, notamment :

- L'éligibilité du prêt
- Les métriques d'effet de levier
- La validation de la tarification
- Les liquidités à la clôture
- Le financement net
- Les intérêts prépayés
- Les estimations de règlement

Aucun calcul manuel ni feuille de tarification séparée n'est requis.

---

### 4. Répéter pour chaque nouveau prêt

Chaque prêt supplémentaire ne nécessite que le remplacement des saisies de l'emprunteur.

Inutile de reconstruire les formules, de modifier les calculs ou de reconcevoir les rapports. Le moteur de tarification reste réutilisable à travers les scénarios de prêts relais, de prêts Fix-and-Flip, de réhabilitation lourde, de réhabilitation légère et de financement de construction.

**Définissez les paramètres de souscription une seule fois. Saisissez le scénario de prêt. Examinez la tarification. Générez le devis. Répétez chaque fois qu'un autre prêt doit être évalué.**

---

## Pourquoi j'ai construit cet outil

La souscription des prêts résidentiels transitionnels semble souvent simple parce que les prêteurs expérimentés connaissent déjà les principaux ratios qu'ils veulent approuver. En réalité, la plupart des erreurs de tarification surviennent bien avant qu'un prêt n'atteigne l'examen en comité.

Le problème est rarement de calculer le LTV ou le LTC individuellement. Le problème est d'évaluer chaque règle de souscription simultanément tout en protégeant la rentabilité du prêteur.

Un responsable du traitement pourrait calculer un LTV acceptable mais négliger que le taux d'intérêt du prêt demandé ne satisfait plus l'exigence de spread minimum. Un autre originateur peut coter un taux attractif qui correspond aux attentes de l'emprunteur mais qui tarife involontairement en dessous du taux d'achat requis du prêteur. Une troisième transaction peut satisfaire les exigences d'effet de levier mais exiger néanmoins beaucoup plus de liquidités de l'emprunteur que prévu, car les intérêts prépayés et les frais de service réduisent le financement disponible.

Au lieu de compter sur plusieurs feuilles de calcul déconnectées ou de vérifier manuellement les directives de souscription une règle à la fois, je voulais un cadre analytique réutilisable qui évalue ensemble chaque contrainte majeure de souscription.

Par exemple :

**Avant**

- Le LTV semble acceptable.
- L'emprunteur reçoit un devis verbal.
- La revue de tarification découvre plus tard un spread de prêteur insuffisant.
- Le devis doit être révisé.
- La confiance de l'emprunteur diminue.
- Le temps de traitement interne augmente.

**Après**

Le classeur évalue l'effet de levier, la tarification, la protection du spread, les coûts de règlement, les exigences de liquidité et l'éligibilité ensemble avant l'émission du devis. Le prêteur sait immédiatement si le scénario passe, nécessite une exception ou ne doit pas être poursuivi.

Ce classeur n'est pas simplement une calculatrice. Il intègre le raisonnement de souscription dans un processus d'aide à la décision reproductible qui réduit la structuration incohérente des prêts entre différents utilisateurs.

---

## Problèmes courants de prêt RTL que cet outil résout

| Problème | Sans cet outil | Avec cet outil |
|------------|-----------------|----------------|
| Prêt approuvé en utilisant un seul ratio d'effet de levier | Des limites de souscription importantes peuvent être négligées jusqu'à la revue finale | Tous les ratios d'effet de levier majeurs sont évalués simultanément avant la cotation |
| Tarification manuelle | Différents originateurs cotent des taux différents pour des emprunteurs identiques | La tarification est générée de manière cohérente à l'aide de règles de tarification centralisées |
| Érosion cachée de la rentabilité | Les prêts semblent acceptables mais violent les exigences de marge minimale | La validation du spread signale immédiatement la tarification en dessous des exigences du prêteur |
| Exigence de liquidités de l'emprunteur inattendue | Les coûts de règlement sont découverts tardivement à la clôture | Les liquidités à la clôture et le financement net sont calculés lors de la structuration initiale |
| Exceptions de prêt identifiées trop tard | Plusieurs révisions retardent la souscription | Les scénarios d'exception sont mis en évidence immédiatement pour la revue managériale |
| Logique de tarification interne exposée | Les calculs sensibles de taux d'achat deviennent visibles pour les utilisateurs externes | Les feuilles de tarification internes restent protégées dans les versions destinées aux originateurs |

---

## À qui s'adresse cet outil

Ce classeur est conçu pour les professionnels impliqués dans le prêt résidentiel transitionnel, notamment :

- Les prêteurs privés
- Les prêteurs non bancaires
- Les originateurs de prêts
- Les chargés de traitement des prêts
- Les souscripteurs
- Les équipes des marchés de capitaux
- Les petites sociétés de prêt recherchant une tarification de prêt standardisée
- Les équipes de crédit évaluant les prêts relais, de réhabilitation et de construction

Il est particulièrement utile pour les organisations qui ont besoin d'un flux de souscription léger sans mettre en œuvre un Loan Origination System (LOS) complet.

Il n'est **pas** destiné à remplacer les plateformes de prêt d'entreprise, les logiciels de servicing ou les systèmes de gestion de la conformité.

Aucune expertise en tableur n'est requise. Ouvrez la version navigateur ou le classeur Excel, saisissez les informations du prêt et commencez immédiatement à évaluer les scénarios de prêt.

---

## À propos

Je construis des outils analytiques légers pour des situations où trop de variables opérationnelles doivent être considérées en même temps. Plutôt que de remplacer les logiciels d'entreprise, ces classeurs intègrent la prise de décision pratique dans des cadres réutilisables qui aident les équipes à parvenir à des conclusions cohérentes avec moins d'effort manuel.

Le **Dimensionnement et tarification des prêts RTL** suit cette philosophie en réunissant les règles de souscription, la logique de tarification, la validation d'effet de levier, les calculs de règlement et la génération de devis dans un flux de travail structuré unique. La question centrale est toujours la même : **Quelles informations doivent être visibles en un seul endroit pour prendre la prochaine décision de prêt avec confiance ?**
## Détails techniques

<details>
<summary><strong>Pour les relecteurs techniques, les praticiens d'Excel et les collaborateurs</strong></summary>

---

## Architecture du classeur

Le classeur suit une architecture en couches qui sépare l'interaction utilisateur, les règles métier, les calculs analytiques et la présentation. Cela empêche la modification accidentelle de la logique de tarification tout en gardant l'opération quotidienne simple pour les originateurs de prêts.

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

## Responsabilités des feuilles

| Feuille | Objet | Modifiable |
|------------|---------|----------|
| 01_ReadMe | Instructions, historique des versions, documentation de l'administrateur | Oui |
| 02_Inputs | Informations sur l'emprunteur et conditions de prêt demandées | Oui |
| 03_Pricing_&_Assumptions | Grilles de taux d'achat, règles d'effet de levier, hypothèses de tarification | Administrateurs uniquement |
| 04_Calc_Engine | Calculs de souscription, moteur de tarification et validation | Non |
| 05_Quote_Summary | Fiche de conditions imprimable destinée au client | Non |

---

## Flux de données

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

Chaque sortie affichée aux utilisateurs provient du moteur de calcul. Aucune valeur n'est saisie manuellement dans le devis final.

---

## Stratégie de sécurité

Le classeur est délibérément compilé en deux formats de distribution.

| Version | Utilisateurs visés | Composants protégés |
|---------|----------------|----------------------|
| Version interne | Principaux, souscripteurs, opérations | Toutes les feuilles visibles avec mot de passe administrateur |
| Version originateur | Originateurs de prêts | Tableaux de tarification et moteur de calcul masqués avec xlSheetVeryHidden |

Les mesures de protection supplémentaires comprennent :

- Protection de la structure du classeur
- Formules masquées
- Cellules de calcul verrouillées
- Grilles de tarification protégées
- Barre de formules masquée (version originateur)
- Structure de feuille protégée par mot de passe

Cette approche protège la tarification propriétaire du prêteur sans maintenir deux classeurs indépendants.

---

## Trois pièges qui trompent même les originateurs de prêts expérimentés

---

## Piège 1 — Ne regarder que le LTV

De nombreux prêteurs se concentrent instinctivement sur le prêt-valeur parce que c'est la métrique de souscription la plus familière.

Malheureusement, le prêt transitionnel s'appuie rarement sur un seul ratio d'effet de levier.

### Décision incorrecte

Prix d'achat

```
$400,000
```

Prêt demandé

```
$320,000
```

Valeur en l'état

```
$420,000
```

LTV calculé

```
76.2%
```

L'originateur conclut :

> "Le prêt respecte la politique."

Cependant...

Budget de réhabilitation

```
$160,000
```

Coût total du projet

```
$560,000
```

LTC réel

```
57.1%
```

LTARV réel

```
88%
```

Le LTARV dépasse la politique interne.

Le prêt est en réalité hors des directives de prêt.

### Approche correcte

Évaluez :

- LTV
- LTC
- LTARV
- LTP

avant de déterminer l'éligibilité.

<details>

<summary>Référence des formules</summary>

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

Résultat :

Le classeur évalue automatiquement chaque ratio d'effet de levier ensemble avant d'attribuer un statut Pass, Exception ou Fail.

---

## Piège 2 — Coter avant de vérifier la marge

Un emprunteur demande un taux attractif.

L'originateur abaisse le taux d'intérêt du prêt pour rester compétitif.

Tout semble acceptable.

Plus tard...

Le marketing secondaire découvre que le spread du prêteur est tombé sous les minimums internes.

Le devis doit être révisé.

### Décision incorrecte

Taux de l'emprunteur

```
10.00%
```

Taux d'achat

```
8.20%
```

Spread

```
1.80%
```

Spread minimum requis

```
2.50%
```

La transaction est en réalité en dessous des exigences de rentabilité du prêteur.

### Approche correcte

Chaque devis devrait valider la tarification avant présentation.

<details>

<summary>Référence des formules</summary>

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

Au lieu de découvrir le problème lors de la revue finale, le classeur signale immédiatement :

```
Below Margin
```

permettant de corriger la tarification avant que l'emprunteur ne reçoive un devis.

---

## Piège 3 — Sous-estimer les liquidités requises à la clôture

De nombreux emprunteurs n'évaluent que le montant de prêt demandé.

Les coûts de règlement réduisent le produit réel.

Ignorer ces déductions produit fréquemment des attentes irréalistes de l'emprunteur.

### Exemple

Prêt demandé

```
$450,000
```

Intérêts intercalaires

```
$6,250
```

Frais de service

```
$2,250
```

Financement net

```
$441,500
```

Liquidités requises

```
$468,000
```

Liquidités réelles à la clôture

```
$26,500
```

Si la liquidité de l'emprunteur s'élève à seulement

```
$18,000
```

le prêt ne peut pas être clôturé sans fonds supplémentaires.

### Approche correcte

Calculez le produit de règlement plutôt que de supposer que le montant brut du prêt équivaut au financement disponible.

<details>

<summary>Référence des formules</summary>

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

Le classeur identifie les pénuries de liquidité avant que les documents de clôture ne soient préparés.

---

## Scénario d'exemple

Considérez la transaction Fix-and-Flip suivante.

| Poste | Valeur |
|------|------:|
| Prix d'achat | $300,000 |
| Budget de réhabilitation | $70,000 |
| Valeur en l'état | $310,000 |
| ARV | $465,000 |
| Prêt demandé | $340,000 |
| FICO | 726 |
| Expérience | 6+ Projects |
| Taux d'intérêt du prêt | 11.25% |
| Durée du prêt | 12 Months |

Le moteur de tarification récupère le taux d'achat correspondant en fonction de la tranche FICO de l'emprunteur et de l'effet de levier calculé.

Le moteur de calcul détermine ensuite :

- LTV réel
- LTC réel
- LTP réel
- LTARV réel
- Spread
- Financement net
- Liquidités à la clôture
- Profit estimé du prêteur

Supposons que les métriques résultantes soient :

| Métrique | Résultat |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Éligibilité | Exception Needed |

Bien que la tarification reste rentable, l'effet de levier dépasse le seuil LTV préféré.

Plutôt que de refuser immédiatement le prêt, le classeur le classe comme **Exception Needed**, permettant à la direction d'examiner les facteurs de compensation tels que l'expérience de l'emprunteur, la liquidité ou des garanties supplémentaires.

Ce flux de travail structuré crée un processus de souscription cohérent où la tarification, l'effet de levier, le règlement et la rentabilité sont évalués ensemble plutôt qu'indépendamment.

---

## Référence des formules

<details>

<summary>Calculs d'effet de levier</summary>

| Calcul | Formule |
|-------------|---------|
| LTV réel | `Loan Amount ÷ As-Is Value` |
| LTC réel | `Loan Amount ÷ (Purchase + Rehab)` |
| LTP réel | `Loan Amount ÷ Purchase Price` |
| LTARV réel | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Moteur de tarification</summary>

| Formule | Objet |
|----------|----------|
| XLOOKUP | Récupérer le taux d'achat |
| INDEX + MATCH | Recherche de tarification héritée |
| Spread | Taux d'intérêt du prêt − Taux d'achat |
| Statut du spread | Validation de la marge |

La tarification utilise toujours un comportement de recherche exact avec une gestion d'erreur par défaut pour empêcher les sorties de tarification invalides.

</details>

<details>

<summary>Calculs de règlement</summary>

| Calcul | Objet |
|-------------|----------|
| Intérêts intercalaires | Intérêts perçus à la clôture |
| Frais de service | Frais déduits sur la durée du prêt |
| Financement net | Fonds disponibles pour l'emprunteur |
| Liquidités à la clôture | Contribution supplémentaire de l'emprunteur |
| Déficit de liquidité | Déficit de financement |

</details>

<details>

<summary>Règles d'éligibilité</summary>

Le moteur de souscription évalue :

- LTV maximum
- LTC maximum
- LTARV maximum
- Marge de tarification
- Liquidité de l'emprunteur

Résultats possibles :

- PASS
- EXCEPTION NEEDED
- FAIL

L'éligibilité globale reflète toujours le résultat de souscription le plus restrictif.

</details>

## Règles de validation

| Champ | Règle de validation | Comportement en cas d'erreur |
|------|-----------------|----------------|
| Loan Type | Menu déroulant uniquement | Rejeter les valeurs invalides |
| Purchase Price | Supérieur à zéro | Renvoyer des calculs nuls |
| As-Is Value | Supérieur à zéro | Empêcher la division par zéro |
| Rehab Budget | Zéro pour les prêts relais | Champ automatiquement grisé |
| ARV | Requis pour les produits de réhabilitation | Afficher N/A le cas échéant |
| Requested Loan | Devise positive | Rejeter les valeurs négatives |
| FICO | 300–850 | Rejeter le score invalide |
| Experience Tier | Menu déroulant uniquement | Empêcher les échecs de recherche |
| Loan Term | 12 / 18 / 24 mois | Rejeter les autres valeurs |
| Short Interest Days | 0–30 | Rejeter la saisie invalide |
| Buy Rate Lookup | XLOOKUP avec valeur de repli | "Check Risk Rules" |
| Division Operations | Enveloppe IFERROR | Renvoyer 0 au lieu des erreurs Excel |
| Text Lookups | TRIM + UPPER | Empêcher les écarts d'espaces et de casse |
| Margin Check | Comparaison avec le spread minimum | Renvoyer "Below Margin" |
| Eligibility | Évaluer tous les indicateurs de souscription | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Autres outils de cette série

Le **Dimensionnement et tarification des prêts RTL** fait partie d'une collection croissante d'outils opérationnels légers d'aide à la décision conçus pour les professionnels qui ont besoin d'analyses fiables sans mettre en œuvre de logiciels d'entreprise.

Chaque outil suit les mêmes principes :

- Aucune inscription requise
- Aucune installation requise
- Disponible en éditions Navigateur et Excel
- Basé sur les formules plutôt que sur les macros
- Conçu pour des décisions opérationnelles reproductibles plutôt que pour des rapports ponctuels

| Outil | Objet |
|------|---------|
| Construction Estimating System | Standardiser l'estimation de projet, les assemblages, la tarification des offres et le suivi des coûts. |
| Inventory Forecasting & Reorder Planner | Prévoir la demande d'inventaire, identifier le moment de réapprovisionnement et surveiller le risque de rupture. |
| Retail & Maquila Inventory Ledger | Suivre le mouvement des stocks au niveau de la pièce, la production, les défauts et la distribution. |
| Unified Personal & Business Budget Framework | Consolider les flux de trésorerie personnels et professionnels dans un seul modèle de planification financière. |
| Cross-Border VAT Compliance Dashboard | Surveiller les obligations de TVA dans plusieurs pays et canaux de vente. |
| Project Financial Control Dashboard | Comparer le budget, les engagements, les factures, la facturation d'avancement et la rentabilité du projet. |
| Coffee Shop Operations Audit Toolkit | Évaluer la performance opérationnelle du café à l'aide d'une notation d'audit standardisée et d'une analyse KPI. |

---

## Avertissement

Ce classeur est destiné à être un outil analytique d'aide à la décision.

Il ne constitue **pas** :

- un conseil juridique,
- un conseil en prêt,
- une approbation de souscription,
- une orientation comptable,
- une certification de conformité réglementaire,
- une recommandation d'investissement.

Toutes les décisions de prêt restent soumises aux politiques de souscription de l'établissement de prêt, aux réglementations applicables, aux exigences des investisseurs et à l'approbation de crédit finale.

Les utilisateurs sont responsables de la vérification de toutes les hypothèses, paramètres de tarification, barèmes de frais et règles de souscription avant de se fier aux sorties générées.

---

## Remerciements

Ce projet reflète les pratiques de souscription courantes utilisées dans le prêt résidentiel transitionnel, notamment les prêts relais, le financement Fix-and-Flip, les prêts de réhabilitation et le prêt à la construction résidentielle.

Son architecture met l'accent sur la transparence, la répétabilité et la cohérence opérationnelle afin que les décisions de tarification puissent être reproduites, examinées et auditées plutôt que de dépendre de la connaissance individuelle des tableurs.

---

**Apache License 2.0 © 2026**

Construit dans le cadre d'une collection plus large d'outils opérationnels légers d'aide à la décision pour la finance, la construction, la gestion des stocks et les opérations commerciales.
