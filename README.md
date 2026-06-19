# 🚨 Hunting Digital Frauds with Classification Algorithms (India-Based Fraud Detection System)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-DecisionTree-green?style=for-the-badge)
![SMOTE](https://img.shields.io/badge/Imbalanced%20Data-SMOTE-orange?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge)
![Data Science](https://img.shields.io/badge/Data%20Science-blue?style=for-the-badge)

---

# 📌 Problem Statement

In India, millions of digital transactions happen every second. While most are genuine, a very small fraction are fraudulent.

Detecting fraud is difficult because:
- Fraud cases are very rare (highly imbalanced data)
- Fraud patterns constantly change
- Many transactions look normal on the surface

This project builds an AI system to classify transactions as:

👉 Real (0)  
👉 Fraud (1)

---

# 💡 Solution: AI-Based Fraud Detection System

This project uses:
- Decision Tree Classifier
- SMOTE (to balance dataset)
- Data preprocessing pipeline
- Feature engineering (time-based analysis)

It helps detect fraud based on:
- Transaction amount
- Time of transaction
- Location
- Card type
- Customer behavior patterns

---

# ⚙️ Project Workflow

## 1. Data Cleaning
- Missing values handled
- Duplicates removed
- Infinite values fixed
- Datetime cleaned

Before Cleaning:
- Missing values in multiple columns

After Cleaning:
- Missing values = 0

---

## 2. Feature Engineering
Created:
- hour from transaction_time

Removed:
- transaction_id
- transaction_time

---

## 3. Encoding
Converted categorical columns using LabelEncoder:
- card_type
- location
- fraud_type
- purchase_category

---

## 4. Handling Imbalanced Data (SMOTE)

Before SMOTE:
- Real (0): 553
- Fraud (1): 258

After SMOTE:
- Real (0): 553
- Fraud (1): 553

---

## 5. Model Used
Decision Tree Classifier:
- max_depth = 5
- min_samples_split = 10

---

# 📊 Model Performance

## Confusion Matrix
