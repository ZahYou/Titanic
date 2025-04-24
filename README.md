# 🎯 Titanic Survival Prediction

Predicting passenger survival on the Titanic using machine learning (Kaggle competition).

## 📊 Project Overview

- Wettbewerb: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- Ziel: Vorhersage, ob ein Passagier überlebt hat (Klassifikation)
- Bestes Ergebnis: **🏅 Kaggle Score 0.77751**

## 🔍 Methoden

- Explorative Datenanalyse (EDA)
- Feature Engineering:
  - `FamilySize`, `Cabin_na`, `HighRiskGroup`, `Title`, ...
- Modelle:
  - RandomForestClassifier (Bestes Modell)
  - VotingClassifier, XGBoost, SHAP für Interpretierbarkeit
- Hyperparameter-Tuning mit GridSearchCV

## 📈 Wichtigste Features

| Feature     | Beschreibung                            |
|-------------|------------------------------------------|
| `Fare`      | Ticketpreis – Proxy für Status/Klasse  
| `Gender`    | Frauen überleben häufiger  
| `Age`       | Jüngere bevorzugt  
| `Pclass`    | 1. Klasse → höhere Chancen  
| `FamilySize`| kleine Familien besser als allein  
| `Cabin_na`  | Kein Kabinencode = höheres Risiko  

## 📂 Projektstruktur

