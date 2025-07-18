# 📉 Customer Churn Prediction

This machine learning project predicts whether a customer will churn (leave the service) based on their demographics, account details, and usage patterns. The dataset used is from a telecom company and includes features like contract type, payment method, tenure, and service subscriptions.

---

## 📁 Dataset

- **Name**: Telco Customer Churn
- **Source**: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7043
- **Columns**: 21
- **Target**: `Churn` (Yes/No)

---

## 🛠️ Techniques Used

- ✔ **Data Preprocessing** (null handling, type conversion)

- ✔ **Feature Engineering**
  - `tenure_group` (binning continuous `tenure`)
  - interaction terms

- ✔ **Encoding**
  - Label Encoding for binary columns
  - One-Hot Encoding for nominal categorical columns
  - Manual Mapping for ordinal columns (e.g., `Contract`)

- ✔ **Class Imbalance Handling**
  - SMOTE (Synthetic Minority Oversampling Technique)

- ✔ **Model Training**
  - Decision Tree
  - Random Forest
  - XGBoost
  - Voting Classifier (ensemble of top models)

- ✔ **Hyperparameter Tuning**
  - GridSearchCV on Random Forest

- ✔ **Evaluation Metrics**
  - Accuracy, F1 Score, Recall
  - ROC AUC Curve
  - Confusion Matrix

---
