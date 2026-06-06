# California Housing Price Prediction 🏠

## 📌 Description
Ce projet de machine learning vise à prédire les prix des logements en Californie à partir de variables socio-économiques.  
L’objectif est de construire un pipeline complet de régression et de comparer plusieurs modèles de machine learning.

---

## 📊 Dataset
Le projet utilise le dataset intégré de **scikit-learn : California Housing Dataset**.

Il contient des informations telles que :
- revenu médian
- âge des maisons
- nombre de pièces
- localisation
- population

---

## ⚙️ Pipeline du projet

Le projet suit les étapes suivantes :
1. Chargement des données
2. Séparation train/test
3. Standardisation des variables
4. Construction de pipelines ML
5. Optimisation des hyperparamètres
6. Évaluation des performances

---

## 🤖 Modèles utilisés

Actuellement, les modèles testés sont :

- SGDRegressor
- RandomForestRegressor (📌 en cours d’ajout dans un notebook dédié)

👉 Un notebook spécifique sera ajouté pour :
- RandomForestRegressor
- optimisation des hyperparamètres
- analyse des features importantes

---

## 📈 Évaluation

Les modèles sont évalués avec :
- R² score (coefficient de détermination)
- Mean Squared Error (MSE)
- Cross-validation (GridSearchCV)

---

## 📁 Structure du projet
