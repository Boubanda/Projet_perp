# Projet Perp - Analyse de Sentiment avec BERT

Ce projet consiste à entraîner un modèle BERT pour la classification de sentiment sur des critiques d'applications mobiles. L'objectif est de prédire si les critiques sont positives ou négatives.

## Structure du projet

- **`src/`** : Contient tous les fichiers Python pour l'extraction des données, le prétraitement, l'entraînement du modèle et les prédictions.
  - `data_extraction.py` : Code pour charger les données depuis un fichier CSV.
  - `data_processing.py` : Code pour nettoyer et prétraiter les données.
  - `model.py` : Code pour définir, entraîner et sauvegarder le modèle BERT.
  - `inference.py` : Code pour charger un modèle pré-entraîné et faire des prédictions sur de nouvelles données.
- **`tests/`** : Contient des tests unitaires pour vérifier la bonne exécution du code.
  - `test_model.py` : Tests pour valider le bon fonctionnement du modèle.
- **`dataset.csv`** : Fichier CSV contenant les critiques à analyser.
- **`requirements.txt`** : Liste des dépendances Python nécessaires pour exécuter le projet.

## Installation

1. Clonez le dépôt :

```bash
git clone https://github.com/ton_nom_utilisateur/Projet_perp.git
