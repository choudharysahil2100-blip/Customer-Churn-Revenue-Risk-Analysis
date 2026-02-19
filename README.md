# 📊 Customer Churn & Revenue Risk Analysis

## 🚀 Project Overview

This project analyzes telecom customer churn behavior and predicts high-risk customers using Machine Learning.  
It combines **SQL, Python, and Power BI** to generate business insights and identify revenue at risk.

The goal is to help businesses reduce churn and protect recurring revenue through data-driven decisions.

---

## 🛠 Tech Stack

- SQL (MySQL) – Data cleaning and KPI analysis
- Python (Pandas, NumPy, Scikit-learn) – Churn prediction model
- Power BI – Interactive dashboards
- GitHub – Version control & documentation

---

## 📂 Project Structure

Customer-Churn-Revenue-Risk-Analysis/

├── data/
│   ├── telco_clean.csv
│   └── telco_with_predictions.csv
│
├── python/
│   └── churn_model.py
│
├── powerbi/
│   └── churn_dashboard.pbix
│
├── images/
│   ├── executive_overview.png
│   ├── churn_drivers.png
│   └── revenue_risk.png
│
├── requirements.txt
└── README.md

---

## 📈 Key Insights

- Total Customers: **7,043**
- Churn Rate: **26.54%**
- Total Revenue: **$16.06M**
- Revenue at Risk: **$2.86M**

### Major Churn Drivers:
- Month-to-month contracts
- Fiber optic customers
- Low tenure (0–1 year)
- Customers without online security
- High monthly charges

---

## 🤖 Machine Learning Model

- Model Used: Logistic Regression
- Accuracy: ~74%
- Handled class imbalance using `class_weight='balanced'`
- Generated churn probability score for each customer
- Customers segmented into:
  - High Risk (> 75%)
  - Medium Risk (50% – 75%)
  - Low Risk (< 50%)

The model output was exported as:
`telco_with_predictions.csv`

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview
- Total customers
- Churn rate
- Revenue
- Revenue at risk
- Churn breakdown by payment, contract, internet type

### 2️⃣ Churn Drivers
- Churn rate by tenure band
- Churn by monthly charges
- Churn by online security
- Tech support impact

### 3️⃣ Revenue at Risk & High-Risk Segments
- Revenue at risk by contract
- Revenue at risk by tenure
- Revenue at risk by internet service
- Risk segmentation (High / Medium / Low)
- Slicers (Tenure Band / Contract / Internet Service)
- Count of Customer by Risk Segment
- Count of Customer by Contract

  
## ▶️ How to Run the Project

### 1. Install Dependencies

pip install -r requirements.txt

### 2. Run the Model

python python/churn_model.py

### 3. Open Dashboard

Open `powerbi/churn_dashboard.pbix` in Power BI Desktop.

---

## 🎯 Business Impact

This project enables:

- Identification of high-risk customers
- Targeted retention campaigns
- Revenue loss prevention
- Executive-level churn monitoring
- Data-driven customer segmentation

---

## 👨‍💻 Author

Sahil Choudhary  
Business Analyst | Data Analytics Enthusiast

