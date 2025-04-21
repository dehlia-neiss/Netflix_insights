Netflix Insights
Contexte du projet
Netflix est aujourd’hui un acteur majeur du streaming avec plus de 200 millions d’abonnés. Ce projet a pour but d’analyser les données du catalogue Netflix (films et séries) en septembre 2021. L’objectif est d’explorer les données pour comprendre les tendances du contenu proposé.

L’analyse est faite avec Python et les outils classiques de data science : Jupyter Notebook, Pandas, Seaborn, Plotly, etc.

Veille sur l’intelligence artificielle
Qu’est-ce que l’intelligence artificielle ?
L’intelligence artificielle (IA), c’est quand une machine arrive à imiter un comportement humain : apprendre, réfléchir, résoudre des problèmes, etc. Exemple : quand Netflix te recommande des films selon ce que tu as déjà regardé.

Qu’est-ce que le Machine Learning ?
Le Machine Learning, c’est une branche de l’IA. Il permet aux machines d’apprendre à partir de données sans que quelqu’un les programme ligne par ligne. Exemple : un algorithme qui devine quel film tu pourrais aimer ensuite.

Qu’est-ce que le pré-traitement des données ?
C’est l’étape où on nettoie les données avant de les analyser. On enlève les valeurs manquantes, on met les bons formats (genre convertir une date en vrai type date), on vire les doublons, etc.

Qu’est-ce que l’analyse descriptive des données ?
C’est le fait de regarder les données de base pour comprendre ce qu’on a sous les yeux. On regarde les moyennes, les fréquences, les répartitions, et tout ce qui permet de faire un premier état des lieux.

Exemple d’application dans la santé
Dans le domaine médical, l’IA permet de :

détecter certaines maladies à partir de radios ou d’IRM,
prédire des risques de maladies avec les données patient,
assister les médecins dans les diagnostics,
organiser les urgences ou les rendez-vous de façon plus efficace.
Concrètement, un algorithme peut trouver une tumeur sur une image médicale plus rapidement qu’un médecin. Et il peut apprendre à s’améliorer avec plus de données.

Données utilisées
Le jeu de données utilisé vient de Kaggle, mis à jour en septembre 2021. Il contient des infos sur les films et séries présents sur Netflix : titre, type, pays, réalisateur, date de sortie, durée, genres, etc.

Objectif du projet
L’objectif est de :

Charger et explorer les données Netflix
Nettoyer les données (dates, durées, valeurs manquantes…)
Visualiser différentes tendances : types de contenu, durée, années, pays, etc.
Sortir quelques conclusions sur ce que propose Netflix
Outils utilisés
Python
Jupyter Notebook
Pandas, Numpy
Seaborn, Matplotlib, Plotly
Missingno
Structure du projet
netflix-insights/

── netflix_data_analysis.ipynb ── README.md
── dataset/netflix_titles.csv
