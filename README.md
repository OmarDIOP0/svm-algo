# 🔍 SVM pour l’Analyse des Logs 

Ce projet utilise un algorithme **SVM (Support Vector Machine)** pour analyser les logs générés dans l’application.

## 🧠 Objectif

L’algorithme SVM a pour but de **classifier les logs** afin de détecter :
- des **comportements anormaux** (intrusions, erreurs fréquentes, abus)
- des **modèles d’utilisation** (utilisateurs actifs, accès récurrents)
- ou encore de **filtrer les logs utiles** des bruitages.

## 🛠️ Technologies

- Python 3
- `scikit-learn` pour le SVM
- `pandas` pour la gestion des données
- `matplotlib` pour la visualisation (facultatif)
- Fichiers de logs au format `.csv` ou `.txt`

## ⚙️ Comment ça marche

1. Chargement des fichiers de logs depuis l’application
2. Prétraitement des logs (nettoyage, vectorisation des événements)
3. Entraînement du modèle SVM sur des données labellisées (anomalie / normal)
4. Prédiction et visualisation des résultats

## 🚀 Lancer le modèle
