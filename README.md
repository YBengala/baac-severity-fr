_Read this in other languages: [Français](README_FR.md)_

# Analysis and Severity Prediction of Road Accidents in France

![Status](https://img.shields.io/badge/Status-Work%20in%20Progress-yellow)

This project aims to analyze the French road traffic accident dataset (BAAC) to identify key risk factors and build a Machine Learning model to predict accident severity.

## 🎯 Project Goal

The final objective is to develop a tool capable of:
1.  **Identifying** the most influential features (weather, light conditions, driver profile, etc.) on accident severity.
2.  **Predicting** the probability of an accident being severe (resulting in death or serious injury) based on its characteristics.
3.  **Presenting** these findings interactively through a simple web application.

## 💾 Data [![Licence](https://img.shields.io/badge/Licence-Licence%20Ouverte%20v2.0-lightgrey)](DATA_LICENSE.md)

The data used comes from the public dataset **"Bases de données annuelles des accidents corporels de la circulation routière"** (Annual databases of personal injury accidents) available on data.gouv.fr.

* **Source:** [Link to the dataset](https://www.data.gouv.fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2023/)
* **Scope:** Annual data from 2018 to 2023.


The dataset is split into four main files for each year :
* `caracteristiques.csv`: General characteristics of the accident (date, time, weather conditions, light).
* `lieux.csv`: Information about the accident location (road category, surface condition, infrastructure).
* `usagers.csv`: Information about the users involved (age, gender, injury severity, safety equipment).
* `vehicules.csv`: Information about the vehicles involved (category, direction of impact).