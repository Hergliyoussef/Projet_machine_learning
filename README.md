# Prédiction et Analyse de la Qualité des Jus

Ce projet a pour objectif de développer et d’évaluer des modèles de **Machine Learning** permettant :  
1. De **prédire** la note de qualité d’un jus à partir de propriétés chimiques.  
2. De **classer** la qualité en catégories (basse, moyenne, haute).  
3. D’explorer la structure des données via des techniques de **clustering**.

---

## 📄 Contenu du dépôt

- `Article_fr.pdf & Article_Ag_projet6`  
  Rapport détaillé du projet version francais et version Anglais (introduction, travaux liés, méthodologie, résultats, conclusion, références).  
- `Data6.csv`  
les données brutes contenant 4 898 enregistrements et 12 variables chimiques + colonne `quality`.  
- `projet_machine_learning_projet6.ipynb`  
  Notebook Jupyter :  
  - Prétraitement et nettoyage (suppression des valeurs manquantes, doublons)  
  - Analyse exploratoire (corrélations, importance des variables)  
  - Construction et évaluation de modèles supervisés (régressions :Multiples & polyminiale, Random Forest)  
  - Classification (Random Forest Classifier : précision, rappel, F1-score)  
  - Clustering non supervisé (KMeans, évaluation par Davies-Bouldin, visualisations 2D/3D)  
