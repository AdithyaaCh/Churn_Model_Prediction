# Churn_Model_Prediction

# 📉 Telco Customer Churn Prediction

Predicting customer churn to help telecom companies retain valuable users.

---

## 🧠 Business Problem

Customer churn — when a customer stops using a service — is a major issue for telecom companies. It’s far more cost-effective to retain existing customers than to acquire new ones. However, many companies react to churn *after* it happens, losing both revenue and the chance to intervene early.

This project aims to solve that problem by building a **machine learning model** that can **predict whether a customer is likely to churn** based on their usage patterns, contract details, and demographics.

---

## 📊 Dataset

The data comes from the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), which includes:

- Customer demographics (gender, senior citizen status, etc.)
- Services subscribed (internet, phone, streaming, etc.)
- Account information (contract type, tenure, payment method)
- Churn label (Yes/No)

---

## ⚙️ Models Used

Two machine learning models were trained and evaluated:

### 🌲 Decision Tree
- Easy to interpret
- Captures simple logical rules
- Prone to overfitting on small datasets

### 🌳 Random Forest
- Ensemble of decision trees
- More robust and accurate
- Better generalization

---

## 📈 Evaluation Metrics

The models were evaluated using:

- **Accuracy**

---

## 🧪 Results

| Model           |Accuracy|
|----------------|----------|
| Decision Tree  | 77.0%    | 
| Random Forest  | 80.0%    | 

🔍 **Random Forest** performed better across all metrics and was chosen as the final model.




