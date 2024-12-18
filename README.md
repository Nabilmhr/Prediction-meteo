# Prediction-meteo

Projet : Prédiction des Températures à partir d'une Série Chronologique

Ce projet consiste à analyser et modéliser une série chronologique des relevés quotidiens de température de la ville de Marignane sur une période de 13 ans. L'objectif est d'observer les tendances et la saisonnalité, afin de prédire les comportements futurs de cette série.

Objectifs

Analyse descriptive : Explorer la distribution et les caractéristiques principales des données de température.

Analyse des tendances et saisonnalité : Identifier les composantes de la série chronologique.

Prévision : Construire un modèle pour prédire les températures futures à l'aide des données historiques.

Données

Le projet utilise un fichier CSV intitulé temperature.csv, contenant les colonnes suivantes :

Date : Date des relevés (au format YYYY-MM-DD).

Température : Valeur de la température quotidienne en degrés Celsius.

Méthodologie

1. Analyse descriptive

Visualisation :

Création de graphiques temporels pour observer les évolutions des températures.

Histogrammes pour analyser la distribution des températures.

Statistiques :

Moyenne, médiane, écart-type.

2. Analyse des tendances et saisonnalité

Décomposition de la série chronologique :

Tendance (trend).

Saisonnalité (seasonality).

Bruit (noise).

3. Modélisation et prédiction

Modèles utilisés :

Modèles ARIMA (Auto-Regressive Integrated Moving Average).

Modèles de lissage exponentiel (ETS).

Autres modèles disponibles dans la bibliothèque forecast.

Outils et Bibliothèques

Le projet est réalisé avec les bibliothèques R suivantes :

tidyverse : Manipulation et visualisation des données.

ggplot2 : Visualisation avancée des données.

forecast : Analyse et prédiction des séries chronologiques.

reshape2 : Restructuration des données pour l'analyse.

Installation des packages nécessaires :

install.packages(c("tidyverse", "ggplot2", "forecast", "reshape2"))

Structure du Projet

Importation des données : Chargement et préparation des relevés de température.

Analyse descriptive : Exploration statistique et visuelle des données.

Décomposition de la série chronologique : Identification des composantes principales.

Prévision : Construction et évaluation des modèles de prévision.

