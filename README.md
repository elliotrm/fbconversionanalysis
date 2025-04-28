# Dashboard - Facebook Conversions Analysis

# Projet

Ce projet a pour objectif d'analyser les données de conversion publicitaire Facebook à l'aide d'un **dashboard interactif** et de **modèles de machine learning**.

Il a été effectué en anglais puisque c'était un projet dédié pour la matière d'anglais de cette première année de Master MAS.

Nous proposons une exploration :
- Des performances publicitaires par genre, âge et campagne,
- De la distribution des clics et conversions,
- De la corrélation entre dépenses et résultats,
- De la prédiction du nombre de conversions par **Random Forest**.

# Auteurs

- Elliot **Rault-Maisonneuve**
- Eva **Le Callonec**
- Maëlys **Le Craver**
- Date : **Mars 2025**

# Données utilisées

- Source : Dataset public sur les campagnes Facebook (`KAG_conversion_data.csv`),
- Variables : Impressions, Clics, Dépenses publicitaires, Conversions totales et approuvées, Genre, Âge, Centre d'intérêt, ID de campagne.

# Technologies

- **R** : visualisations interactives avec `plotly`, analyse statistique avec `ggplot2`, `dplyr`, `caret`, `randomForest`.
- **R Markdown Dashboard** : mise en forme visuelle responsive,
- **Modèle Machine Learning** : Random Forest avec optimisation des hyperparamètres (`caret`).

# Fonctionnalités principales

- **KPI Cards** : aperçu rapide du dataset (taille, variables clés).
- **Analyses descriptives** : genre, âge, campagnes.
- **Corrélations** : matrices et régressions.
- **Modélisation prédictive** : prévision des conversions, analyse d'importance des variables.
- **Dashboard interactif** : navigation simplifiée par onglets.

# Structure du dépôt

- `data/` : Données sources (`KAG_conversion_data.csv`)
- `www/` : Images utilisées dans le dashboard (`mark.jpg`)
- `dashboard_facebook_analysis.Rmd` : Code principal du dashboard
- `README.Rmd` : Ce fichier de documentation

# Installation et Exécution

1. Cloner ce dépôt : git clone https://github.com/elliotrm/fbconversionanalysis.git
2. Installer les packages R nécessaires (dplyr, ggplot2, randomForest, caret, plotly, DT, kableExtra, ggcorrplot, etc.).
3. Lancer dashboard_facebook_analysis.Rmd pour visualiser le dashboard.
