# Segmentation des Clients avec K-Means

Ce projet utilise l'algorithme de clustering **K-Means** pour segmenter des clients en groupes distincts en fonction de leurs **revenus annuels** et de leur **score de dépense**. La segmentation client est une méthode d’analyse qui permet de regrouper des clients aux comportements similaires pour une stratégie marketing ciblée.

## Dataset

Le dataset utilisé est `Customers.csv`, qui contient des informations de base sur les clients. Ce fichier a les colonnes suivantes :

- **CustomerID** : Identifiant unique du client.
- **Gender** : Sexe du client.
- **Age** : Âge du client.
- **Annual Income (k$)** : Revenu annuel du client en milliers de dollars.
- **Spending Score (1-100)** : Score de dépense, représentant le comportement d'achat du client.

## Objectif

L'objectif de ce projet est de regrouper les clients en **5 segments** basés sur les colonnes "Annual Income" et "Spending Score". Ces segments peuvent aider à comprendre différents profils de clients et à adapter les stratégies marketing en conséquence.

## Prérequis

- Python 3.x
- Jupyter Notebook
- Bibliothèques Python :
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Installation des dépendances

Pour installer les bibliothèques nécessaires, vous pouvez utiliser la commande suivante :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
