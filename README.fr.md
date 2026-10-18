[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Modèle Excel de coûts de fabrication alimentaire et d'économie par unité

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)

> **Modèle Excel de coûts de fabrication alimentaire et d'économie par unité** : calcule le vrai COGS (coût des marchandises vendues), répartis les frais généraux d'usine, analyse les pertes de rendement par lot et détermine la rentabilité précise par SKU sans logiciel ERP complexe. Une solution Excel prête à l'emploi pour les entreprises agroalimentaires (F&B) et CPG.

**Aucune inscription. Aucune installation. Gratuit dans ton navigateur.**

Essaie la version navigateur pour des estimations COGS rapides. Si tu as besoin de sauvegarder tes données d'usine en sécurité pour le reporting mensuel, tu peux télécharger le classeur Excel complet avec une garantie de remboursement de 30 jours sans questions.

> 🌐 **Tester la calculatrice** → [Essaie la démo web gratuite sur les coûts de fabrication alimentaire](https://hyvoid.github.io/food-manufacturing-cost-calculator-excel/)
>
> 📥 **Télécharger le classeur** → [Télécharge le modèle Excel complet d'économie par unité (garantie 30 jours)](https://www.theseusworkshop.com/l/wtcwzb?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=food-manufacturing-unit-economics)

Utilise le format qui correspond le mieux à ton workflow de production. La version navigateur est idéale pour une vérification de marge en une seule session, tandis que la version Excel fournit un modèle financier entièrement transparent, fondé sur des formules, adapté à la planification et analyse financières (FP&A) continues et aux opérations quotidiennes.

---

## Ce que cet outil de calcul des coûts de production alimentaire résout (points de douleur vs. solutions)

- **Point de douleur :** estimer les marges produit en se basant uniquement sur les ingrédients de la recette.
  **Solution :** calcule le **vrai coût de fabrication par SKU** en intégrant les estimations standard de la nomenclature (BOM) aux réalités du sol de production.
- **Point de douleur :** érosion de marge inexpliquée en fin de période financière.
  **Solution :** cartographie exactement comment **l'utilisation de la main-d'œuvre directe, les services publics de l'usine, l'amortissement des équipements et les frais généraux de fabrication (MOH)** affectent ton résultat net.
- **Point de douleur :** fixer les prix de gros ou de détail à l'aveugle.
  **Solution :** révèle quels produits CPG atteignent réellement ta **marge brute cible** une fois tous les coûts de fabrication indirects correctement absorbés.
- **Point de douleur :** seuils de rentabilité imprévisibles lors de la montée en production.
  **Solution :** modélise comment les fluctuations de volume de production influencent **l'économie par unité et l'analyse du seuil de rentabilité**.
- **Point de douleur :** incapacité à identifier la cause première des pics de coûts.
  **Solution :** isole les écarts pour que tu saches immédiatement si les hausses de coûts proviennent de **l'inflation des matières premières, des déchets d'emballage/pertes de rendement, des heures supplémentaires ou des temps d'arrêt de l'usine**.

---

## Tutoriel de démarrage rapide : comment calculer les coûts de fabrication

### Étape 1 : configure les hypothèses opérationnelles de l'usine (paramètres)
Commence par saisir les paramètres globaux qui définissent ton installation de production. Configure tes tarifs d'électricité, tes coûts d'eau, tes calendriers d'amortissement des équipements, tes seuils de marge brute cible et ta méthodologie préférée de répartition des frais généraux. Ceux-ci sont stockés sur la feuille **Assumptions** pour une planification de scénarios facile.

### Étape 2 : importe les données de production et les recettes BOM (entrées)
Colle tes enregistrements réels de lots de production, tes données de référence SKU, tes recettes d'ingrédients BOM, tes prix d'approvisionnement en matériaux, tes coûts d'emballage, tes résumés de paie et tes dépenses d'exploitation mensuelles (OpEx). Tu peux coller directement des exports de données existants depuis QuickBooks, Xero ou ton système de gestion d'entrepôt dans ce modèle de calcul des coûts.

### Étape 3 : exécute le moteur d'allocation des coûts (analyse)
Navigue vers le Executive Dashboard, la Unit Cost Analysis ou la Margin Spending Map. Les tableaux dynamiques intégrés répartissent automatiquement les ressources d'usine mutualisées vers les SKU individuels, donnant aux équipes opérationnelles une visibilité immédiate sur les vrais COGS et la rentabilité au niveau SKU.

### Étape 4 : actualise les données financières mensuelles (maintenance)
À la clôture d'une nouvelle période comptable, remplace les anciennes données opérationnelles par les chiffres de production du dernier mois. Le tableau de bord se met à jour automatiquement, fournissant une vue glissante de la santé financière de ton usine.

### Étape 5 : passe de l'essai gratuit au workflow Excel permanent (action)
> **Prêt à standardiser ton reporting mensuel ?** Après avoir testé tes chiffres dans l'outil navigateur à session unique, [télécharge la version classeur Excel](https://www.theseusworkshop.com/l/wtcwzb?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=food-manufacturing-cost-calculator) pour sauvegarder en sécurité tes données d'usine historiques, personnaliser les formules d'allocation et intégrer définitivement cette trousse dans le processus de clôture financière mensuelle de ton entreprise.

---

## Pourquoi j'ai construit ce tracker de rentabilité CPG

De nombreux petits et moyens fabricants agroalimentaires (boulangeries, brasseries, marques de snacks) suivent parfaitement leurs dépenses mensuelles agrégées mais peinent encore à répondre à une question commerciale fondamentale :

> **Combien coûte réellement à notre usine la production d'exactement une unité de ce produit spécifique ?**

Les coûts des matières premières sont faciles à suivre car des nomenclatures (BOM) standard existent. L'angle mort financier se produit sur le sol de production.

Les salaires d'usine, l'amortissement des équipements, les services publics industriels, la maintenance, les pertes de rendement à l'emballage et les frais généraux de fabrication mutualisés restent regroupés sous forme de totaux comptables mensuels. Les produits apparaissent artificiellement rentables simplement parce que ces frais généraux mutualisés n'ont jamais été absorbés de manière cohérente.

**Le danger des coûts mal répartis :**
Avant d'utiliser ce cadre d'économie par unité, la direction pourrait regarder une boisson premium et supposer une marge brute de 48 % sur la seule base des coûts d'ingrédients de gros. Après répartition systématique de la main-d'œuvre réelle de la ligne de production, de l'amortissement des machines, des services publics de l'usine et des déchets d'emballage, la vraie marge brute tombe à 18 % — bien en dessous du seuil de rentabilité de l'entreprise.

Ce modèle expose immédiatement ces drains opérationnels cachés.

## Défis courants de fabrication F&B résolus

| Défi de l'industrie F&B | Limites des tableurs traditionnels | Avec cette trousse Excel d'économie par unité |
|------------------------|-------------------------------------|----------------------------------------|
| **Déconnexion entre BOM et COGS réel** | Les modèles de tarification ne regardent que les coûts des ingrédients de la recette, en ignorant la main-d'œuvre, les services publics et les frais généraux. | Les coûts matériels standard fusionnent automatiquement avec les dépenses d'exploitation d'usine réparties pour donner un vrai coût de fabrication unitaire entièrement chargé. |
| **Frais généraux d'usine non répartis** | La finance suit les dépenses mensuelles totales (OpEx), mais les opérations ne peuvent pas expliquer quels SKU consomment ces ressources. | La main-d'œuvre directe, les frais généraux de fabrication (MOH) et les services publics sont systématiquement répartis sur chaque SKU via des inducteurs d'absorption des coûts configurables. |
| **Mystère de l'érosion de marge** | Les managers subissent des marges brutes en réduction mais ne peuvent pas isoler si cela est dû à l'inflation des matériaux, aux déchets d'emballage ou à l'inefficacité de la main-d'œuvre. | Les composantes de coût (matériau, emballage, main-d'œuvre, frais généraux) sont isolées, rendant le principal inducteur de coût immédiatement visible pour les opérations. |
| **Risques de subventionnement croisé** | Les produits de base à haut volume subventionnent silencieusement les SKU complexes à faible volume, conduisant à une planification de production défectueuse. | Les dépenses de fabrication mutualisées sont distribuées équitablement sur la base de la consommation réelle des ressources, corrigeant les distorsions de prix. |
| **Reporting de fin de mois manuel** | Les équipes FP&A gaspillent des jours à consolider manuellement les journaux de production, la paie et les données d'achat dans une feuille maîtresse. | Le tableau de bord exécutif se met à jour automatiquement grâce aux tableaux dynamiques dès que de nouvelles données opérationnelles sont collées, rationalisant la clôture mensuelle. |

---

## À qui cela s'adresse : rôles et cas d'usage

Cette trousse est conçue pour les organisations F&B qui exigent une visibilité précise sur les coûts de fabrication sans subir une implémentation ERP à six chiffres.

Elle est activement utilisée par :
- **Responsables financiers Food & Beverage** ayant besoin d'un *modèle Excel de répartition des coûts de fabrication* pour clôturer précisément les livres mensuels.
- **Responsables des opérations et d'usine** recherchant un *tracker d'efficacité de production* pour mesurer l'utilisation de l'usine et justifier le ROI des équipements.
- **Fondateurs de startups CPG** cherchant un *tableur F&B d'économie par unité* pour valider les marges avant de pitcher des acheteurs de détail ou des investisseurs.
- **Comptables analytiques** ayant besoin d'une *calculatrice de rentabilité par SKU* pour fixer des bases de prix standardisées.
- **Consultants en fabrication** déployant un *tableau de bord de transformation digitale* léger pour des clients manufacturiers traditionnels.

*(Remarque : ce classeur fournit une couche analytique transparente reliant les opérations et la finance. Il ne remplace pas un système MES ni un logiciel comptable fondamental.)*

---

## Cas d'usage idéaux et scénarios dans l'industrie F&B

Cette trousse s'adapte à divers environnements de production alimentaire où le traitement par lots et les ressources mutualisées compliquent le calcul des coûts standard :
- **Brasseries artisanales et embouteillage de boissons :** calcule combien coûtent réellement la perte de liquide, le temps d'embouteillage et l'amortissement des cuves par canette.
- **Boulangeries et confiseries commerciales :** suis comment les coûts des fours et des services publics et la main-d'œuvre directe des boulangers affectent la marge des SKU de pâtisserie à haut mélange et faible volume.
- **Snacks et aliments emballés (CPG) :** détermine si l'emballage premium de ta nouvelle gamme de produits détruit la marge brute de référence par rapport aux articles historiques.
- **Co-packing et fabrication sous contrat :** justifie les quantités minimales de commande (MOQ) et les paliers de prix auprès des clients en montrant exactement comment les petites séries font grimper les coûts de main-d'œuvre et de réglage machine par unité.

---

## Détails techniques

<details>
<summary>Pour les réviseurs techniques, les praticiens FP&A et les développeurs Excel</summary>

## Architecture du classeur

Le classeur utilise une architecture modulaire et en couches pour séparer proprement la saisie des données brutes, la logique de calcul des formules et le reporting exécutif. Cela garantit une haute auditabilité.

```text
Input Layer (Raw Data)
│
├── Assumptions (Global Parameters)
├── SKU Master
├── Material Costs (Procurement)
├── Packaging Costs
├── Production Inputs (Batch Logs)
│
▼
Calculation Layer (Cost Engine)
│
├── BOM Recipe Consolidation
├── Direct Labor Allocation
├── Manufacturing Overhead Absorption
├── Utilities Costs Distribution
├── Cost Allocation Engine
│
▼
Decision Layer (Outputs)
│
├── COGS Unit Cost
├── Margin & Break-even Analysis
├── Spending Map
└── Executive Dashboard (KPIs)

```

### Flux de données

```
Master Data → Production Records → Material Lookup → Cost Pools → Dynamic Allocation Engine → True SKU Cost → Executive Dashboard

```

Ce flux unidirectionnel empêche les références circulaires et rend l'audit des formules simple pour les comptables externes.

## Fonctions Excel modernes utilisées

Conçu exclusivement pour Microsoft 365, la trousse exploite les tableaux dynamiques pour éliminer le besoin de macros VBA ou de glisser les formules vers le bas :

* `XLOOKUP`, `FILTER`, `UNIQUE`, `LET`, `LAMBDA`, `MAP`, `HSTACK`, `SUMIFS`

Lorsque tu colles des milliers de nouveaux enregistrements de production ou ajoutes de nouveaux SKU, les plages d'analyse s'étendent automatiquement — un véritable modèle sans maintenance.

</details>

---

## La logique métier et la méthodologie

### Le problème métier : le piège du « subventionnement croisé des coûts »
Dans les entreprises agroalimentaires et CPG traditionnelles, l'analyse du coût des marchandises vendues (COGS) commence et s'arrête souvent à la nomenclature (BOM) standard. Les dépenses d'usine indirectes — comme le loyer des installations, les services publics industriels, l'amortissement des équipements et la main-d'œuvre de production mutualisée — restent sous forme d'un immense pool non réparti de dépenses d'exploitation mensuelles (OpEx).

Cela crée un angle mort dangereux connu sous le nom de **subventionnement croisé des coûts** : les produits à haut volume, faciles à produire, absorbent silencieusement les frais généraux générés par les SKU complexes à faible volume. Le résultat est une stratégie de tarification déformée où la direction sous-évalue accidentellement les produits gourmands en ressources tout en surévaluant les plus efficaces, détruisant finalement la vraie marge bénéficiaire du portefeuille.

### La méthodologie : la méthode des coûts par activité (ABC) en pratique
Cette trousse met en œuvre les principes fondamentaux de la **méthode des coûts par activité (ABC)** et de la **méthode des coûts complets** sans le fardeau administratif d'un système ERP d'entreprise.

Au lieu de diviser les frais généraux mensuels totaux également sur toutes les unités produites (la méthode traditionnelle du beurre de cacahuète qui pénalise les produits simples), ce modèle financier comble le fossé entre les données comptables agrégées et les réalités opérationnelles grâce à des **inducteurs de coûts** configurables.

### Comment fonctionne le moteur d'allocation
1. **Regroupement des coûts :** le modèle agrège tes dépenses d'exploitation mensuelles, la paie de production et les coûts de maintenance des installations en pools de coûts financiers distincts (par ex. main-d'œuvre directe, frais généraux de fabrication, services publics).
2. **Identification des inducteurs :** il utilise tes journaux réels de lots de production pour mesurer combien de capacité d'usine chaque produit consomme. La direction peut configurer la base d'allocation — comme les heures de main-d'œuvre directe, le temps machine, le poids du lot ou le volume unitaire — selon ce qui pilote réellement les dépenses dans ton installation spécifique.
3. **Allocation dynamique des coûts :** le moteur de calcul distribue systématiquement les dépenses financières mutualisées jusqu'au niveau du SKU individuel, strictement sur la base de leur consommation opérationnelle réelle des ressources.

### Le résultat métier
En reliant directement les dépenses financières aux activités de production opérationnelles, la trousse fournit une **économie par unité** précise et entièrement chargée. Cela permet au leadership manufacturier de passer des revues comptables mensuelles réactives à une prise de décision commerciale proactive :
* **Rationalisation des SKU :** identifier et éliminer (ou réévaluer) en toute confiance les produits « vampires » qui consomment la capacité d'usine sans contribuer de marge adéquate.
* **Stratégie de tarification fondée sur les données :** fixer les prix de gros et de vente directe aux consommateurs (DTC) sur la base de coûts de fabrication entièrement absorbés, garantissant la protection de ta marge brute cible.
* **Sensibilité des marges et planification des capacités :** comprendre exactement comment les fluctuations de taille des lots de production ou d'utilisation de l'usine affectent ta charge de frais généraux par unité et ton seuil de rentabilité global.

---

## Licence

Ce projet est sous licence **Apache License 2.0**.
Voir le fichier **LICENSE** pour le texte de licence complet.

## Avertissement

Ce classeur est un cadre d'aide à la décision. Les politiques comptables de fabrication, les méthodes de valorisation des stocks (FIFO/LIFO) et les calendriers d'amortissement fiscal varient dans le monde entier. Consulte toujours un expert-comptable certifié avant d'appliquer ces résultats à des déclarations fiscales officielles ou à des états financiers audités.
