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

L'objectif de ce projet est de regrouper les clients en **segments** basés sur les colonnes "Annual Income" et "Spending Score". Ces segments peuvent aider à comprendre différents profils de clients et à adapter les stratégies marketing en conséquence.

## Prérequis

- Python 3.11
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
```

## Structure du Projet

**Customers.csv** : Le fichier de données contenant les informations clients.

**K_means.ipynb** : Le notebook Jupyter contenant le code de segmentation des clients avec K-Means.

## Explication du Notebook

**Importation des bibliothèques** : On importe toutes les bibliothèques nécessaires (pandas, numpy, matplotlib, seaborn, scikit-learn).

**Chargement des données** : Les données sont chargées à partir de Customers.csv en utilisant pandas.

**Prétraitement des données** : 

Sélection des colonnes pertinentes pour la segmentation (Annual Income (k$) et Spending Score (1-100)).
Vérification des valeurs manquantes et nettoyage si nécessaire.

## Application de K-Means

Utilisation de l'algorithme K-Means pour segmenter les clients en groupes.

Calcul du nombre optimal de clusters en utilisant la méthode du coude (Elbow Method).

## Visualisation des clusters

Représentation graphique des différents segments de clients sur un graphique 2D, en utilisant la couleur pour distinguer les clusters.

## Résultats

Le modèle divise les clients en 5 segments distincts en fonction de leurs habitudes de dépenses et de leur revenu annuel. Cela permet de faire ressortir les groupes de clients aux comportements similaires et d'adapter des stratégies spécifiques pour chaque groupe.
