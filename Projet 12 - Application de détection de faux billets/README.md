# Projet 12 : Application de détection de faux billets

<br/>

## 🎬 Scénario  
Dans le cadre d’une mission de Data Analyst pour l'ONCFM (Organisation nationale de lutte contre le faux-monnayage), vous êtes chargé d’évaluer différents modèles de machine learning pour détecter automatiquement les faux billets à partir de leurs caractéristiques physiques.

<br/>

## 🎯 Objectifs  

- Analyser le jeu de données ainsi que les caractéritiques géométriques des billets et le préparer pour leur utilsiation dans des modèles 
- Tester plusieurs algorithmes de classification supervisée et non supervisée  
- Comparer leurs performances à l’aide de métriques adaptées  
- Créer une interface interactive pour exploiter le modèle final

<br/>

## 🛠 Outils utilisés  
- Python 
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn
- SciPy, scikit-learn et statsmodels

<br/>

## 📈 Étapes du projet  
- Chargement et exploration des données  
- Visualisation et compréhension des variables
<p align="center"><em>Analyses des variables et des distributions</em><br/><img src="images/12-analyses-variables.png" alt="Analyses des variables" width="450"/></p>

- Réalisation d'une régression linéaire pour combler les valeurs manquantes
- Sélection des variables prédictives
<p align="center"><img src="images/12-selection-variables-predictives.png" alt="Sélection des variables prédictives" width="500"/></p>

- Réalisation d'une régression logistique
- Modélisation non supervisée : K-means
<p align="center"><em>Projections des clusters Kmeans via ACP</em><br/><img src="images/12-projection-kmeans.jpg" alt="Projections clusters Kmeans" width="500"/></p>

- Modélisation KNN
<p align="center"><img src="images/12-variations-knn.png" alt="Variation de K modèle KNN" width="450"/></p>

- Modélisation Random Forest
- Optimisation par GridSearchCV
- Évaluation des performances (accuracy, AUC, courbe ROC)  
- Comparaison des modèles
<p align="center"><img src="images/12-comparaisons-modeles.jpg" alt="Comparaison des modèles" width="500"/></p>

- Exportation du modèle sélectionné (KNN)
- Création d'une interface interactive pour tester de nouveaux billets
<p align="center"><img src="images/12-application.jpg" alt="Application de détection" width="600"/></p>
