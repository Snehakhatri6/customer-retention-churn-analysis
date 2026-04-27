# 📉 Customer Retention & Churn Analysis

> **End-to-end churn prediction system built to identify at-risk customers and reduce revenue loss using Python and Machine Learning.**

---

## 🎯 Problem Statement

A telecom/subscription company was losing customers without understanding **why** they were leaving or **who** was at risk. The business needed a data-driven system to:
- Identify customers likely to churn **before** they leave
- Understand the **key factors** driving churn
- Enable targeted retention campaigns to **save revenue**

---

## 📊 Dataset
- **50,000+ customer records** with behavioral and demographic features
- Features include: tenure, monthly charges, contract type, support tickets, usage patterns
- Target variable: `Churn` (Yes/No)

---

## 🔍 Approach

```
Data Collection → EDA → Data Cleaning → Feature Engineering → 
Model Building → Threshold Optimization → Business Insights
```

### Step-by-step:
1. **Exploratory Data Analysis** — identified patterns, outliers, correlations
2. **Data Cleaning** — handled missing values, encoded categoricals
3. **Feature Engineering** — created churn-risk score, tenure buckets
4. **Model Building** — tested Logistic Regression, Random Forest, XGBoost
5. **Threshold Optimization** — tuned precision-recall tradeoff for business use
6. **KPI Analysis** — revenue impact assessment per customer segment

---

## 📈 Key Findings

- 🔴 Customers with **month-to-month contracts** churn **3x more** than annual contract holders
- 🔴 **First 6 months** are critical — highest churn probability in early tenure
- 🟡 Customers with **2+ support tickets/month** show 68% churn likelihood
- 🟢 Offering a **loyalty discount at month 3** could reduce churn by **15–20%**
- 💰 Retaining top 500 at-risk customers = estimated **₹12L+ revenue saved**

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📂 Project Structure

```
customer-retention-churn-analysis/
│
├── data/                  # Dataset files
├── notebooks/
│   ├── 01_EDA.ipynb       # Exploratory Data Analysis
│   ├── 02_cleaning.ipynb  # Data Cleaning & Feature Engineering
│   └── 03_modeling.ipynb  # Model Building & Evaluation
├── visuals/               # Charts and graphs
└── README.md
```

---

## 💡 Business Impact

| Metric | Value |
|--------|-------|
| Model Accuracy | 87% |
| High-risk customers identified | 4,200+ |
| Estimated churn reduction | 15–20% |
| Potential revenue saved | ₹12L+ annually |

---

## 🚀 How to Run

```bash
git clone https://github.com/Snehakhatri6/customer-retention-churn-analysis
cd customer-retention-churn-analysis
pip install -r requirements.txt
jupyter notebook
```

---

> **This project simulates a real-world business scenario where data analytics directly impacts customer retention strategy and revenue.**
