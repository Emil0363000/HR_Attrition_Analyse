# HR_Attrition_Analyse

## Objectifs 
L'objectif est d'analyser les facteurs d'attrition au sein d'une entreprise de 1 470 employés et identifier les profils à risque à l’aide d’un pipeline BI complet.

## Stack technique 
  - Dataset brut depuis Kaggle (https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction)
  - ETL (Knime): Nettoyage et normalisation des données
  - Power Query: Transformation
  - PowerBI: Création de mesures DAX (Taux d'attrition, Satisfaction Jitter) et visualisation

## Pipeline du projet 
Raw Data -> ETL (KNIME) -> Clean Dataset -> PowerBI -> Dashboard

## Dashboards
  - Page 1: KPI (taux d'attrition, salaire moyen, age moyen, ancienneté moyenne, distance moyenne du lieu de travail)
  - Page 2: Analyse de l'attrition par rôle, département et tranche d'âge
  - Page 3: Analyse de l'attrition en fonction du departement et du rôle
  - Page 4: Analyse de l'attrition en fonction du salaire et de la satisfaction au travail
  - Page 5: Identification des employées à risque 
  - Page 6: Satisfaction moyenne en fonction des départements
  - Page 7: Analyse de l'attrition en fonction de différents facteurs

## Insight
  - Il y a une forte corréaltion entre heures supplémentaires et départ 
  - Les jeunes (18-25) ainsi que ceux ayant un salaire mensuel faible présentent un turnover plus élevé
  - Peu importe la satisfaction, le salaire joue un rôle prépondérant les départs des employés

## Limites 
  - Dataset statique

## Améliorations possibles
  - Modèle prédictif 
  - Intégration de données RH supplémentaires 
