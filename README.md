# Mini-Projet Big Data — Sujet A : Avis clients e-commerce

Pipeline Spark → MongoDB pour l'analyse d'avis produits (dataset Amazon Fine Food Reviews).

## Contenu
- `examBigData.ipynb` — notebook principal (nettoyage, indicateurs, écriture MongoDB)
- `Rapport_BigData.pdf` — rapport du projet

## Prérequis
- Python 3.12, PySpark 4.2.0, pymongo
- MongoDB (via Docker : `docker run -d --name mongo_avis -p 27017:27017 mongo:7`)

## Dataset
Télécharger "Amazon Fine Food Reviews" sur Kaggle et placer `Reviews.csv` 
à la racine du projet (non inclus dans ce dépôt, voir .gitignore).