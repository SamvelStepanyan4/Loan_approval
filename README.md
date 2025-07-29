# 🏦 Loan Approval Classification

Welcome to the **Loan Approval Classification** project! This repository contains a machine learning pipeline to predict whether a loan application will be approved or not based on applicant data. We explore multiple models and handle data cleaning, anomalies, and feature engineering to improve prediction accuracy. 🚀

---

## 📂 Files in this Repository

- `train.csv` — Training dataset containing loan applicant features and their approval status.  
- `test.csv` — Test dataset with applicant features for which we want to predict loan approval.  
- `Loan_approval.ipynb` — Jupyter notebook with full code, step-by-step data cleaning, model training, evaluation, and predictions.

---

## 🔎 Project Overview

Loan approvals are crucial decisions for banks and financial institutions. Automating this process using machine learning helps to speed up decisions, reduce human bias, and identify key factors affecting approvals.

In this project, we:  
- Clean and preprocess the data (handle missing values, anomalies, categorical variables) 🧼  
- Try multiple classification algorithms to find the best-performing model 🤖  
- Compare model results and provide insights 📊  

---

## 🧹 Data Preprocessing Steps

1. **Load Data:** Using pandas to read `train.csv` and `test.csv`.  
2. **Data Cleaning:** Handle missing values, fill or drop as appropriate.  
3. **Anomaly Detection:** Analyze and handle outliers/anomalies. The notebook compares results using data with and without anomalies.  
4. **Feature Encoding:** Convert categorical variables into numeric form using Label Encoding or One-Hot Encoding.  
5. **Feature Scaling:** If needed, scale numerical features for models like KNN.

---

## 🤖 Models Used

We experimented with several popular machine learning models:

| Model                | Description                             | Emoji  |
|----------------------|-------------------------------------|--------|
| K-Nearest Neighbors   | Classifies based on closest neighbors | 🔍     |
| Random Forest        | Ensemble of decision trees for robust classification | 🌲     |
| XGBoost              | Gradient boosting algorithm with high performance | 🚀     |
| Logistic Regression  | Linear model for binary classification | 📈     |

The notebook contains detailed code for training each model, tuning hyperparameters, and evaluating accuracy.

---

## 📊 Model Evaluation & Results

- Metrics used: **Accuracy**, **Precision**, **Recall**, and **F1-Score**.  
- Comparison of models to find the best one for loan approval prediction.  
- Discussion on how anomalies affected model performance.  

---

## ⚙️ How to Run

1. Clone this repository.  
2. Make sure you have Python 3 installed with the following packages (can install with pip):  
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn
