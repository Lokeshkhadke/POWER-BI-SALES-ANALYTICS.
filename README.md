# Sales Analytics Dashboards - Power BI

**A multi-faceted view of sales performance, customer insights, and product trends to drive strategic growth.**

![Power BI](https://img.shields.io/badge/Platform-Power%20BI-yellow) ![DAX](https://img.shields.io/badge/Logic-DAX-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen) ![Dashboard](https://img.shields.io/badge/Contains-4%20Dashboards-blue)

This repository contains a comprehensive **Power BI Sales Analytics** suite designed to provide a 360-degree view of business performance. Through four interconnected dashboards, it enables data-driven decision-making for sales managers, marketing teams, and executives.

---

## 📊 Dashboard Portfolio

| Dashboard | Purpose | Key Metrics |
| :--- | :--- | :--- |
| **📈 Sales Performance** | Track overall business health and progress towards goals. | Total Revenue, YTD Sales, Profit Margin, Sales Targets vs. Actuals |
| **👥 Customer Analysis** | Understand customer demographics and purchasing behavior. | Customer Count, New vs. Returning, Sales by Region/Cohort |
| **📦 Product Analysis** | Identify top-performing products and category trends. | Sales by Product/Category, Top/Bottom N, Quarterly Performance |
| **🎯 Executive Summary** | High-level overview of KPIs for strategic decision-making. | YTD Revenue, YoY Growth, Profitability, Key Highlights |

---

## 🗂️ Project Contents

- **`Sales Dashboard.pbix`** - The main Power BI file.
- **`Sales Dashboard.pdf`** - A static PDF export for quick review.
- **`Sample - Superstore.xlsx`** - The sample dataset used.
- **Screenshots** - Visual previews of each dashboard.

---

## 🚀 Getting Started

1.  **Download** the `Sales Dashboard.pbix` file.
2.  Open it using **Power BI Desktop** (Free download).
3.  Use the navigation pane to switch between dashboards.
4.  Interact with slicers, filters, and click on visuals to explore the data.

*All data is embedded—no external connections required.*

---

## ⚙️ Technical Architecture & Skills Demonstrated

- **Data Modeling:** Built a robust star schema data model for optimal performance.
- **Power Query (M):** Performed ETL to clean, reshape, and prepare the raw data.
- **DAX (Data Analysis Expressions):** Created advanced calculated measures:
    - **YTD Sales:** `TOTALYTD(SUM(Sales[Amount]), 'Date'[Date])`
    - **YoY Growth:** `[Total Sales] - CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date]))`
    - **Profit Margin:** `DIVIDE([Total Profit], [Total Sales])`
- **Data Visualization:** Designed intuitive and visually coherent reports.

---

## 💡 Key Business Insights

This analysis empowers stakeholders to:
- **Identify Top Markets & Products:** Pinpoint which regions and product categories are driving revenue and profit.
- **Monitor Sales Targets:** Track performance against goals in real-time.
- **Understand Customer Segments:** Analyze buying patterns to improve retention and marketing.
- **Optimize Inventory:** Identify slow-moving products to manage stock levels effectively.

---

## 🏆 Best Practices Highlighted

- **Modular Design:** Separate dashboards for different user roles improve usability.
- **Consistent Design Language:** Unified color scheme and layout for a professional look.
- **Interactive Elements:** Tooltips, drill-through, and cross-filtering for deep exploration.
- **Performance Optimization:** Efficient DAX and data model ensure fast load times.

---

## 👨‍💻 Author

**Lokesh K**
MSc Data Science, University of Surrey (2024–2025)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/lokeshkhadke)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?style=flat&logo=gmail)](mailto:lkhadke16@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/Lokeshkhadke)

---

**⭐ If this sales analytics suite provides valuable insights, please consider giving this repository a star!**
