<div align="center">

<!-- Header Banner -->
<h1 style="font-size: 40px; font-weight: 700; margin-bottom: 10px;">
 Fraud & Anomaly Detection in Financial Transactions by Machine learning
</h1>

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/Python-3.12.2-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
</p>

</div>

---

<div align="center">

## 🎯 **Project Overview**

</div>

<p style="font-size: 18px; color: #555; max-width: 700px;">
A machine learning project that detects fraudulent financial transactions using 
feature engineering, Chi-Square feature selection, and Logistic Regression.
</p>

<div align="center">

## 🚀 **Key Features**

</div>

<div align="center">
<table>
<tr>
<td align="center" width="25%">
<b>Data cleaning</b><br/>
<sub>Improve dataset quality and reliability</sub>
</td>
<td align="center" width="25%">
<b>Feature selection</b><br/>
<sub>Improve a machine learning model's performance</sub>
</td>
<td align="center" width="25%">
<b>Feature Engineering</b><br/>
<sub>Improve the performance of machine learning models</sub>
</td>
<td align="center" width="25%">
<b>Model training </b><br/>
<sub>Find patterns and make predictions using Logistic Regression</sub>
</td>
</tr>
</table>
</div>

---

<div align="center">

## 📊 **Dataset Information**

</div>

<div align="center">

<p>
This project uses the <strong>PaySim Financial Transaction Simulation Dataset</strong>, a widely used dataset for fraud detection research.
<a href="https://www.kaggle.com/datasets/ealaxi/paysim1" target="_blank">
PaySim1 – Financial Transactions Dataset (Kaggle)
</p>
 
| **Attribute** | **Details** |
|:---:|:---:|
| **Total Records** | 6,362,620 transactions |
| **Features** | 11 columns (5 float, 3 int, 3 object) |
| **Target Variable** | isFraud (Binary Classification) |
| **Legitimate (Class 0)** | 6,354,407 |
| **Fraudulent (Class 1)** | 8,213 |
| **Memory Usage** | ~534 MB |

</div>

---

<div align="center">

## **Technical Stack**

</div>

<div align="center">

```mermaid
graph LR
    A[Data Collection] --> B[Data Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model Training]
    D --> E[Evaluation]
    E --> F[Prediction]
    
    style A fill:#ff6b6b,stroke:#c92a2a,stroke-width:2px,color:#fff
    style B fill:#4ecdc4,stroke:#0a9396,stroke-width:2px,color:#fff
    style C fill:#ffe66d,stroke:#f5c211,stroke-width:2px,color:#000
    style D fill:#a8dadc,stroke:#457b9d,stroke-width:2px,color:#000
    style E fill:#f1faee,stroke:#8ab17d,stroke-width:2px,color:#000
    style F fill:#e63946,stroke:#a4161a,stroke-width:2px,color:#fff
```

</div>
<br>

<h3>Description of Each Step</h3>

<ul>
  <li><strong>Data Collection:</strong> Importing the financial transactions dataset from a publicly available source.</li>
  
  <li><strong>Data Preprocessing:</strong> Cleaning missing values, encoding categorical features, and transforming numerical fields for consistency.</li>
  
  <li><strong>Feature Engineering:</strong> Selecting impactful variables such as transaction amount, current balance, and old balance to improve model performance.</li>
  
  <li><strong>Model Training:</strong> Training a Logistic Regression model with optimized parameters on 80% of the dataset.</li>
  
  <li><strong>Evaluation:</strong> Measuring model accuracy, F1-score, and analyzing confusion matrix for fraud vs. non-fraud performance.</li>
  
  <li><strong>Prediction:</strong> Using the trained model to predict whether future transactions are fraudulent.</li>
</ul>

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
