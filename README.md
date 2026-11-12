# Microsoft Fabric - Taxi Demand Prediction Pipeline

Ce projet vise à construire un pipeline de données pour prédire la demande de taxis à New York en utilisant Microsoft Fabric.

## Étapes actuellement présentes dans le projet

Le projet contient, pour le moment, les étapes suivantes dans le dossier `Data preparation` :

1. Ingestion Bronze des données NYC Taxi 2025
   - Notebook : `01_ingestion_bronze_nyc_taxi_2025.ipynb`
2. Ingestion Bronze des données météo des 5 zones de Manhattan 2025
   - Notebook : `02_ingestion_bronze_weather_5_zones_taxi_manhattan_2025.ipynb`
3. Traitement des données en couche Silver
   - Notebook : `03_silver_data_processing.ipynb`
4. Ingénierie des features en couche Gold
   - Notebook : `04_gold_feature_engineering.ipynb`

Ces étapes représentent la base du pipeline actuel : ingestion, nettoyage/standardisation, puis préparation des données pour la modélisation et l'analyse prédictive.
