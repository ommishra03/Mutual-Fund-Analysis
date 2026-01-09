# Mutual Fund Recommendation System & Analytics 📊🤖

> An end-to-end, data-driven mutual fund recommendation system built using statistical analysis and machine learning models, supported by business dashboards.

This repository demonstrates how **investment recommendation systems** are developed in real-world fintech and asset management environments — starting from baseline analytics to advanced ML-based scoring.

The project combines **Python (analytics + ML)**, **Excel (data validation)**, and **Power BI (business storytelling)** to deliver investor-ready insights.

---

## 🚀 Project Objective

The primary goal of this project is to **recommend suitable mutual funds** based on:
- Risk profile
- Return expectations
- Historical performance
- Risk-adjusted metrics

The system evolves progressively:
1. Baseline analytical recommendations  
2. Statistical normalization (Z-score)  
3. Machine Learning–based ranking (XGBoost)

---

## 🧠 Recommendation System Approaches

### 1️⃣ Baseline Recommendation (Rule-Based)
- Simple filtering using returns and volatility
- Acts as a benchmark system
- Easy to interpret and explain

📄 Notebook:  
`mutual_fund_baseline.ipynb`

---

### 2️⃣ Z-Score Based Scoring Model
- Standardizes multiple financial metrics
- Enables fair comparison across funds
- Generates composite fund scores

📄 Notebook:  
`mutual_fund_zscore.ipynb`

---

### 3️⃣ Machine Learning–Based Recommendation (XGBoost)
- Uses gradient boosting for fund ranking
- Learns complex relationships between risk and returns
- Mimics production-style fintech recommendation engines

📄 Notebook:  
`mutual_fund-XGboost.ipynb`

---

## 📁 Repository Structure

```
Mutual-Fund-Analysis/
│
├── Excel/
│ ├── raw_data.xlsx
│ ├── cleaned_data.xlsx
│ └── exploratory_analysis.xlsx
│
├── Python/
│ ├── Mutual Fund Analysis.ipynb # Exploratory & feature analysis
│ ├── mutual_fund_baseline.ipynb # Rule-based recommendation
│ ├── mutual_fund_zscore.ipynb # Statistical scoring model
│ └── mutual_fund-XGboost.ipynb # ML-based recommendation system
│
├── PowerBI/
│ └── mutual_fund_dashboard.pbix
│
├── .gitignore
└── README.md
```

---

## 🛠 Tools & Technologies

### Analytics & Machine Learning
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Statistical normalization (Z-score)
- Feature engineering & model evaluation

### Business Analysis
- Microsoft Excel (data validation, pivots)

### Visualization & Reporting
- Power BI (interactive dashboards, KPIs)

### Version Control
- Git & GitHub

---

## 📊 Key Metrics Used

- Absolute returns
- CAGR
- Volatility & standard deviation
- Risk-adjusted scoring
- Composite fund ranking

---

## 📈 Dashboards & Business Insights

Power BI dashboards are designed to:
- Compare fund performance across categories
- Highlight top-performing and high-risk funds
- Support investor and stakeholder decision-making
- Translate model outputs into business-friendly insights

---

## 🎯 Business Value

This project simulates real analytics and ML work performed in:
- Fintech investment platforms
- Asset management firms
- Wealth advisory solutions
- Data-driven investment research teams

It demonstrates the ability to:
- Build explainable recommendation systems
- Combine statistics with machine learning
- Align technical models with business goals

---

## 👤 Author

**Om Mishra**  
Data Analytics | Machine Learning   

🔗 LinkedIn: https://www.linkedin.com/in/om-mishra-a62991289  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Final Note

This repository is structured as a **portfolio-grade, production-style project**.
It highlights:
- Progressive model development
- Strong analytical reasoning
- Practical ML application in finance
- Clear communication of insights

Ideal for roles in **Data Analytics, Business Analytics, and Fintech ML**.
