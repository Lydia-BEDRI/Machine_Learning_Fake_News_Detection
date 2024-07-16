# Machine_Learning_Fake_News_Detection

## Projet Machine Learning HAI817
Université de Montpellier, Faculté des Sciences

**Année universitaire : 2023-2024**

### Réalisé par :
- Louis BALANDRAS
- Lydia BEDRI
- Sara ZIDOUNE
- Alexandre SAR
- Mohamad EL-KAAKOUR

### Encadrants :
- Pascal PONCLET
- Ensiyeh RAOUFI

## Introduction
Ce projet vise à développer un modèle de détection automatique des fake news en utilisant des techniques de machine learning sur des données textuelles. 

## Prétraitement des données
Le prétraitement inclut :
- Suppression des colonnes inutiles
- Gestion des valeurs manquantes
- Fusion de `title` et `text`
- Conversion en minuscules
- Suppression des stopwords
- Lemmatisation

## Modèles de classification
Nous avons exploré plusieurs approches de classification :
1. **True vs. False** : Élimination des catégories "mixture" et "other".
2. **True or False vs. Other** : Regroupement des catégories "True" et "False" contre "Other".
3. **True vs. False vs. Mixture vs. Other** : Classification multi-classes.

## Résultats et Comparaison
Les modèles utilisant TF-IDF ont surpassé ceux utilisant BoW. Les techniques de prétraitement avancées ont amélioré la performance des modèles.

## Conclusion
La combinaison de TF-IDF, lemmatisation et suppression des stopwords donne les meilleurs résultats pour la détection de fake news.

## Notebooks
- `Pretraitement.ipynb` : Prétraitement des données.
- `True_vs_False.ipynb` : Classification binaire "True" vs. "False".
- `True_or_False_vs_Other.ipynb` : Classification binaire "True or False" vs. "Other".
- `True_vs_False_vs_Mixture_vs_Other.ipynb` : Classification multi-classes.

