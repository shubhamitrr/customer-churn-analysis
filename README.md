# 📊 Customer Churn Analysis & Customer Intelligence

An end-to-end Data Analytics project focused on analyzing customer churn, subscription behavior, revenue impact, and customer support interactions for an OTT subscription platform.

The project integrates customer, subscription, and support data from a relational SQLite database and uses SQL and Python for data extraction, data cleaning, feature engineering, exploratory data analysis, visualization, and business insights.

---

## 🎯 Business Objective

Customer retention is a major challenge for subscription-based businesses.

The objective of this project is to:

- Analyze customer churn behavior
- Identify high-risk customer segments
- Analyze churn by subscription plan and contract type
- Analyze state-wise and monthly churn trends
- Measure revenue and CLTV impact of churn
- Analyze customer support escalations
- Generate actionable recommendations for customer retention

---

## 🗄️ Database Structure

The project uses a SQLite database containing three main tables:

### 👤 `db_customer`

Contains customer demographic and profile information.

- `customerid`
- `name`
- `country`
- `state`
- `gender`
- `dob`
- `interests`
- `pincode`

### 📋 `db_subscription`

Contains customer subscription and billing information.

- `customerid`
- `subscription_start_date`
- `subscription_type`
- `renewal_date`
- `plan_type`
- `contract_type`
- `cancellation_date`
- `cancellation_reason`
- `monthly_charges`
- `cltv`
- `churn_score`

### 🎧 `db_support`

Contains customer support and complaint information.

- `customerid`
- `complaint_date`
- `escalations`
- `csat_score`
- `comment`

---

## 🛠️ Tech Stack

- **Python**
- **SQL**
- **SQLite**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔄 Project Workflow

```text
SQL Database
      ↓
Data Extraction
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Business Insights
      ↓
Retention Recommendations
```

---

## 📌 Analysis Performed

### Customer Churn Analysis
- Overall churn rate
- Retention rate
- Churn by plan type
- Churn by contract type
- State-wise churn
- Monthly churn trend

### Customer Analysis
- Average customer tenure
- Churn score
- Churn risk segmentation
- Customer behavior analysis

### Revenue Analysis
- Total revenue
- Revenue lost due to churn
- CLTV lost due to churn
- Revenue loss percentage
- ARPU analysis

### Support Analysis
- Escalation rate
- Average complaints per customer
- Support escalation vs churn correlation
- CSAT analysis

---

## 📈 Key Metrics

| KPI | Result |
|---|---:|
| Churn Rate | 28.6% |
| Retention Rate | 71.4% |
| Average Customer Tenure | 1,451 days |
| ARPU | ₹18.8 |
| Total Revenue | 395 |
| Revenue Lost to Churn | 74 |
| CLTV Lost | 2,047 |
| Revenue Loss | 18% |
| Monthly Churn | 55.6% |
| Annual Churn | 8.3% |

---

## 🔍 Key Insights

- The overall customer churn rate was **28.6%**, while the retention rate was **71.4%**.
- The **Basic subscription plan** contributed the highest number of churned customers.
- The highest churn activity was observed in **September 2024**.
- **Karnataka** was identified as the most affected state in the analysis.
- Monthly contracts showed significantly higher churn compared with annual contracts.
- Customer churn resulted in measurable **revenue and CLTV loss**.
- Customers with **High and Medium churn risk** should be prioritized for retention activities.
- Support escalations were analyzed to understand their relationship with customer churn.

---

## 💡 Business Recommendations

Based on the analysis:

1. Investigate the reasons behind higher churn in Karnataka.

2. Review pricing, customer complaints, and technical issues affecting Basic-plan customers.

3. Encourage monthly customers to migrate to annual contracts through suitable offers.

4. Prioritize High and Medium churn-risk customers for retention campaigns.

5. Monitor customer complaints and support escalations.

6. Use CLTV to prioritize high-value customers for retention activities.

7. Develop targeted retention strategies for customers showing early signs of churn.

---

## 📊 Visualizations

The project visualizations are available in the `visualizations` folder.

### Available Visualizations

- Churn by Plan Type
- Churn by State
- Monthly Churn Trend
- Correlation Heatmap

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── README.md
├── customer_churn.db
├── exported_churn.csv
├── python_project.ipynb
│
└── visualizations/
    ├── churn_by_plan_type.png
    ├── churn_by_state.png
    ├── heatmap.png
    └── monthly_churn_trend.png
```

---

## 🚀 Skills Demonstrated

- SQL Database Connectivity
- SQL Queries
- Python for Data Analytics
- Pandas & NumPy
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- GroupBy & Aggregation
- Data Visualization
- Matplotlib & Seaborn
- Customer Churn Analysis
- Revenue Analysis
- Business Insight Generation

---

## 🎓 Key Learning

This project helped me understand the complete Data Analytics workflow — from extracting data from a relational database to cleaning, analyzing, visualizing, and converting data into actionable business insights.

The key learning from this project was:

> **Data Analytics is not just about writing code or creating charts; it is about using data to answer business questions and support better decisions.**

---

## 👨‍💻 Author

**Shubham Kumar**

B.Tech – Information Technology  
Aspiring Data Analyst

**Skills:** SQL | Python | Pandas | NumPy | Excel | Power BI | Data Visualization
