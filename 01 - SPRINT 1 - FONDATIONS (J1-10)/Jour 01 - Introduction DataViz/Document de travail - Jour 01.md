# Jour 01 : Introduction à la Data Visualization

**Sprint :** 1 — Fondations | **Niveau :** Guidé | **Outil :** Théorie / Recherche

---

## Objectifs du Jour

À la fin de ce jour, vous serez capable de :
- Comprendre ce qu'est la data visualization et son importance
- Connaître les principes fondamentaux de la dataviz
- Distinguer une bonne dataviz d'une mauvaise dataviz
- Créer votre repository GitHub pour le bootcamp
- Préparer votre environnement de travail

---

## Théorie

### 1. Qu'est-ce que la Data Visualization ?

**Définition personnelle :**
La data visualization est l'art de représenter des données sous forme visuelle (graphiques, cartes, dashboards) pour faciliter la compréhension, l'analyse et la prise de décision.

**Pourquoi est-elle importante en entreprise ?**
- Permet de comprendre rapidement des milliers de lignes de données
- Facilite la communication des résultats
- Aide à la prise de décision
- Détecte les tendances et anomalies

**Bénéfices d'une bonne visualisation :**
- Compréhension immédiate
- Gain de temps
- Prise de décision éclairée
- Mémorisation facilitée
- Communication efficace

---

### 2. Les 5 principes d'Edward Tufte

| # | Principe | Description | Exemple concret |
|---|----------|-------------|-----------------|
| 1 | **Ratio données/encre** | Maximiser l'information, minimiser l'encre | Éviter les grilles inutiles, les 3D |
| 2 | **Pas de chartjunk** | Éviter les décorations inutiles | Pas d'images, d'ombres, d'effets |
| 3 | **Petits multiples** | Comparer plusieurs graphiques côte à côte | Petits graphiques répétés sur une grille |
| 4 | **Intégrité graphique** | Ne pas tromper le lecteur | Axe Y commence à 0, échelles honnêtes |
| 5 | **Hiérarchie visuelle** | Guider l'œil vers l'essentiel | Couleurs, tailles, positionnement |

**Qui est Edward Tufte ?**
Professeur et statisticien américain, considéré comme le "père" de la data visualization moderne.

**Le principe le plus important selon moi :**
Le **ratio données/encre** — parce qu'il force à se demander : "Est-ce que cet élément apporte de l'information ?"

---

### 3. Bonnes vs Mauvaises pratiques

**5 bonnes pratiques :**
1. Choisir le bon type de graphique (barres pour comparer, courbe pour évoluer)
2. Axe Y commence à 0
3. Titres clairs et explicites
4. Couleurs cohérentes et limitées
5. Étiquettes lisibles

**5 mauvaises pratiques :**
1. Graphiques 3D
2. Pie charts avec trop de catégories
3. Axe Y tronqué
4. Trop de couleurs
5. Chartjunk (décorations inutiles)

**Pourquoi les graphiques 3D sont déconseillés ?**
Ils déforment la perception des valeurs et rendent la comparaison difficile.

**Qu'est-ce que le ratio données/encre ?**
Le rapport entre l'information utile et l'encre utilisée. Plus il est élevé, plus le graphique est efficace.

---

## Recherche

### 3 bonnes dataviz

| # | Exemple | Pourquoi est-ce bon ? |
|---|---------|----------------------|
| 1 | Courbe de température (Météo France) | Lisible, axe Y à 0, couleurs claires |
| 2 | Carte COVID (Johns Hopkins) | Intuitive, hiérarchie visuelle claire |
| 3 | Dashboard Tableau Public (ventes) | KPI + filtres, navigation fluide |

### 3 mauvaises dataviz

| # | Exemple | Pourquoi est-ce mauvais ? | Comment l'améliorer ? |
|---|---------|---------------------------|----------------------|
| 1 | Pie chart 3D avec 10 catégories | Illisible, déformé | Remplacer par un histogramme |
| 2 | Axe Y tronqué | Trompeur | Commencer à 0 |
| 3 | Trop de couleurs | Confus | Limiter à 3-4 couleurs |

---

## Questions de réflexion

**Critères pour juger une dataviz :**
- Clarté du message
- Honnêteté des données
- Efficacité visuelle
- Facilité de lecture

**Pièges courants :**
- 3D
- Axe tronqué
- Surcharge visuelle
- Mauvais type de graphique

**3 types de graphiques et leur usage :**

| Type | Usage |
|------|-------|
| Histogramme | Comparer des catégories |
| Courbe | Évolution dans le temps |
| Nuage de points | Relation entre 2 variables |

---

## Repository GitHub

- [x] Repository créé : `bootcamp-bi-30jours` → `BootcampPowerBi`
- [x] Cloné en local
- [x] Structure des 30 jours créée
- [x] Premier commit effectué

---

## Installation & Préparation

### Power BI Desktop
- [x] Installé
- [x] Compte Microsoft créé

### Tableau Public
- [x] Installé
- [x] Inscription faite

---

## Notes sur les premières impressions

**Power BI :**
- Interface ruban, proche d'Excel
- 3 vues : Rapport, Données, Modèle
- Très orienté modélisation

**Tableau :**
- Interface par glisser-déposer
- Plus visuel
- Orienté exploration

---

## Livrables

- [x] Définition personnelle de la data visualization
- [x] Tableau des 5 principes de Tufte complété
- [x] Réponses aux questions bonnes/mauvaises pratiques
- [x] Tableau des 3 bonnes dataviz
- [x] Tableau des 3 mauvaises dataviz
- [x] Réponses aux questions de réflexion
- [x] Repository GitHub créé et structuré
- [x] Premier commit effectué
- [x] Capture Power BI Desktop installé
- [x] Capture Tableau Public installé
- [x] Notes sur les premières impressions

---

## Pour Demain

- Power BI Desktop installé et fonctionnel
- Repository GitHub prêt
- Télécharger `ventes_sample.csv` (disponible dans `Data/` du Jour 02)