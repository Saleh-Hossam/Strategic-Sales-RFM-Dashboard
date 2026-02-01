# Strategic Sales & RFM Dashboard 📊

## Project Overview
This project analyzes sales performance and customer behavior to help
business stakeholders understand revenue trends, identify high-value
customers, and detect operational inefficiencies.

The dashboard supports decision-making across executives, operations,
and marketing teams.

---

## Key Insights
- A small percentage of customers generate a large share of total revenue.
- High-value customers with declining recency indicate churn risk.
- Certain regions and shipping modes consistently reduce profitability.

---

## Business Context
This Sales Intelligence Dashboard transforms raw sales data into
actionable insights using a Star Schema data model and advanced visual
logic. It is designed to serve three key stakeholder groups: Executives,
Operations, and Marketing.

---

## 🚀 Dashboard Showcase

### 1. Executive View (Financial Health)
*Focus: Monitoring revenue performance and Year-over-Year (YoY) growth.*
![Executive Dashboard](assets/Executive.gif)

### 2. Operations View (Efficiency & Profit)
*Focus: Identifying operational inefficiencies and profit leaks.*
![Operations Dashboard](assets/Operations.gif)

### 3. Customer View (RFM & Retention)
*Focus: Identifying high-value customers at risk of churn using RFM analysis.*
![Customer Dashboard](assets/Customers.gif)

---

## 🧠 Analytical & Visual Strategy

| Feature | Logic |
| :--- | :--- |
| Profit Analysis | Diverging color logic highlights unprofitable regions. |
| Customer Retention | Recency vs. Lifetime Value scatter plot identifies churn risk. |
| Operational Efficiency | Volume vs. delivery speed analysis detects bottlenecks. |
| Dashboard Design | Structured layout to improve readability and insight discovery. |

---

## 🛠️ Technical Stack
- **Data Modeling:** Star Schema using fact and dimension tables.
- **ETL:** Power Query for data cleaning and transformation.
- **DAX:** Measures for churn risk, shipping performance, and customer metrics.
- **Visualization:** Power BI dashboards with conditional formatting and custom visuals.

### Backend Data Model
![Data Model](assets/Model.png)

---

## 🔄 Data Source
- **Dataset:** Superstore Sales Data (2015–2018)
- **Volume:** ~10,000 records

---

*Author: Saleh Hossam*
