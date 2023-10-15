# Application Web de Classification d'Images de Chiens et de Chats avec Flask

## Description

L'application est conçue pour permettre aux utilisateurs de télécharger des images de chiens ou de chats via une interface conviviale. Elle utilise un modèle CNN (Convolutional Neural Network) pré-entraîné pour classifier ces images en chiens ou en chats. L'interface utilisateur simple permet aux utilisateurs de télécharger une image, après quoi l'application fournit une prédiction quant à savoir si l'image téléchargée représente un chien ou un chat. Le processus de classification est entièrement automatisé et se déroule côté serveur.

Le modèle CNN utilisé a été entraîné sur un large ensemble de données comprenant des images de chiens et de chats. Le modèle a été optimisé pour obtenir une précision élevée de classification et est intégré dans l'application pour permettre des prédictions rapides et fiables.

L'application utilise le micro-framework Flask pour l'interface utilisateur Web et la gestion des requêtes. Elle permet également aux utilisateurs de télécharger plusieurs images successivement et de voir les prédictions pour chaque image téléchargée.

Le projet comprend également des fonctionnalités de gestion de fichiers pour stocker temporairement les images téléchargées, ainsi que des bibliothèques de traitement d'images pour prétraiter les images téléchargées avant de les soumettre au modèle de classification.

## Fonctionnalités

- Interface simple permettant aux utilisateurs de télécharger des images.
- Utilisation d'un modèle CNN pré-entraîné pour classifier les images de chiens et de chats.
- Affichage rapide des résultats de classification pour chaque image téléchargée.
- Gestion sécurisée des fichiers téléchargés et des prédictions effectuées.
- Prétraitement des images téléchargées pour les adapter à la taille requise par le modèle CNN.
- Prise en charge de plusieurs téléchargements successifs d'images.

## Dépendances

- Flask : Un micro-framework Web léger pour Python.
- TensorFlow : Une plateforme open source de bout en bout pour l'apprentissage automatique.
- Keras : Une bibliothèque open source de réseaux de neurones pour Python.
- NumPy : Une bibliothèque pour le calcul scientifique en Python.
- Werkzeug : Une bibliothèque WSGI (Web Server Gateway Interface) pour Python.

Ce projet fournira une application Web simple mais utile pour les utilisateurs qui souhaitent rapidement classifier des images de chiens et de chats sans avoir à exécuter de code ou à utiliser un terminal.
