# Customer Churn Prediction

## 📌 Project Overview
This project predicts customer churn using machine learning.  
We trained and tuned an **XGBoost classifier** with SMOTE oversampling for handling class imbalance.  
Model explainability was added using **SHAP (SHapley Additive exPlanations)** to interpret feature importance and decision contributions.

---

## ⚙️ Features
- Data preprocessing and handling class imbalance with **SMOTE**
- Model training using **XGBoost**
- **Hyperparameter tuning** with RandomizedSearchCV
- **Threshold tuning** to balance precision/recall
- Model explainability using **SHAP**
- Visualizations for feature importance and SHAP summary plots

---

## 🗂️ Dataset
The dataset contains customer information with churn labels.  
- Features include demographics, usage, account details, etc.  
- Target: `churn` (1 = churned, 0 = retained)

> ⚠️ Dataset is not uploaded here due to size/privacy. Please place your dataset in the `/data` folder before running.

---

## 📊 Results
- Best ROC-AUC Score (CV): **0.90**
- Test ROC-AUC Score: **0.81**
- Accuracy: ~**76%**
- SHAP analysis shows that features such as `X`, `Y`, `Z` (replace with actual ones from your SHAP plots) strongly influence churn.

---

## 🚀 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/abhinav428/customer_churn_prediction.git
   cd customer_churn_prediction
