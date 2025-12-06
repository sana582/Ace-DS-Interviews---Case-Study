# Ace-DS-Interviews---Case-Study# 📊 Réussir les entretiens en Data Science – Étude de cas

## 📝 Description du projet

Ce projet a pour objectif d'analyser une base de données contenant des
informations sur des candidats : caractéristiques personnelles, parcours
académique, expérience professionnelle, salaire demandé, disponibilité
et statut d'embauche.

L'objectif final est de comprendre : 1. **Quels facteurs influencent
l'embauche.**\
2. **Quel est le profil général des candidats.**

------------------------------------------------------------------------

## 📂 Contenu de la base de données

La dataset contient les colonnes suivantes :

  Colonne        Description
  -------------- --------------------------------------------------------------------------
  `date`         Date d'enregistrement du candidat
  `cheveux`      Couleur des cheveux
  `age`          Âge du candidat
  `exp`          Années d'expérience
  `salaire`      Salaire souhaité
  `sexe`         Sexe (M/F)
  `diplome`      Niveau d'étude
  `specialite`   Spécialité (géologie, forage, etc.)
  `note`         Évaluation du candidat
  `dispo`        Disponibilité (oui / non)
  `embauche`     1 = embauché, 0 = non

------------------------------------------------------------------------

## 🎯 Objectifs de l'analyse

### 1️⃣ Analyse des facteurs liés à l'embauche

-   Étudier l'impact de : âge, expérience, note, salaire, spécialité,
    diplôme, sexe, disponibilité.
-   Visualiser les différences entre candidats embauchés et non
    embauchés.

### 2️⃣ Profil général des candidats

-   Statistiques descriptives.
-   Répartition des diplômes, sexes, couleurs de cheveux et spécialités.
-   Analyse des distributions des variables clés.
-   Nettoyage et traitement des données manquantes.

------------------------------------------------------------------------

## 🛠️ Technologies utilisées

-   Python 3
-   Pandas
-   NumPy
-   Matplotlib / Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🚀 Résultats attendus

-   Compréhension des critères d'embauche
-   Profil général des candidats
-   Visualisations et rapports

------------------------------------------------------------------------

## 📁 Structure du projet

    📦 analyse-candidats
     ┣ 📂 data
     ┃ ┗ candidats.csv
     ┣ 📂 notebooks
     ┃ ┗ analyse.ipynb
     ┣ 📂 outputs
     ┃ ┣ graphiques/
     ┃ ┗ rapports/
     ┣ README.md
     ┗ requirements.txt
