# 📊 Superstore Sales Analysis – Power BI Dashboard

## 📁 Project Overview

This project is part of a Data Analyst Internship Task 2: **Data Visualization and Storytelling**. It uses the **Superstore dataset** to explore and communicate business insights via an interactive Power BI dashboard.

---

## ✅ Objectives

* Clean and prepare Superstore sales data
* Create meaningful and engaging visuals
* Highlight business insights
* Summarize key findings and recommendations in a story format

---

## 🛠 Tools & Technologies

* **Power BI Desktop** (DAX, Power Query)
* Data Source: `Superstore.xlsx`

---

## 🧹 Data Cleaning & Preparation

Performed in Power Query:

* Fixed inconsistent date formats using locale conversion
* Created derived columns:

  * `Year`, `Month`, `Quarter` from `Order Date`
  * `Shipping Delay` = `Ship Date` - `Order Date`
  * `Profit Margin` = `Profit / Sales`
* Cleaned text columns (Customer Name, State, Product Name)
* Sorted `Month-Year` column using numeric `MonthNumber`

---

## 📊 Visualizations

| Visual Type          | Title                                      | Purpose                  |
| -------------------- | ------------------------------------------ | ------------------------ |
| KPI Cards            | Sales, Profit, Avg. Shipping Delay, Margin | Summary Metrics          |
| Bar Chart            | Top 10 Products by Sales                   | Product Performance      |
| Stacked Column Chart | Sales by Segment and Region                | Segment Analysis         |
| Line Chart           | Monthly Sales Trend                        | Time Series Analysis     |
| Donut Chart          | Sales Contribution by Category             | Product Category Split   |
| Scatter Plot         | Impact of Discount on Profitability        | Discount Strategy Review |

---

## 📖 Executive Summary

* Technology is the most profitable category.
* Discounts over 30% often reduce profitability.
* Q4 sees consistent sales spikes.
* Top 10 products dominate revenue share.

---

## 💡 Business Recommendations

* Focus promotions on profitable categories like Technology.
* Limit deep discounting on loss-generating products.
* Prioritize logistics improvements in low-profit states.
* Prepare for Q4 with top-seller stocking strategies.

---

## 📂 Repository Contents

* `Superstore.pbix` – Power BI report file
* `Screenshots/` – Visual snapshots
* `README.md` – This documentation
* `Summary Slide` – Executive overview page inside dashboard

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Explore visuals and filters
3. Read the Summary Slide for final takeaways

---

> Created as part of the Data Analyst Internship: Task 2 – Visualization & Storytelling
