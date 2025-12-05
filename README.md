# 📊 E-Commerce Performance & User Behavior Dashboard

This project presents an end-to-end **Power BI analytical dashboard** built using an **E-commerce dataset from Maven Analytics**. The objective of this dashboard is to analyze sales performance, profitability insights, user behavior, and conversion metrics — all in a unified and interactive report.

This dashboard empowers stakeholders to make data-driven decisions by highlighting **revenue performance, marketing funnel efficiency, customer purchase patterns, profitability, and web session engagement**.

---

## 🚀 Project Objectives

The dashboard is designed to answer critical business questions such as:

- How is the revenue and net revenue performing over time?
- Which products contribute the most to total sales and profitability?
- What is the trend of total orders and refunds?
- What is the operational profitability after accounting for COGS?
- Which traffic sources are leading to better conversions and engagement?
- Which landing pages and product pages drive maximum page views?
- What does the conversion funnel look like from session → views → lead → conversion?

---

## 🛠️ Tech Stack Used

| Component | Tool |
|----------|------|
| BI Tool | **Power BI Desktop** |
| Data Modeling | **DAX (40+ custom measures)** |
| Data Transformation | **Power Query** |

---

## 📂 Dataset Source
- ✔ Dataset Provider — **Maven Analytics**
- ✔ Dataset Type — Public E-commerce performance dataset

---

## 📌 Dashboard Pages Overview

### 🔹 1. **E-Commerce Performance – Overview**
This report page focuses on business performance and revenue KPIs.

**Key Metrics**
- Total Revenue: **$1.94M**
- Net Revenue: **$1.85M**
- Total Orders: **32K**
- Average Order Value: **$60**
- Refund Amount: **$85.34K**

**Highlighted Visuals**
- Monthly Sales Trend
- Orders Trend by Year
- Refund Trend by Year
- Top Selling Products (Bar Chart)
- Traffic Distribution by Source (Donut Chart)
- Slicers for YoY, MoM, Device Type

---

### 🔹 2. **Operational Performance – Profitability Insights**
This page highlights operational costs, profit margins and refund reasons.

**Key Metrics**
- Total COGS: **$722K**
- Gross Profit: **$1.22M**
- Total Orders: **32K**
- Gross Profit Margin %
- Refund Count: **1731**

**Highlighted Visuals**
- Gross Profit Trend by Month
- Profit Contribution by Product (Treemap)
- COGS by Product (Bar)
- Refund Amount by Product (Bar)
- **Funnel Chart – Revenue → COGS → Profit**

---

### 🔹 3. **User Behavior & Conversion Performance**
This page focuses on UX analytics and conversion funnel evaluation.

**Key Metrics**
- Total Sessions: **473K**
- Total Page Views: **1188K**
- Pages per Session: **3**
- Bounce Rate: **44.76%**
- Conversion Rate: **6.83%**

**Highlighted Visuals**
- Traffic by Source
- Sessions by Device
- Conversion Funnel
- Top Landing Pages
- Exit Pages

---

## 🔥 Key Insights & Findings

📌 **Products**
- *The Original Mr. Fuzzy* generated the highest share of revenue and profit.
- Refunds were mostly concentrated around high-selling items.

📌 **Operations**
- COGS is stable relative to revenue trend, ensuring strong profitability margin.
- Profitability peaks show correlation with season-based shopping.

📌 **User Behavior**
- Majority of sessions originate from **gsearch (Google search)**.
- Desktop traffic generated more engaged sessions than mobile.
- Certain landing pages attract large traffic but experience higher exits — improving UX can drive conversion.

📌 **Marketing Funnel**
- Loss in funnel is evident between **views → conversions**, indicating opportunity to optimize CTAs and remarketing campaigns.

---

## 🔧 DAX Highlights
This report includes **40+ custom DAX measures**, covering:
- Time-series calculations (YoY %, MoM %)
- Profitability metrics
- Conversion ratio calculations
- Average order value
- Total sessions & pageview aggregation
- Product-level performance KPIs

---

## 📸 Dashboard Screenshots


| Page | Screenshot |
|------|------------|
| Overview | ![](./images/dashboard-overview.png) |
| Profitability Insights | ![](./images/dashboard-profitability.png) |
| User Behavior & Conversions | ![](./images/dashboard-user-behavior.png) |

---

## 📈 Business Impact
This dashboard enables business stakeholders to:

✔ Identify top-performing products and seasonal trends  
✔ Optimize marketing channels for highest returns  
✔ Improve conversion funnel using behavioral analytics  
✔ Reduce refunds using product-level refund data  
✔ Prioritize UI/UX improvement on weak landing pages  

---

## 🌱 Future Scope (Enhancements)

Potential improvements that can be added next:
- Predictive modeling for forecasting demand
- Customer segmentation using RFM clustering
- Integration with Power BI Service + automatic refresh
- Alerts & subscriptions for KPI thresholds
- Embedded dashboard for web analytics

---

## 👤 Author

**Gaurav Walwadkar**  
📧 Email: **gaurav.walwadkar31@gmail.com**  
🔗 LinkedIn: **https://www.linkedin.com/in/gaurav-walwadkar/**  
💻 GitHub: **https://github.com/Gaurav31-gw**

---

### ⭐ If you like this project
Feel free to ⭐ star the repository and share feedback.  
Thank you for exploring the E-commerce Performance Dashboard!
