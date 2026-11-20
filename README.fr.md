[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# RTL Loan Sizer & Pricer : calculateur de prêt résidentiel transitionnel gratuit et modèle Excel de souscription Fix-and-Flip
<img width="1245" height="1209" alt="image" src="https://github.com/user-attachments/assets/856c2ddf-16a5-4212-a162-b3e82ab67dcc" />


![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser Web App and Offline Excel Workbook](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Category: RTL Underwriting and Loan Pricing Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Release Status: Production Stable](https://img.shields.io/badge/Version-Stable-brightgreen)

**RTL Loan Sizer & Pricer** est un **calculateur de prêts résidentiels transitionnels (RTL)** prêt à l'emploi, un **moteur de tarification de prêts Fix-and-Flip** et un **modèle Excel de souscription hard money**. Utilisez-le pour dimensionner des prêts Bridge, Light Rehab, Heavy Rehab et Ground-Up Construction, valider les limites LTV, LTC, LTP et LTARV, vérifier le spread de rendement du prêteur par rapport à votre taux de refinancement, et calculer le Cash-to-Close de l'emprunteur en moins d'une minute. Testez gratuitement l'outil navigateur en ligne, sans inscription, ou achetez une seule fois le classeur Excel hors ligne réutilisable avec une garantie de remboursement de 30 jours sans condition.

> **Outil en ligne gratuit (à essayer immédiatement dans votre navigateur)**  
> [Lancez le calculateur de prêts RTL gratuit dans le navigateur (dimensionnement instantané de prêts Fix-and-Flip et Bridge)](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> **Feuille de calcul hors ligne réutilisable (achat unique, garantie de remboursement de 30 jours)**  
> [Obtenez le modèle Excel RTL Loan Sizer & Pricer hors ligne réutilisable sur Theseus Workshop](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Points critiques de la souscription des prêts résidentiels transitionnels et solutions automatisées

Les opérations de prêt privé stagnent lorsque les limites d'effet de levier, les ajustements de taux par tranche de crédit et les déductions à la clôture sont vérifiés dans des feuilles de calcul séparées. Cet outil de souscription RTL fait correspondre chaque écart de calcul courant à des sorties automatisées :

| Point critique du prêt hard money et RTL | Solution automatisée dans ce RTL Loan Sizer | Métriques et sorties de souscription suivies |
| :--- | :--- | :--- |
| **Coter des opérations inéligibles avant la revue de crédit** | Vérifie automatiquement chaque opération par rapport aux plafonds configurés de votre programme avant l'émission d'une fiche de conditions | Statut d'éligibilité Pass / Exception / Decline pour les programmes Bridge, Rehab et Construction |
| **Calculer un seul ratio d'effet de levier à la main** | Évalue les quatre contraintes de dimensionnement des prêts résidentiels transitionnels simultanément et lie le prêt à la limite la plus stricte | **LTV** (Loan-to-Value), **LTC** (Loan-to-Cost), **LTP** (Loan-to-Purchase) et **LTARV** (Loan-to-After-Repair-Value) |
| **Surprises tardives sur le Cash-to-Close de l'emprunteur** | Déduit dès le dimensionnement initial les points d'origine, les intérêts prépayés et les frais de service | **Produit net du financement**, **Cash-to-Close** total, structure de rétention des fonds de réhabilitation et contrôle de la réserve de liquidité |
| **Taux incohérents entre originateurs de prêts** | Applique les ajustements tarifaires d'une matrice de taux centralisée liée aux tranches de score de crédit et d'effet de levier | Tarification par **tranche FICO**, ajustements selon l'expérience de l'emprunteur et taux nominal standardisé |
| **Érosion cachée de la marge sous le taux de refinancement** | Signale immédiatement tout taux nominal demandé qui passe sous votre plancher interne de spread de rendement | **Taux de refinancement du prêteur**, **validation du spread minimal** et statut de protection de la marge nette |
| **Assemblage manuel lent des devis en période de pointe** | Regroupe données d'entrée, règles de souscription et calculs de clôture dans une seule vue formatée prête pour le client | **Quote Summary** prête à envoyer et décomposition préliminaire des conditions de prêt |

---

## Guide de démarrage rapide : dimensionner et tarifer un prêt Fix-and-Flip ou Bridge en 4 étapes

Vous pouvez exécuter un scénario de test dès maintenant dans l'[application web RTL Loan Sizer en ligne gratuite](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/), puis transférer votre pipeline quotidien dans le classeur Excel hors ligne une fois que vous avez confirmé qu'il correspond à vos directives de prêt.

### Étape 1. Configurez une seule fois vos règles de souscription et votre grille tarifaire

Configurez vos paramètres de prêt sur la feuille de calcul **Pricing & Assumptions**. Saisissez vos limites d'effet de levier maximales (LTV, LTC, LTP, LTARV), vos grilles tarifaires FICO, vos points d'origine, vos frais de service, vos exigences de spread minimales du prêteur et vos programmes de prêt pris en charge. Après la configuration initiale, vous ne mettez à jour cet onglet que lorsque votre partenaire de capital ou votre comité de crédit modifie les directives.

### Étape 2. Collez les chiffres de l'emprunteur et du bien dans Inputs

Ouvrez la feuille de calcul **Inputs** et saisissez les données de l'opération :

- Prix d'achat et valeur du bien en l'état (As-Is)
- Budget de réhabilitation / construction et valeur après travaux (ARV)
- Montant de prêt demandé et durée du prêt
- Score FICO de l'emprunteur, expérience de fix-and-flip antérieure et actifs liquides vérifiés
- Taux nominal demandé et programme de prêt sélectionné (Bridge, Light Rehab, Heavy Rehab ou Construction)

Les menus déroulants intégrés et la validation des données bloquent les saisies invalides. La mise en forme conditionnelle grise les champs qui ne s'appliquent pas au programme de prêt choisi.

### Étape 3. Consultez les résultats de souscription, de tarification et de Cash-to-Close

Ouvrez la feuille de calcul **Quote Summary** pour examiner la décomposition complète de l'opération en un seul endroit :

- Verdict d'éligibilité du prêt et signalements d'exceptions
- Métriques d'effet de levier déterminantes (LTV, LTC, LTP et LTARV)
- Validation du taux par rapport au taux de refinancement et aux règles de spread minimal
- Intérêts prépayés, estimations de règlement, produit net du financement et Cash-to-Close de l'emprunteur

### Étape 4. Passez au classeur Excel hors ligne réutilisable pour les opérations de votre pipeline quotidien

La tarification des prêts résidentiels transitionnels implique une logique de souscription à plusieurs niveaux, et pourtant vous n'avez jamais besoin d'écrire une seule formule, de déboguer des références de cellules cassées ni de faire glisser des équations le long d'une colonne. Chaque règle de correspondance et chaque formule auto-mise à jour est pré-construite dans le modèle Excel.

Téléchargez le classeur sur votre ordinateur, collez vos propres chiffres d'opération dans les cellules d'entrée et obtenez des décisions de souscription claires en moins d'une minute. Même un débutant sans aucune expérience de modélisation sur tableur obtient immédiatement une analyse commerciale structurée, libérant des heures en haute saison pour les appels aux courtiers, les négociations avec les emprunteurs et les clôtures d'opérations.

**Pourquoi les équipes de prêt passent de l'essai navigateur gratuit au classeur Excel hors ligne payant :**

- **Achat unique, réutilisation illimitée :** Payez une fois au lieu de souscrire des abonnements SaaS mensuels récurrents pour des Loan Origination Systems (LOS) d'entreprise ou des moteurs de tarification cloud. Remplacez les données d'entrée et réutilisez le même flux de travail figé pour chaque opération Bridge, Fix-and-Flip, Rehab et Construction.
- **Confidentialité des données 100 % locale :** Enregistrez et exécutez le fichier hors ligne sur votre propre machine. Les données financières sensibles des emprunteurs, les taux de refinancement internes et les planchers de spread du prêteur ne résident jamais sur des serveurs cloud tiers.
- **Garantie sans risque :** La version navigateur est gratuite à tester en ligne. Le classeur Excel téléchargeable est un produit payant couvert par une **garantie de remboursement de 30 jours sans condition**.

> **Prêt à standardiser votre flux de souscription hors ligne ?**  
> [Téléchargez le modèle Excel RTL Loan Sizer & Pricer hors ligne réutilisable (achat unique, garantie de remboursement de 30 jours)](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Logique métier et méthodologie : comment la souscription RTL automatisée prévient les angles morts de décision cachés

La plupart des erreurs de tarification dans le prêt immobilier privé surviennent bien avant qu'un dossier de prêt n'atteigne le comité de crédit. Même les originateurs expérimentés commettent des erreurs de cotation coûteuses lorsqu'ils calculent les ratios un par un dans des feuilles déconnectées. Pour les nouveaux venus au hard money ou au prêt Fix-and-Flip, quatre angles morts commerciaux spécifiques font échouer des opérations ou anéantissent en silence le profit du prêteur.

### 1. L'angle mort du ratio unique (pourquoi un LTV conforme peut encore échouer à la souscription)

**Fait objectif :** un prêt Fix-and-Flip qui semble sûr à 75 % de LTV en l'état peut néanmoins dépasser un plafond de 90 % de LTC ou de 70 % de LTARV dès qu'un budget de réhabilitation important est inclus.  
**Comment ce modèle le résout :** le moteur de dimensionnement calcule le LTV, le LTC, le LTP et le LTARV en parallèle et impose le montant de prêt admissible le plus bas parmi les quatre ratios. Vous identifiez la contrainte déterminante exacte avant de coter des conditions à un emprunteur.

### 2. L'angle mort taux vs spread (gagner une opération en perdant la marge)

**Fait objectif :** aligner le taux nominal d'un concurrent pour gagner un emprunteur fait souvent descendre le prêt sous votre taux de refinancement interne ou votre spread de rendement minimal une fois les ajustements FICO et d'effet de levier appliqués.  
**Comment ce modèle le résout :** chaque taux nominal coté est automatiquement testé contre votre matrice centralisée de taux de refinancement et votre exigence de spread minimale. Si une opération viole votre plancher de profit, la feuille la signale immédiatement afin que vous puissiez re-tarifer ou ajouter des points d'origine avant d'émettre une fiche de conditions.

### 3. L'angle mort du Cash-to-Close (des opérations qui meurent quelques jours avant la clôture)

**Fait objectif :** les emprunteurs débutants et les processeurs juniors supposent fréquemment que l'apport initial équivaut au total des liquidités nécessaires. Les intérêts prépayés, les frais d'origine, les frais de service et les règles de réserve de liquidité réduisent le produit net du financement et augmentent les liquidités requises à la clôture.  
**Comment ce modèle le résout :** le classeur calcule dès le premier jour le financement net du prêt, les déductions initiales et le Cash-to-Close total de l'emprunteur. Les emprunteurs connaissent immédiatement leur besoin réel en liquidités, ce qui réduit les abandons tardifs.

### 4. L'angle mort de la fuite tarifaire (exposer les taux de refinancement propriétaires)

**Fait objectif :** remettre une feuille de tarification non verrouillée à des courtiers externes ou à des représentants juniors expose vos taux de refinancement de gros, vos coûts de capital et vos règles de marge internes.  
**Comment ce modèle le résout :** les tableaux de tarification et les formules de spread résident sur un onglet d'hypothèses dédié qui peut être verrouillé et masqué dans les versions destinées aux originateurs, préservant la confidentialité des données économiques sensibles tout en maintenant une cotation en libre-service rapide.

### Changement de flux de travail concret : avant vs après

**Avant (cotation manuelle)**
1. L'originateur vérifie le LTV en l'état dans une calculatrice rapide et envoie un devis verbal à l'emprunteur.
2. La revue de souscription découvre ensuite un dépassement de LTARV et un déficit de spread sous le taux de refinancement du prêteur.
3. L'équipe révise le devis à la baisse et augmente le Cash-to-Close requis de l'emprunteur.
4. La confiance de l'emprunteur chute, les retards de clôture s'accumulent et le personnel interne passe des heures à retravailler un seul dossier.

**Après (flux de travail automatisé du RTL Loan Sizer)**
1. L'originateur saisit une seule fois les chiffres du bien, le budget de réhabilitation et le FICO de l'emprunteur.
2. Le classeur vérifie en quelques secondes, simultanément, les plafonds d'effet de levier, le plancher de spread, les déductions de règlement et les réserves de liquidité.
3. L'équipe sait immédiatement si l'opération passe sans réserve, nécessite une exception de la direction ou doit être refusée avant l'envoi d'un devis.

---

## Cotation hard money manuelle vs RTL Loan Sizer automatisé : comparaison opérationnelle

| Goulot d'étranglement du prêt résidentiel transitionnel | Risque de la feuille de calcul ad hoc et de la cotation manuelle | Flux de travail standardisé du RTL Loan Sizer |
| :--- | :--- | :--- |
| **Dimensionnement du prêt sur un seul ratio** | Approuver sur le seul LTV laisse passer les plafonds LTC, LTP ou LTARV jusqu'à la revue en comité de crédit | Évalue le LTV, le LTC, le LTP et le LTARV simultanément et impose le plafond de prêt déterminant avant la cotation |
| **Recherches manuelles dans les grilles de taux** | Différents chargés de prêt cotent des taux et des points contradictoires pour des profils FICO et d'effet de levier identiques | Applique des taux et ajustements uniformes issus d'une grille de tarification FICO et d'effet de levier centralisée |
| **Compression de marge passée inaperçue** | Des prêts franchissent les contrôles d'effet de levier tout en étant tarifés silencieusement sous le taux de refinancement interne et les planchers de spread | La validation intégrée du spread signale immédiatement tout devis sous les exigences de marge minimale du prêteur |
| **Cash-to-Close de l'emprunteur inattendu** | Intérêts prépayés, points d'origine et déductions de service font surface tardivement, près de la table de clôture | Calcule le produit net du financement, les déductions de règlement et le Cash-to-Close dès la structuration initiale |
| **Découverte tardive des exceptions de souscription** | De multiples révisions de fiches de conditions bloquent les pipelines de souscription et frustrent les courtiers | Met en évidence les exceptions de politique sans délai pour une validation managériale structurée |
| **Logique tarifaire de gros exposée** | Les classeurs manuels partagés fuient les taux de refinancement internes et les marges bénéficiaires vers des tiers | Sépare les hypothèses de tarification protégées des feuilles de saisie des originateurs et du récapitulatif de devis |

---

## Qui utilise ce calculateur de prêt RTL : cas d'usage par rôle pour prêteurs privés, courtiers et équipes hard money

Cet outil s'intègre aux flux de travail quotidiens de l'industrie du prêt résidentiel transitionnel, sans exiger de compétences en modélisation sur tableur ni un déploiement lourd de logiciel d'entreprise :

| Rôle / Intitulé de poste | Besoin principal de recherche et de flux de travail | Comment ils utilisent RTL Loan Sizer & Pricer |
| :--- | :--- | :--- |
| **Prêteurs hard money et prêteurs privés** | Feuille de tarification de prêts hard money et moteur de dimensionnement d'opérations | Appliquer des plafonds LTV/LTC/LTARV cohérents et protéger le spread minimal du prêteur sur chaque devis |
| **Courtiers en crédit et originateurs de prêts (LO)** | Générateur de devis de prêts Fix-and-Flip et outil de pré-qualification des emprunteurs | Transformer des chiffres de bien bruts et des budgets de réhabilitation en fiches de conditions propres pour l'emprunteur en moins d'une minute |
| **Processeurs de prêts et coordinateurs de transactions** | Calculateur de Cash-to-Close et de financement net pour prêts Bridge | Vérifier les intérêts prépayés, les frais de service, la liquidité de l'emprunteur et le produit net avant de commander les documents de clôture |
| **Analystes de crédit et souscripteurs** | Vérificateur d'éligibilité des prêts RTL et modèle de présélection des exceptions | Auditer les limites d'effet de levier multi-ratios et signaler les opérations atypiques avant la revue en comité de crédit |
| **Équipes marchés de capitaux et desk secondaire** | Validation des taux de refinancement et modèle de spread de rendement du prêteur | Maintenir des grilles tarifaires centralisées et confirmer que la tarification au niveau du prêt franchit les seuils de cession secondaire |
| **Petites sociétés de prêt privé et fonds de dette de boutique** | Alternative LOS légère en classeur Excel | Standardiser la souscription Bridge, Light Rehab, Heavy Rehab et Ground-Up Construction sans frais SaaS d'entreprise |
| **Investisseurs immobiliers et house flippers** | Analyseur d'opérations hard money adapté aux débutants | Estimer le montant maximal de financement et le total des liquidités requises à la clôture avant de déposer une demande de prêt |

**Note de périmètre :** ce classeur est conçu spécifiquement pour le dimensionnement de prêts en amont, la validation d'éligibilité, les contrôles de tarification et la génération de devis. Le servicing des prêts, la comptabilité des décaissements de tranches et la gestion de la conformité réglementaire restent du ressort de plateformes dédiées de servicing et de conformité.

---

## Foire aux questions (dimensionnement RTL et modèle Excel)

<details>
<summary><strong>Quelle est la différence entre LTV, LTC, LTP et LTARV dans un prêt résidentiel transitionnel ?</strong></summary>

- **LTV (Loan-to-Value) :** montant du prêt divisé par la valeur en l'état (As-Is) actuelle du bien telle qu'évaluée.
- **LTP (Loan-to-Purchase) :** avance initiale d'acquisition divisée par le prix d'achat contractuel.
- **LTC (Loan-to-Cost) :** montant total du prêt divisé par le coût total du projet (prix d'achat plus budget de réhabilitation).
- **LTARV (Loan-to-After-Repair-Value) :** montant total du prêt divisé par la valeur après travaux (ARV) projetée une fois les rénovations terminées.

Comme les prêteurs hard money plafonnent les quatre ratios simultanément, c'est le montant de prêt le plus bas obtenu qui définit votre taille de prêt admissible maximale.
</details>

<details>
<summary><strong>Faut-il des compétences Excel avancées pour utiliser le modèle hors ligne ?</strong></summary>

Non. Toutes les grilles tarifaires, formules d'effet de levier et vérifications conditionnelles sont préconfigurées. Vous collez simplement les données de l'opération dans les cellules dédiées de l'onglet **Inputs** et lisez vos résultats dans l'onglet **Quote Summary**.
</details>

<details>
<summary><strong>Quelle est la différence entre la version navigateur gratuite et la version Excel payante ?</strong></summary>

Le [calculateur de prêts RTL gratuit dans le navigateur](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) vous permet de tester la logique de souscription en ligne immédiatement, sans création de compte. Le [classeur Excel hors ligne payant](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan) vous donne un fichier local permanent que vous pouvez personnaliser avec vos propres grilles tarifaires, enregistrer par opération, réutiliser indéfiniment pour un paiement unique (avec garantie de remboursement de 30 jours) et garder totalement à l'écart des serveurs cloud tiers.
</details>

---

## À propos de Theseus Workshop

**Theseus Workshop** conçoit des classeurs d'analyse légers et réutilisables pour les décisions commerciales et de prêt où trop de variables financières interagissent simultanément. Chaque modèle intègre une logique de souscription et d'analyse commerciale éprouvée dans un flux de travail Excel hors ligne et épuré, afin que les petites équipes et les opérateurs indépendants parviennent à des décisions cohérentes et défendables en quelques minutes.

Le **RTL Loan Sizer & Pricer** réunit sur un seul écran les limites de souscription, les règles de tarification au taux de refinancement, la validation de l'effet de levier, les déductions de règlement et les sorties de devis clients, pour que vous sachiez toujours si une opération tient avant d'engager du capital.

Vous cherchez d'autres modèles financiers Excel hors ligne, moteurs de tarification et outils d'aide à la décision opérationnelle prêts à l'emploi ?  
[Explorez le catalogue complet de modèles Excel business & finance hors ligne sur Theseus Workshop (theseusworkshop.com)](https://www.theseusworkshop.com)

## Détails techniques

<details>
<summary><strong>Pour les relecteurs techniques, les praticiens Excel et les collaborateurs</strong></summary>

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
| 01_ReadMe | Instructions, historique des versions, documentation administrateur | Oui |
| 02_Inputs | Informations sur l'emprunteur et conditions de prêt demandées | Oui |
| 03_Pricing_&_Assumptions | Grilles de taux de refinancement, règles d'effet de levier, hypothèses de tarification | Administrateurs uniquement |
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

Le classeur est volontairement compilé en deux formats de distribution.

| Version | Utilisateurs visés | Composants protégés |
|---------|----------------|----------------------|
| Version interne | Dirigeants, souscripteurs, opérations | Toutes les feuilles visibles avec mot de passe administrateur |
| Version originateur | Originateurs de prêts | Tableaux de tarification et moteur de calcul masqués via xlSheetVeryHidden |

Les mesures de protection supplémentaires comprennent :

- Protection de la structure du classeur
- Formules masquées
- Cellules de calcul verrouillées
- Grilles de tarification protégées
- Barre de formules masquée (version originateur)
- Structure de feuille protégée par mot de passe

Cette approche protège la tarification propriétaire du prêteur sans maintenir deux classeurs indépendants.

---

## Trois pièges qui attrapent même les originateurs de prêts expérimentés

---

## Piège 1 — Ne regarder que le LTV

De nombreux prêteurs se concentrent instinctivement sur le Loan-to-Value parce que c'est la métrique de souscription la plus familière.

Malheureusement, le prêt transitionnel repose rarement sur un seul ratio d'effet de levier.

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

L'originateur abaisse le taux nominal pour rester compétitif.

Tout semble acceptable.

Plus tard...

Le marketing secondaire découvre que le spread du prêteur est tombé sous les minimums internes.

Le devis doit être révisé.

### Décision incorrecte

Taux de l'emprunteur

```
10.00%
```

Taux de refinancement

```
8.20%
```

Spread

```
1.80%
```

Spread minimal requis

```
2.50%
```

La transaction est en réalité en dessous des exigences de rentabilité du prêteur.

### Approche correcte

Chaque devis doit valider la tarification avant présentation.

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

Cash-to-Close réel

```
$26,500
```

Si la liquidité de l'emprunteur équivaut seulement à

```
$18,000
```

le prêt ne peut pas être clôturé sans fonds supplémentaires.

### Approche correcte

Calculez le produit du règlement plutôt que de supposer que le montant brut du prêt équivaut au financement disponible.

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

Le classeur identifie les pénuries de liquidité avant la préparation des documents de clôture.

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
| Expérience | 6+ projets |
| Taux nominal | 11.25% |
| Durée du prêt | 12 mois |

Le moteur de tarification récupère le taux de refinancement correspondant en fonction de la tranche FICO de l'emprunteur et de l'effet de levier calculé.

Le moteur de calcul détermine ensuite :

- LTV réel
- LTC réel
- LTP réel
- LTARV réel
- Spread
- Financement net
- Cash-to-Close
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

Plutôt que de refuser immédiatement le prêt, le classeur le classe comme **Exception Needed**, permettant à la direction d'examiner les facteurs compensatoires tels que l'expérience de l'emprunteur, la liquidité ou des garanties supplémentaires.

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
| XLOOKUP | Récupérer le taux de refinancement |
| INDEX + MATCH | Recherche de tarification héritée |
| Spread | Taux nominal − Taux de refinancement |
| Spread Status | Validation de la marge |

La tarification utilise toujours un comportement de recherche exact avec une gestion d'erreur par défaut pour éviter des sorties de tarification invalides.

</details>

<details>

<summary>Calculs de règlement</summary>

| Calcul | Objet |
|-------------|----------|
| Intérêts intercalaires | Intérêts perçus à la clôture |
| Frais de service | Frais déduits sur la durée du prêt |
| Financement net | Fonds disponibles pour l'emprunteur |
| Cash-to-Close | Contribution supplémentaire de l'emprunteur |
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
| Rehab Budget | Zéro pour les prêts Bridge | Champ automatiquement grisé |
| ARV | Requis pour les produits de réhabilitation | Afficher N/A le cas échéant |
| Requested Loan | Devise positive | Rejeter les valeurs négatives |
| FICO | 300–850 | Rejeter le score invalide |
| Experience Tier | Menu déroulant uniquement | Empêcher les échecs de recherche |
| Loan Term | 12 / 18 / 24 mois | Rejeter les autres valeurs |
| Short Interest Days | 0–30 | Rejeter la saisie invalide |
| Buy Rate Lookup | XLOOKUP avec valeur de repli | "Check Risk Rules" |
| Division Operations | Enveloppe IFERROR | Renvoyer 0 au lieu des erreurs Excel |
| Text Lookups | TRIM + UPPER | Empêcher les écarts d'espaces et de casse |
| Margin Check | Comparaison avec le spread minimal | Renvoyer "Below Margin" |
| Eligibility | Évaluer tous les indicateurs de souscription | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Autres outils de cette série

Le **RTL Loan Sizer / Pricer** fait partie d'une collection croissante d'outils opérationnels légers d'aide à la décision, conçus pour les professionnels qui ont besoin d'analyses fiables sans mettre en œuvre de logiciel d'entreprise.

Chaque outil suit les mêmes principes :

- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — Pourquoi la trésorerie est-elle toujours serrée ? — Prévoyez la liquidité future sous des hypothèses opérationnelles et financières changeantes.
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — Quels flux commerciaux sont réellement rentables après effets de change ? — Mesurez la rentabilité des échanges multidevises à travers des opérations transfrontalières.
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — Où les liquidités personnelles et professionnelles sont-elles mélangées ou mal affectées ? — Séparez les flux de trésorerie personnels et professionnels en pistes budgétaires suivies indépendamment.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — Cette acquisition immobilière crée-t-elle encore de la valeur de fonds propres après rénovation et hypothèses d'exploitation ? — Évaluez les rendements d'acquisition d'immeubles multifamiliaux sous scénarios de financement de rénovation et d'exploitation.
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — Combien vaut un bien selon les différentes méthodes d'évaluation ? — Calculez la valeur d'un bien selon plusieurs méthodes d'évaluation avec modélisation de la fiscalité et des dépenses en capital.
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — Les coûts partagés sont-ils répartis équitablement entre entités, certains actifs étant surchargés pendant que d'autres échappent à leur véritable exposition aux coûts ? — Répartissez les factures fournisseurs entre plusieurs entités juridiques et actifs opérationnels selon des méthodologies d'allocation configurables.
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — Que doit réellement chaque participant compte tenu de son moment d'entrée et de la valeur actuelle du pool ? — Suivez en continu les parts d'un pool d'investissement via une comptabilité d'unités basée sur la NAV.
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — Quels engagements opérationnels créeront un problème de trésorerie dans les douze prochaines semaines ? — Reliez ventes Shopify, transactions bancaires, dépenses publicitaires et achats de stock dans un cadre unifié de décision de flux de trésorerie.
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — Assez d'informations significatives ont-elles changé pour justifier un ajustement tarifaire ? — Gouvernez les recommandations tarifaires via des garde-fous configurables qui préviennent la volatilité inutile des revenus.
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — Qu'est-ce qui a réellement changé dans l'activité cette période et quels produits ou mots-clés ont porté le changement ? — Transformez les exports SQP de Amazon Seller Central et Sellerboard en revues commerciales exécutives standardisées.
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — Quels produits sont réellement rentables après allocation de tous les coûts de fabrication et lesquels détruisent la marge ? — Allouez la main-d'œuvre d'usine, les services (utilities), les frais généraux et les coûts matières à chaque SKU pour une véritable économie unitaire de fabrication.
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — Quelles commandes sont réellement rentables après tous les coûts cachés et où l'argent fuit-il entre canaux et devises ? — Reconstituez la rentabilité réelle au niveau des commandes en rapprochant versements de ventes, frais d'expédition, frais de paiement et commissions de marketplaces sur des opérations e-commerce multicanal.
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — Quels projets d'entrepreneurs et quels clients sont réellement rentables après tous les coûts de chantier ? — Reliez l'estimation des prospects, l'exécution des chantiers et le suivi des coûts réels dans un cadre unifié de rentabilité des entrepreneurs.
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — La boutique est-elle réellement rentable après tous les coûts d'ingrédients, de main-d'œuvre et d'exploitation ? — Reliez le coût des recettes, les ventes, la consommation de stock et les charges d'exploitation dans un cadre unifié de rentabilité et de flux de trésorerie.
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — Quelles réservations de fret sont réellement rentables après tous les coûts, frais et conversions de devises ? — Mesurez la rentabilité du fret au niveau des réservations en rapprochant revenus, COGS, frais bancaires et coûts de conteneurs sur des transactions multidevises.
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — Quels conteneurs et quels clients sont réellement rentables à travers les opérations de douane et de flotte ? — Consolidez le dédouanement et l'exécution de flotte dans une vue unique de rentabilité au niveau du conteneur.
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — Que reste-t-il réellement dû aujourd'hui après des années de transferts et d'intérêts accumulés ? — Rapprochez les transferts de fonds à long terme et les intérêts accumulés en un solde restant dû actuel.
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — À quoi ressembleront nos états financiers sous différents scénarios opérationnels et de financement ? — Prévoyez des états financiers intégrés en reliant revenus, charges, besoin en fonds de roulement et dette dans un modèle unifié.
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — Quelle part de la marge déclarée de chaque bâtiment est réellement générée par ce bâtiment plutôt que par la manière dont les coûts du siège ont été alloués ? — Allouez les charges partagées entre unités opérationnelles tout en préservant les transactions sources et en rapprochant les résultats au niveau des unités des totaux de la société.
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — À quel prix d'acquisition maximal du foncier ce projet de développement devient-il un investissement finançable par une banque ? — Évaluez les opportunités de développement résidentiel en présélectionnant les comparables fonciers, en estimant les coûts de construction et en calculant les seuils de profit sur coût.
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — Ce projet de construction atteindra-t-il réellement sa marge cible une fois la logistique de chantier, les coefficients de déchets et les variations de taux des corps de métier pris en compte ? — Séparez les quantités physiques du bâtiment des taux volatils des corps de métier et des frais de chantier (site preliminaries) pour dérouler les marges commerciales à travers les budgets d'appels d'offres et les devis clients.
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — Quels prix de gros et segments de clientèle préservent réellement la marge une fois fret, droits de douane, conditions de paiement et changes entièrement coûtés ? — Calculez les coûts rendus (landed costs) au niveau SKU, le coût de service et les cascades de prix de marge poche pour simuler la rentabilité du commerce de gros transfrontalier.
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — Combien facturer une commande d'étiquettes personnalisées à chaque palier de quantité pour rester compétitif et rentable ? — Calculez une tarification paramétrique des étiquettes en modélisant les coûts au pouce carré des substrats, les frais de mise en route et les remises par palier de quantité par rapport aux références concurrentes.
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — Quelle est la véritable marge nette de chaque SKU une fois les coûts rendus réels et les déductions des distributeurs prises en compte ? — Rapprochez les coûts rendus estimés sur bon de commande des frais réels de fret, droits de douane, changes et transport local (drayage) tout en auditant les déductions de reversement des distributeurs pour révéler la marge nette au niveau SKU.
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — Pouvons-nous honorer les engagements de recrutement, de marketing et de fournisseurs de cette semaine sans manquer de trésorerie avant la clôture comptable ? — Suivez le rythme hebdomadaire de consommation de trésorerie, les écarts du waterfall MRR/ARR, les métriques de rétention et les coûts de paie par rapport au budget avant la clôture mensuelle.
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — Notre plan de croissance manquera-t-il de trésorerie avant que la monétisation des cohortes ne rattrape ? — Prévoyez la consommation de trésorerie pluriannuelle, la runway, l'économie unitaire et la dilution des levées de fonds à partir d'hypothèses bottom-up de cohortes et d'effectifs.
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — Chaque boutique Shopify est-elle réellement rentable une fois les coûts réels au niveau SKU, les charges partagées et les frais bancaires rapprochés ? — Rapprochez les exports de ventes Shopify multi-boutiques des COGS au niveau SKU, des OPEX multidevises alloués et des relevés bancaires pour produire un P&L mensuel fiable.
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — Quelles réservations de voyages génèrent réellement un bénéfice net et un flux de trésorerie positif après coûts fournisseurs et encaissements B2B ? — Calculez les coûts de dossier par réservation, les marges brutes, les règlements AR/AP et le flux de trésorerie opérationnel sur plusieurs devises.

| Outil | Objet |
|------|---------|
| Construction Estimating System | Standardiser l'estimation de projet, les assemblages, la tarification des offres et le suivi des coûts. |
| Inventory Forecasting & Reorder Planner | Prévoir la demande d'inventaire, identifier le moment de réapprovisionnement et surveiller le risque de rupture de stock. |
| Retail & Maquila Inventory Ledger | Suivre le mouvement des stocks au niveau de la pièce, la production, les défauts et la distribution. |
| Unified Personal & Business Budget Framework | Consolider les flux de trésorerie personnels et professionnels dans un seul modèle de planification financière. |
| Cross-Border VAT Compliance Dashboard | Surveiller les obligations de TVA dans plusieurs pays et canaux de vente. |
| Project Financial Control Dashboard | Comparer budget, engagements, factures, facturation d'avancement et rentabilité du projet. |
| Coffee Shop Operations Audit Toolkit | Évaluer la performance opérationnelle du café à l'aide d'une notation d'audit standardisée et d'une analyse KPI. |

---

## Avertissement

Ce classeur est destiné à servir d'outil analytique d'aide à la décision.

Il ne constitue **pas** :

- un conseil juridique,
- un conseil en prêt,
- une approbation de souscription,
- une orientation comptable,
- une certification de conformité réglementaire,
- une recommandation d'investissement.

Toutes les décisions de prêt restent soumises aux politiques de souscription de l'établissement prêteur, aux réglementations applicables, aux exigences des investisseurs et à l'approbation de crédit finale.

Les utilisateurs sont responsables de la vérification de toutes les hypothèses, paramètres de tarification, barèmes de frais et règles de souscription avant de se fier aux sorties générées.

---

## Remerciements

Ce projet reflète les pratiques de souscription courantes du prêt résidentiel transitionnel, notamment les prêts Bridge, le financement Fix-and-Flip, les prêts de réhabilitation et le prêt à la construction résidentielle.

Son architecture met l'accent sur la transparence, la répétabilité et la cohérence opérationnelle afin que les décisions de tarification puissent être reproduites, examinées et auditées plutôt que de dépendre du savoir tableur d'individus.

---

**Apache License 2.0 © 2026**

Construit dans le cadre d'une collection plus large d'outils opérationnels légers d'aide à la décision pour la finance, la construction, la gestion des stocks et les opérations commerciales.