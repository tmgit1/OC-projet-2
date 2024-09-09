# Projet 2 : Open Food Facts - Qualité Nutritionnelle des Produits

## Description du Projet
Ce projet utilise le dataset d'Open Food Facts, une base de données open source mise à disposition par l'agence Santé publique France, pour analyser la qualité nutritionnelle des produits alimentaires. L'objectif principal est de nettoyer les données, d'effectuer des analyses statistiques et de visualiser les résultats de manière pertinente.

## Objectifs du Projet
1. Nettoyage des Données (Data Cleaning)
Le dataset initial contient des doublons, des valeurs manquantes et des valeurs aberrantes. Pour améliorer la qualité des données, différentes techniques de nettoyage ont été appliquées :
- Traitement des doublons : suppression des entrées redondantes.
- Gestion des valeurs manquantes : remplissage ou suppression selon les colonnes concernées et le taux de valeurs manquantes.
- Traitement des valeurs aberrantes : utilisation de techniques statistiques pour identifier et gérer les outliers.

2. Analyse Statistique
Différentes analyses statistiques ont été réalisées pour explorer les données.

- Analyse Univariée
Exploration des distributions de variables individuelles à l'aide de mesures statistiques et de visualisations comme les histogrammes et les boxplots.
- Analyse Bivariée
ANOVA (Analyse de la Variance) : comparaison des moyennes de plusieurs groupes pour voir si elles sont statistiquement différentes.
Corrélations : utilisation d'une matrice de corrélation pour visualiser les relations entre les variables continues.
- Analyse Multivariée
Analyse en Composantes Principales (ACP) : réduction de la dimensionnalité pour mieux comprendre la structure globale des données et identifier les principaux axes de variation.

3. Visualisations
Des visualisations graphiques ont été utilisées pour mieux comprendre les données et communiquer les résultats des analyses.

- Histogrammes : pour visualiser la distribution des différentes variables.
- Boxplots : pour comparer les distributions entre groupes.
- Scatterplots : pour analyser les relations entre deux variables.
- Matrice de Corrélation : pour visualiser les corrélations entre variables.

## Outils Utilisés

- Python : Langage principal utilisé pour le projet.
- Pandas & NumPy : Manipulation des données.
- Matplotlib & Seaborn : Visualisation des données.
- Scikit-learn : Réalisation de l'ACP et d'autres analyses statistiques.
- Statsmodels : Pour effectuer l'ANOVA.

## Conclusion
Ce projet a permis de nettoyer et d'explorer en profondeur les données du dataset Open Food Facts, en identifiant des tendances nutritionnelles et des relations pertinentes entre les variables. Les analyses univariées, bivariées et multivariées, ainsi que les visualisations, offrent une vue d'ensemble claire de la qualité nutritionnelle des produits étudiés.
