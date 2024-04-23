# Analyse Superstore Global

Ce projet implique l'analyse du jeu de données du Superstore Global 2018. Le jeu de données contient des informations sur les commandes passées, les personnes impliquées et les régions d'où proviennent les commandes.

## Structure du Projet

Le projet a la structure suivante :

* [Global_Superstore_2018.xlsx](https://github.com/caphey/analyse-global-superstore/blob/main/Global_Superstore_2018.xlsx) : C'est le jeu de données principal utilisé pour l'analyse. Il contient trois feuilles : Orders, People et Regions.
* [notebook.ipynb](https://github.com/caphey/analyse-global-superstore/blob/main/notebook.ipynb) : Ce notebook Jupyter contient tout le code utilisé pour l'analyse.

## Analyse

L'analyse est divisée en trois parties principales :

1. Analyse descriptive : Cela implique de comprendre le jeu de données, de vérifier les valeurs nulles et d'avoir une idée des données.

2. Analyse prédictive : Cela implique de créer un modèle de régression linéaire pour prédire les ventes en fonction de la quantité et de la remise. Le modèle est entraîné sur les colonnes 'Quantity' et 'Discount' du dataframe. La colonne 'Sales' est la variable cible.

3. Analyse prescriptive : Cela implique de prendre des décisions commerciales basées sur l'analyse. Par exemple, identifier les produits avec des taux de retour élevés et ajuster les prix et les remises pour maximiser les ventes.

## Bibliothèques Utilisées

* `pandas` : Pour la manipulation et l'analyse des données.
* `numpy` : Pour les calculs numériques.
* `statsmodels` : Pour la méthode des moindres carrés pour ajuster le modèle de régression linéaire.
* `sklearn` : Pour calculer le score R² du modèle.


## Résultats

Les résultats de l'analyse sont imprimés dans le notebook Jupyter. Les coefficients et l'intercept du modèle de régression linéaire sont imprimés, ainsi que les premières prédictions du modèle. Le score R² du modèle est également calculé et imprimé.