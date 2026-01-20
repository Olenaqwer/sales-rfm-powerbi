# 📊 Sales & Customer RFM Analysis (Power BI)

This project demonstrates an end-to-end sales and customer analysis using Power BI, 
with a strong focus on revenue, profit, and RFM customer segmentation.

The goal is to transform raw transactional data into actionable business insights 
that support customer retention and profitability decisions.

---

## 🔍 Business Questions
- How is revenue and profit distributed over time?
- Which customer segments generate the most revenue and profit?
- Who are the most valuable customers?
- Which customer segments are at risk of churn?

---

## 📈 Dashboards Overview

### 1️⃣ Revenue Metrics Dashboard
![Revenue Dashboard](dashboards/Sales_Revenue_Dashboard.png)

**Key KPIs:**
- Total Revenue
- Total Profit
- Total Orders
- Average Order Value (AOV)

**Insights:**
- Monthly revenue and profit trends
- Product category performance
- Top orders by profit and profit margin

---

### 2️⃣ Customers & RFM Segmentation Dashboard
![Customers Dashboard](dashboards/Customers_RFM_Dashboard.png)

**Customer Metrics:**
- Total Customers
- Average Orders per Customer
- ARPU

**RFM Segmentation:**
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Lost
- Hibernating
- New Customers

**Advanced Analysis:**
- Revenue contribution (%) by RFM segment
- Profit contribution (%) by RFM segment
- Comparison of high-revenue vs high-profit segments

---

## 🧠 RFM Methodology

- **Recency**: Days since last order
- **Frequency**: Number of unique orders per customer
- **Monetary**: Total profit per customer

Each metric is scored using percentile-based logic (1–5),
and customers are grouped into business-friendly RFM segments.

---

## 🛠 Tools & Technologies
- Power BI
- DAX (CALCULATE, ALLEXCEPT, PERCENTILEX)
- Data Modeling
- Business Analytics

---

## 📌 Key Business Insights
- Champions generate the largest share of profit despite representing a smaller portion of customers
- At Risk and Lost customers contribute revenue but show low profitability
- Loyal customers present strong potential for upsell and retention strategies

---

## 📂 Files
- `Sales_RFM_Analysis.pbix` – Power BI dashboard
- `/dashboards` – dashboard screenshots
- `/docs` – methodology documentation

---

## 👩‍💻 Author
Created by **Olenka**  
