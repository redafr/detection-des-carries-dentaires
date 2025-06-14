# Détection de Caries Dentaires par Apprentissage Profond

Ce projet vise à détecter automatiquement les caries dentaires à partir d'images, en utilisant un réseau de neurones convolutifs (CNN) développé avec TensorFlow/Keras. Une interface utilisateur est également fournie pour faciliter l'utilisation du modèle par des non-spécialistes, ainsi qu'une génération automatique de rapports PDF.

## Contenu du dépôt

- `detection de carries dentaires.ipynb` : Notebook principal contenant l'ensemble du traitement.
- `model_caries.h5` : Fichier du modèle entraîné.
- `README.md` : Ce fichier de description.

## Objectifs

- Prétraiter et organiser un jeu de données d'images dentaires.
- Entraîner un modèle de classification binaire pour détecter la présence de caries.
- Fournir une interface utilisateur graphique pour tester le modèle.
- Générer un rapport PDF avec la prédiction du modèle.

## Technologies utilisées

- Python
- TensorFlow / Keras
- OpenCV
- PIL (Pillow)
- Tkinter (interface graphique)
- ReportLab (PDF)

## Étapes du projet

1. **Chargement et préparation des données** à partir du dossier `teeth_dataset`
2. **Augmentation des données** avec `ImageDataGenerator` pour améliorer la robustesse du modèle
3. **Construction du modèle CNN**
4. **Entraînement et validation du modèle**
5. **Évaluation du modèle**
6. **Interface utilisateur** pour charger une image et afficher la prédiction
7. **Génération d'un rapport PDF** incluant l'image analysée et le diagnostic

