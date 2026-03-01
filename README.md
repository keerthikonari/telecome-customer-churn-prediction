# 📊 Telecom Customer Churn Prediction

##  Project Overview

This project aims to predict customer churn in a telecom company using Machine Learning classification models.  
The goal is to identify customers who are likely to leave the service so that businesses can take proactive retention measures.

This is an end-to-end machine learning project covering data preprocessing, exploratory data analysis (EDA), handling class imbalance, model building, and evaluation.

---

##  Business Objective

Customer churn directly affects company revenue. By predicting churn:

- Companies can reduce customer loss
- Retention strategies can be improved
- Marketing efforts can be optimized
- Business decisions can be data-driven

---

##  Dataset Information

The dataset contains the following features:

- Customer demographics (Gender, Senior Citizen)
- Account information (Tenure, Contract Type, Payment Method)
- Service subscriptions (Internet Service, Phone Service, Streaming)
- Monthly Charges
- Total Charges
- Target Variable: *Churn (Yes/No)*

---

##  Project Workflow

### 1️⃣ Data Preprocessing

- Handled missing values
- Converted data types where necessary
- Encoded categorical variables
- Feature scaling
- Removed unnecessary columns

### 2️⃣ Exploratory Data Analysis (EDA)

- Analyzed churn distribution
- Compared contract type vs churn
- Studied tenure vs churn
- Analyzed monthly charges impact
- Generated correlation heatmap

### 3️⃣ Handling Imbalanced Data

- Applied *SMOTE (Synthetic Minority Oversampling Technique)*
- Balanced the dataset before model training

### 4️⃣ Model Building

Implemented multiple classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 5️⃣ Model Evaluation

Evaluated models using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Special focus was given to *Recall* to correctly identify churn customers.

---

## 📊 Key Insights

- Month-to-month contract customers show higher churn rates.
- Customers with short tenure are more likely to churn.
- Higher monthly charges increase churn probability.
- Contract type and tenure are strong predictors.

---

## 🏆 Results

- Class imbalance handling improved model performance.
- Ensemble models performed better than basic models.
- The best model achieved strong recall and ROC-AUC score.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

---
