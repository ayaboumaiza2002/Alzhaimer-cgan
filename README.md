# 🧠 Génération de Données Alzheimer avec cGAN

## 🎯 Objectif
Utiliser un GAN conditionnel (cGAN) pour générer des données médicales synthétiques similaires aux données réelles Alzheimer.

## 📁 Dataset réel
- Données tabulaires (451 colonnes)
- Chaque ligne représente un patient avec ou sans Alzheimer

## 🛠️ Technologies utilisées
- Python
- TensorFlow / Keras
- Pandas, Scikit-learn
- Matplotlib, Seaborn
- Flask (pour servir le modèle dans une API)

## 🧪 Étapes du projet
1. Prétraitement des données (normalisation, split par classe)
2. Entraînement d'un modèle cGAN sur les données réelles 
3. Génération de nouvelles données synthétiques
4. Évaluation des données générées à l'aide de classifieurs ML entraînés sur les données réelles
5. Déploiement du modèle sous forme d'API Flask

## 📊 Résultats
- Similarité statistique élevée entre données réelles et synthétiques 
- Les classifieurs atteignent +90% de précision sur les données générées

## 👩‍💻 Réalisé par
Aya Boumaiza — Master Informatique Constantine 2  
Spécialité : Data Science et Systèmes Intelligents
