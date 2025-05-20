# 🔍 Churn Prediction Model for Bank Customers

This project aims to predict whether a bank customer is likely to churn using machine learning techniques. It uses **Logistic Regression**, **Random Forest**, and **XGBoost** classifiers, with a focus on optimizing the **recall score** for identifying churning customers.

---

## 📊 Dataset

The dataset used in this project contains several columns which has customer information and then a target column which specifies whether the customer will churn or not

The dataset is included in this repository as:  
📁 `churn_prediction.csv` 

---

## 🧠 Models Used

Three classification models were trained and compared:

- ✅ **Logistic Regression**
- ✅ **Random Forest**
- ✅ **XGBoost**

Additionally, **Recursive Feature Elimination (RFE)** was applied to improve model performance by selecting the most relevant features.

---

## 🎯 Goal

The primary evaluation metric for this project is **Recall**, as correctly identifying churning customers is crucial for retention strategies.

Additionally, the AUC-ROC score was also taken into consideration.

---

## 🏁 Final Results

- **Best Model**: ✅ **Random Forest Classifier**
- **Why?** It achieved the highest recall score among all models.
- **Feature Selection**: RFE was applied, and results with fewer features showed better or comparable recall.

---
