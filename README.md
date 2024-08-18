<div align="center">
  <h1>Analyse de Données sur les Prix des Maisons</h1>
  <p>Ce projet utilise un ensemble de données sur les prix des maisons pour effectuer une analyse exploratoire, visualiser les données et créer des modèles de régression pour prédire les prix des maisons.</p>
  <img src="https://github.com/user-attachments/assets/d9102f04-3414-4fd7-a77a-d745c76ea0f4" alt="House Prices Analysis" width="600">
</div>

<hr>

## 🛠️ Dépendances

- `os`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

## 📝 Description du Projet

Le projet commence par importer les données à partir d'une URL, puis nettoie les données en supprimant les colonnes inutiles et en traitant les valeurs manquantes. Une analyse exploratoire des données est effectuée en utilisant des statistiques descriptives et des visualisations.

Ensuite, le projet utilise la régression linéaire pour prédire les prix des maisons en fonction de différentes caractéristiques. Des modèles de régression Ridge et de régression polynomiale sont également utilisés pour améliorer les prédictions.

## 🚀 Utilisation

Pour exécuter le projet, lancez simplement le script Python dans un environnement avec les dépendances nécessaires installées.

```bash
python analyse_prix_maisons.py
## 📊 Résultats

Nous avons utilisé plusieurs modèles pour prédire les prix des maisons, et voici les résultats obtenus :

- **Régression linéaire** : Le modèle de régression linéaire a obtenu un score R-carré de **0.6614** sur l'ensemble de test.
- **Pipeline avec mise à l'échelle, caractéristiques polynomiales et régression linéaire** : Ce modèle a obtenu un score R-carré de **0.7513**.
- **Régression Ridge** : Le modèle de régression Ridge avec un alpha de 0.1 a obtenu un score R-carré de **0.6479** sur l'ensemble de test.
- **Régression Ridge avec caractéristiques polynomiales** : Ce modèle a obtenu un score R-carré de **0.7003** sur l'ensemble de test.

Ces résultats montrent que notre pipeline avec mise à l'échelle, caractéristiques polynomiales et régression linéaire est le modèle le plus performant pour prédire les prix des maisons dans cet ensemble de données.

## 🖼️ Visualisation

Feel free to explore, experiment, and contribute to enhance the effectiveness of this house price analysis project!
