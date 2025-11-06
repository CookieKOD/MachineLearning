#  Détection de malwares – Projet Machine Learning

*Projet académique réalisé dans le cadre de mon Master 1 en Intelligence Artificielle et Big Data à l’École Supérieure Polytechnique de Dakar.*

## Objectif
Développer un modèle de classification capable d’identifier des fichiers exécutables comme **malveillants** ou **légitimes**, à partir de caractéristiques extraites de leur structure (features statiques).

## Fonctionnalités principales
- Extraction de features à partir de fichiers PE (Portable Executable)
- Entraînement d’un modèle **Decision Tree** (optimisé avec GridSearchCV)
- Sauvegarde du modèle au format `.joblib`
- Script de déploiement simple (`malware-deploy.py`) pour tester une nouvelle instance

## Outils & technologies
- Python 3.9+
- Bibliothèques : `pandas`, `scikit-learn`, `joblib`
- Dataset : "MalwareData.csv" basé sur la base de données de VirusTotal
- Visualisation : matplotlib/seaborn (graphiques dans `/images`)

# Installation des dépendances
Installez les dépendances :
   ```bash
   pip install -r requirements.txt
```
⚠️ Remarque 

Ce projet a une vocation pédagogique. Il ne remplace pas un outil de cybersécurité professionnel, mais montre la capacité à transformer des données brutes en modèle prédictif fonctionnel. 
 
