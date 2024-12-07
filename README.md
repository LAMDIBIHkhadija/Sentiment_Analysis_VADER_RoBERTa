
# Analyse de Sentiment avec VADER et Transformers

Ce projet illustre des techniques d'analyse de sentiment en Python en utilisant deux approches principales :

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)** : Une approche basée sur un dictionnaire de mots (bag-of-words) pour évaluer les sentiments.  
2. **Modèle pré-entraîné RoBERTa** : Un modèle basé sur les transformers, fourni par Hugging Face, pour une analyse des sentiments prenant en compte le contexte.  
3. **Pipeline Transformers** : Une méthode rapide et simple pour exécuter des prédictions de sentiments à l'aide de l'API `pipeline` de Hugging Face.

## Aperçu du Projet

Le notebook couvre les étapes suivantes :  
- **Chargement et Prétraitement des Données** :  
  - Lecture du dataset des avis alimentaires d'Amazon (Amazon Fine Food Reviews).  
  - Analyse exploratoire des données (EDA) pour comprendre la distribution des avis.  
- **Analyse de Sentiment avec VADER** :  
  - Évaluation des textes sur les sentiments positifs, neutres et négatifs en utilisant une approche bag-of-words.  
  - Visualisation des scores de sentiment par rapport aux étoiles des avis.  
- **Analyse de Sentiment avec RoBERTa** :  
  - Utilisation du modèle pré-entraîné `cardiffnlp/twitter-roberta-base-sentiment` pour la classification des sentiments.  
  - Évaluation des textes basée sur des modèles transformers prenant en compte le contexte.  
  - Comparaison des résultats entre RoBERTa et VADER.  
- **Pipeline Transformers** :  
  - Démonstration de l'utilisation de l'API `pipeline` de Hugging Face pour des prédictions rapides des sentiments.

## Installation

Pour exécuter ce projet, vous aurez besoin des bibliothèques Python suivantes :

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk`
- `transformers`
- `tqdm`
- `scipy`
  
## Dataset : 
- [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)  
