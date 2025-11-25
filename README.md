<div align="center">

<h1 style="font-size: 40px; font-weight: 700; margin-bottom: 10px;">
 Fraud & Anomaly Detection in Financial Transactions by Machine learning 
</h1>

<p style="font-size: 18px; color: #555; max-width: 700px;">
A machine learning project that detects fraudulent financial transactions using 
feature engineering, Chi-Square feature selection, and Logistic Regression.
Built as part of my AI coursework — focused on showing 
<strong>data cleaning → preprocessing → feature engineering → model training → evaluation</strong>.
</p>

<img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=for-the-badge"/>

</div>
<br>

---

## 🌟 Overview

This project analyzes a large financial transaction dataset and builds a machine learning
model to classify transactions as **fraud (1)** or **non-fraud (0)**.

The goal is to show:
- ✔ Data cleaning  
- ✔ Feature selection  
- ✔ Feature engineering  
- ✔ Model training  
- ✔ Evaluation  
- ✔ Interpretation of fraud patterns  

This project demonstrates practical handling of **imbalanced datasets**,  
fraud patterns, and ML interpretability.

---

## 📌 Dataset

**Source:** Synthetic Financial Transactions Dataset (Kaggle)  
**Records:** ~6.3 million  
**Fraud cases:** Only 8,213 → extremely imbalanced (~0.12%)

Main challenges:
- Highly skewed class distribution  
- Multiple transaction types  
- Balance discrepancies  
- Patterns hidden without feature engineering  

---

## 🧹 1. Data Cleaning

```python
df.drop(['nameOrig', 'nameDest'], axis=1)
df = pd.get_dummies(df, columns=['type'], drop_first=True)
