# Mutual Fund Recommendation System & Analytics 📊

> An end-to-end, data-driven mutual fund recommendation system built using **statistical analysis, quantitative scoring, and machine learning**, supported by interactive dashboards and a production-ready web application.

This repository demonstrates how **investment recommendation systems** are designed in real-world fintech and asset management environments — starting from exploratory analytics to deployable recommendation engines.

The project integrates **Python (analytics & modeling)**, **Excel (data validation)**, **Power BI (business dashboards)**, and **Streamlit (deployment)** to deliver investor-ready insights.

---

## 🌐 Live Application

**Deployed Streamlit App:**  
👉 https://mutualfundanalytics.streamlit.app/

The application allows users to:
- Select risk preference (or no preference)
- Compare SIP vs Lumpsum investments
- View ranked fund recommendations
- Understand *why* a fund is recommended
- Export recommendations as CSV

---

## Project Objective

The goal of this project is to **recommend suitable mutual funds** based on:

- Risk profile
- Return expectations
- Historical performance
- Risk-adjusted metrics
- Quantitative ranking logic

The system is built progressively to reflect **industry-style model evolution**.

---

## Recommendation System Approaches

### 1️⃣ Baseline Recommendation (Rule-Based)
- Simple filtering using returns and volatility
- Acts as a benchmark system
- Easy to interpret and explain

📄 Notebook:  
`mutual_fund_baseline.ipynb`

---

### 2️⃣ Z-Score Based Statistical Scoring
- Standardizes financial metrics (returns, Sharpe ratio, volatility)
- Enables fair comparison across funds
- Generates a composite ranking score

📄 Notebook:  
`mutual_fund_zscore.ipynb`

---

### 3️⃣ Machine Learning–Based Ranking (XGBoost)
- Uses gradient boosting for fund ranking
- Learns complex relationships between risk and return features
- Mimics production-style fintech recommendation engines

📄 Notebook:  
`mutual_fund-XGboost.ipynb`

📦 Trained Model:  
`xgboost_fund_ranker.pkl`

---

## 🖥️ Streamlit Recommendation App

📄 File:  
`Python/app.py`

### Key Features:
- Risk-based and risk-agnostic recommendations
- SIP vs Lumpsum comparison
- Quantitative ranking with confidence score
- Return vs Risk visualization
- Mobile-friendly responsive UI
- CSV export for reports
- Clean, explainable, non-hype presentation

---

## 📁 Repository Structure


```
Mutual-Fund-Analysis/
│
├── Excel/
│ ├── top_30_mutual_funds_excel.xlsx
│ └── top_30_mutual_funds_original.xlsx
│
├── Python/
│ ├── app.py # Streamlit recommendation app
│ ├── Mutual Fund Analysis.ipynb # Exploratory & feature analysis
│ ├── mutual_fund_baseline.ipynb # Rule-based recommendation
│ ├── mutual_fund_zscore.ipynb # Statistical scoring model
│ ├── mutual_fund-XGboost.ipynb # ML-based ranking system
│ └── xgboost_fund_ranker.pkl # Trained ML model
│
├── PowerBI/
│ └── mutual_fund_dashboard.pbix # Business dashboard
│
├── requirements.txt
├── .gitignore
├── License
└── README.md
```
---

## 🛠 Tools & Technologies

### Analytics & Modeling
- Python (Pandas, NumPy, SciPy)
- Statistical normalization (Z-score)
- Feature engineering
- XGBoost (ranking model)

### Visualization & Reporting
- Streamlit (interactive web app)
- Plotly (risk-return visualization)
- Power BI (business dashboards)

### Data Handling
- Microsoft Excel (data validation & exploration)

### Deployment & Version Control
- Git & GitHub
- Streamlit Cloud

---

## 📊 Key Metrics Used

- 5-Year Annual Returns
- Sharpe Ratio
- Volatility (Standard Deviation)
- Composite Ranking Score
- Confidence Score (Explainability metric)

---

## 📈 Business Dashboards (Power BI)

Power BI dashboards are designed to:
- Compare fund performance across risk categories
- Identify top-performing funds
- Support investor decision-making
- Translate model outputs into stakeholder-friendly insights

---

## 💼 Business Value

This project simulates real analytics and recommendation systems used in:

- Fintech investment platforms
- Asset management firms
- Wealth advisory products
- Data-driven investment research teams

It demonstrates the ability to:
- Build explainable recommendation systems
- Combine statistics with machine learning
- Design user-facing analytical applications
- Align technical models with business objectives

---

## 👤 Author

**Om Mishra**  
Data Analytics | Machine Learning | Financial Analytics  

🔗 LinkedIn:  
https://www.linkedin.com/in/om-mishra-a62991289  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Final Note

This repository is built as a **portfolio-grade, production-style project**.

It highlights:
- Progressive model development
- Strong analytical reasoning
- Practical ML application in finance
- Clean deployment with Streamlit
- Clear communication of insights

Ideal for roles in **Data Analytics, Business Analytics, Fintech, and Financial ML**.
