# TP1 - Régression Linéaire

Ce projet contient un notebook Jupyter réalisé dans le cadre du premier TP du cours **Introduction à l’Apprentissage Automatique** (S7). Il met en œuvre une **régression linéaire** pour modéliser des relations entre différentes variables liées à l’espérance de vie à partir d’un jeu de données fourni par l’OMS.

## 🎯 Objectifs du TP

- Configurer un environnement iPython / Jupyter Notebook
- Charger, nettoyer et visualiser un jeu de données réel
- Implémenter une régression linéaire simple à l’aide de `scikit-learn` et manuellement (descente de gradient)
- Évaluer la qualité de la régression (MAE, RMSE, R²)
- Réaliser des visualisations de diagnostic : résidus, score R², distance de Cook, etc.

## 🗂 Données

Le jeu de données contient 20 variables décrivant la situation sanitaire, économique et sociale de plusieurs pays sur une période de 15 ans. Le fichier utilisé est : `Life_Expectancy_Data.csv`.

## 🧰 Librairies utilisées

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

## ▶️ Lancer le notebook

1. Cloner le dépôt ou télécharger le fichier `.ipynb`
2. Lancer dans un environnement Jupyter :

```bash
jupyter notebook TP1_LinearRegression.ipynb
