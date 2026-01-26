# Setting up the technical test / Mise en place du test technique

To carry out the technical test, we advise you to use this platform : / Pour réaliser le test technique, nous vous conseillons d'utiliser cette plateforme :

https://mybinder.org/

If you are already familiar with mybinder, you can click directly on the button below : / Si vous êtes déjà familiarisé avec mybinder, vous pouvez cliquer directement sur le bouton ci-dessous :

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mdm-test-anonymous/technical_test.git/master)

How it works: / Comment ça marche : 

-  The candidate opens the Binder page, and fills in the repo information: / Le candidat ouvre la page Binder, et renseigne les informations du repo :
https://github.com/mdm-test-anonymous/technical_test.git
![Visualization](https://github.com/NTAIRec/technical_test/blob/master/img/binder.png)

-  Once the Jupyter server has been created : / Une fois le serveur Jupyter créé :
![Jupyter Server](https://github.com/NTAIRec/technical_test/blob/master/img/jupyter_server.png)


-  The candidate is working on his version of the Jupyter, no modifications on the Github repo: / Le candidat travaille sur sa version du Jupyter, pas de modification sur le repo Github :
![Notebook](https://github.com/NTAIRec/technical_test/blob/master/img/Notebook.png)


-  At the end of the work, the candidate downloads his version of the notebook and sends it to us for discussion. / A la fin du travail, le candidat télécharge sa version du notebook et nous l’envoie pour discussion.

# Content of the technical test (In French below)

The order doesn't matter, it doesn't matter either if you don't finish all the parts. If you need more python librairies, you can add them executing the following command in a cell : !pip install <the_package_name> (dont forget the !)

-  Part 1: Predicting the position of a city from weather data
The objective of this exercise is to try to predict whether a city is above or below the 60th parallel based on temperature and precipitation readings in winter 2015 and 2016.
To do this, load the file: data_ex_1.csv 
All three issues will have to be addressed by a generative model and a discriminant model.

-  Part 2: Predicting the type of building (high or low) based on geographic coordinates and altitude 
The objective of this exercise is to try to predict whether or not a building is high-rise or not based on GPS-type coordinates (the unit is not known). When the data is not known, it has been set to 0.
To do this use the file: data_ex_2.csv
The three issues will have to be addressed by two models together.

-  Part 3: SQL
The objective of this exercise is to mnipulate data in SQL

# Contenu du test technique

L’ordre n’a pas d’importance, ce n’est pas grave non plus de ne pas finir toutes les parties. Si vous avez besoin d'autres librairies python, vous pouvez les ajouter via la commande suivante dans une cellule : !pip install <the_package_name> (ne pas oublier le !)

-  1ère Partie : Prédiction de la position d’une ville à partir de données météo
L’objectif de cet exercice est d’essayer de prédire si une ville se trouve au-dessus ou en dessous du 60ème parallèle en fonction des relevés de température et de précipitation en hiver 2015 et 2016.
Pour cela charger le fichier : data_ex_1.csv 
Les trois questions devront être traitées par un modèle génératif et par un modèle discriminant.

-  2ère Partie : Prédiction du type d’immeuble (haut ou bas) en fonction des coordonnées géographiques et de l’altitude 
L’objectif de cet exercice est d’essayer de prédire si un immeuble est de grande hauteur ou pas en fonction des coordonnées de type GPS (l’unité n’est pas connue). Quand les données ne sont pas connues elles ont été renseignées à 0.
Pour cela utiliser le fichier : data_ex_2.csv
Les trois questions devront être traitée par deux modèles ensemblistes.


-  3ème partie : SQL
L’objectif de cet exercice est de manipuler des données en sql
