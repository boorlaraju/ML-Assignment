# Titanic Survival Prediction - Machine Learning Assignment 
## BOORLA RAJU ID:B200276 

This repository contains a complete machine learning pipeline applied to the **Titanic dataset** to predict passenger survival.

## 📁 Dataset
The dataset used is the **Titanic Survival Dataset** from [Kaggle](https://www.kaggle.com/competitions/titanic/data), which contains information about the fate of passengers on the Titanic.

- `train.csv` - training data
- `test.csv` - testing data

## 🔍 Objective
To build and compare various machine learning models to predict whether a passenger survived the Titanic disaster.

---

## ✅ Workflow

### 1. 📥 Data Loading
- Loaded using pandas
- Combined train and test sets for consistent preprocessing

### 2. 🧼 Data Cleaning & Preprocessing
- Handled missing values (`Age`, `Cabin`, `Embarked`)
- Converted categorical variables to numerical (e.g., `Sex`, `Embarked`)
- Feature engineering (e.g., `Title`, `FamilySize`, `IsAlone`)
- One-hot encoding and label encoding applied

### 3. 📊 Exploratory Data Analysis
- Plotted distributions of age, fare, survival count
- Visualized relationships using:
  - Barplots
  - Countplots
  - Heatmaps (for correlation)

### 4. ⚙️ Feature Selection
- Selected important features based on correlation and domain knowledge:
  - `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, `Title`, `FamilySize`, `IsAlone`

---

## 🤖 Models Implemented

| Model                     | Accuracy (on test/validation) |
|--------------------------|-------------------------------|
| Logistic Regression       | ✅                            |
| K-Nearest Neighbors (KNN) | ✅                            |
| Support Vector Machine    | ✅                            |
| Decision Tree Classifier  | ✅                            |
| Random Forest Classifier  | ✅                            |
| Naive Bayes               | ✅                            |

> Note: Use cross-validation or hold-out validation to compare models accurately.

---

## 📈 Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve (for binary classification)

---


