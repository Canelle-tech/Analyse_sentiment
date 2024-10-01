# Analyse de Sentiment avec LSTM et Transformers

## Description

Ce projet met en œuvre deux types de modèles de traitement du langage naturel pour l’analyse de sentiment à partir de l’ensemble de données Yelp : un modèle LSTM avec attention douce et un modèle Transformer. Le projet compare leurs performances sur cette tâche en analysant la polarité des avis clients.

## Modèles implémentés :

	1.	LSTM avec attention douce : Réseau de mémoire à long terme utilisé pour capturer la séquence des données textuelles avec un mécanisme d’attention permettant de se concentrer sur les éléments importants.
	2.	Transformer : Modèle basé sur l’attention multi-têtes, utilisé ici pour capturer des dépendances complexes dans les séquences textuelles. L’architecture est similaire à celle décrite dans Attention Is All You Need.

## Structure du Projet

	•	main.ipynb : Notebook contenant le code pour entraîner et évaluer les modèles sur l’ensemble de données Yelp.
	•	lstm.py : Contient l’implémentation du modèle LSTM avec attention.
	•	transformer.py : Contient l’implémentation du modèle Transformer.
