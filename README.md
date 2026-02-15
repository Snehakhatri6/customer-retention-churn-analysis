# customer-retention-churn-analysis
End-to-end Customer Retention Analytics &amp; Churn Prediction project using SQL, Python, and Machine Learning. Includes KPI analysis, revenue impact assessment, and threshold-optimized churn modeling (ROC-AUC: 0.83).
# Customer Retention Analytics & Churn Prediction System

## 📌 Business Problem

A telecom company is experiencing a high customer churn rate, directly impacting revenue growth and retention strategy effectiveness.

The objective of this project is to:
- Identify key churn drivers
- Quantify revenue at risk
- Build a predictive model to flag high-risk customers
- Provide actionable business recommendations

---

## 📊 Key Business Insights

- Overall churn rate: **25.58%**
- Revenue at risk: **30.53% of total monthly revenue**
- Month-to-month contracts show **42.71% churn**
- First-year customers (0–12 months) show **47.68% churn**
- High-paying customers are more likely to churn

👉 Churn is concentrated among early-stage, flexible-contract customers.

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- SQL (SQLite)
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

---

## 🧠 Analytical Approach

### 1️⃣ SQL-Based KPI Analysis
- Overall churn rate calculation
- Revenue impact assessment
- Churn segmentation by contract type
- Churn segmentation by tenure group

### 2️⃣ Exploratory Data Analysis
- Contract-based churn patterns
- Tenure-based churn distribution
- Revenue contribution analysis

### 3️⃣ Machine Learning Modeling

Baseline Model:
- Logistic Regression

Model Performance:
- ROC-AUC Score: **0.83**
- Default recall (churn): 52%

Threshold Optimization:
- Adjusted decision threshold from 0.5 → 0.35
- Improved churn recall from **52% → 71%**
- Reduced missed churners significantly

Model Comparison:
- Compared Logistic Regression vs Random Forest
- Logistic Regression selected due to better recall and business alignment

---

## 📈 Key Visualizations

- Churn Rate by Contract Type
- Churn Rate by Tenure Group
- ROC Curve
- Top Feature Importance Drivers
- Revenue at Risk Distribution

---

## 💡 Business Recommendations

- Focus retention efforts on first-year customers
- Incentivize migration from month-to-month to annual contracts
- Proactively engage high-value customers
- Implement risk-based retention campaigns using churn probability scoring

---

## 🚀 Project Outcome

This project demonstrates how combining SQL analytics with machine learning can transform raw customer data into actionable retention strategies that directly impact revenue stability.

---

## 📎 Repository Structure

- `Customer_Retention_Analytics.ipynb` → Full analysis notebook
- Visual outputs for reporting
- Model training and evaluation
