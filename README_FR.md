_Read this in other languages: [English](README.md)_

# Analyse et Prédiction de la Gravité des Accidents Routiers en France

![Status](https://img.shields.io/badge/Status-En%20Cours-yellow)

Ce projet a pour objectif d'analyser les données des accidents corporels en France (BAAC) afin d'identifier les facteurs de risque et de construire un modèle de Machine Learning pour prédire la gravité d'un accident.

## 🎯 Objectif du Projet

L'objectif final est de développer un outil capable de :
1.  **Identifier** les caractéristiques les plus influentes (météo, luminosité, profil du conducteur, etc.) sur la gravité d'un accident.
2.  **Prédire** la probabilité qu'un accident soit grave (mortel ou blessé hospitalisé) en fonction de ses caractéristiques.
3.  **Présenter** ces résultats de manière interactive via une application web simple.

## 💾 Données [![Licence](https://img.shields.io/badge/Licence-Licence%20Ouverte%20v2.0-lightgrey)](DATA_LICENSE.md)

Les données utilisées proviennent du jeu de données public **"Bases de données annuelles des accidents corporels de la circulation routière"** disponible sur data.gouv.fr.

* **Source :** [Lien vers le dataset](https://www.data.gouv.fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2023/)
* **Périmètre :** Données annuelles de 2018 à 2023.

Le jeu de données est divisé en quatre fichiers principaux pour chaque année :
* `caracteristiques.csv` : Caractéristiques générales de l'accident (date, heure, conditions atmosphériques, luminosité).
* `lieux.csv` : Informations sur le lieu de l'accident (catégorie de route, état de la surface, infrastructure).
* `usagers.csv` : Informations sur les usagers impliqués (âge, sexe, gravité de la blessure, équipement de sécurité).
* `vehicules.csv` : Informations sur les véhicules impliqués (catégorie, point de choc).