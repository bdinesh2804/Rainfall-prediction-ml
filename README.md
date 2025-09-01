# 🌧️ Rainfall Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict whether it will rain or not based on historical weather data using **Machine Learning algorithms**.  
The dataset includes weather parameters like temperature, humidity, wind speed, etc., and the target variable is `rainfall` (Yes/No).

## 🎯 Goal
- Build a machine learning model to **predict rainfall**.
- Handle **imbalanced data** using oversampling techniques.
- Compare different classifiers and select the best-performing one.

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** → Data processing
- **Matplotlib, Seaborn** → Visualization
- **Scikit-learn** → Logistic Regression, SVM, Evaluation metrics
- **XGBoost** → Advanced classification model
- **Imbalanced-learn (RandomOverSampler)** → Handling imbalanced dataset

## 📊 Evaluation Metrics
The models were evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**
- **Confusion Matrix**

## 🔍 Models Applied
- Logistic Regression
- Support Vector Classifier (SVC)
- XGBoost Classifier

## 📈 Results
- XGBoost performed the best overall with the highest ROC-AUC score.
- Logistic Regression provided interpretable baseline results.
- SVM showed competitive accuracy but required scaling.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Rainfall-prediction-ml.git
   cd Rainfall-prediction-ml
