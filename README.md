# Analyse de données sur les prix des maisons

Ce projet utilise un ensemble de données sur les prix des maisons pour effectuer une analyse exploratoire des données, visualiser les données et créer des modèles de régression pour prédire les prix des maisons.

## Dépendances

- os
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

## Description du projet

Le projet commence par importer les données à partir d'une URL. Ensuite, il nettoie les données en supprimant les colonnes inutiles et en traitant les valeurs manquantes. Il effectue ensuite une analyse exploratoire des données en utilisant des statistiques descriptives et des visualisations.

Le projet utilise ensuite la régression linéaire pour prédire les prix des maisons en fonction de différentes caractéristiques. Il utilise également la régression Ridge et la régression polynomiale pour améliorer les prédictions.

## Utilisation

Pour exécuter le projet, vous pouvez simplement exécuter le script Python dans un environnement qui a les dépendances nécessaires installées.

## Résultats

Nous avons utilisé plusieurs modèles pour prédire les prix des maisons et voici les résultats que nous avons obtenus :

- **Régression linéaire** : Le modèle de régression linéaire a obtenu un score R-carré de 0.6614 sur l'ensemble de test.
- **Pipeline avec mise à l'échelle, caractéristiques polynomiales et régression linéaire** : Nous avons créé un pipeline qui met à l'échelle les caractéristiques, les transforme en caractéristiques polynomiales (sans biais) et utilise la régression linéaire pour prédire les prix des maisons. Ce modèle a obtenu un score R-carré de 0.7513.
- **Régression Ridge** : Le modèle de régression Ridge avec un alpha de 0.1 a obtenu un score R-carré de 0.6479 sur l'ensemble de test.
- **Régression Ridge avec caractéristiques polynomiales** : Nous avons transformé nos caractéristiques en caractéristiques polynomiales de degré 2 et utilisé la régression Ridge avec un alpha de 0.1. Ce modèle a obtenu un score R-carré de 0.7003 sur l'ensemble de test.

Ces résultats montrent que notre pipeline avec mise à l'échelle, caractéristiques polynomiales et régression linéaire est le modèle qui prédit le mieux les prix des maisons dans notre ensemble de données.

