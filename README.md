# 📊 Sales Report Dashboard

[![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)

An interactive Sales Report built entirely from scratch in Power BI, analyzing product performance, inventory status, revenue trends, and dead stock for a retail store scenario. This was my first Power BI project, focused on exploring a variety of chart types and writing custom DAX measures.

## 📌 Project Overview

The goal of this dashboard is to provide a comprehensive view of retail store performance, focusing on:

* **Revenue Tracking:** Monitoring daily and product-level revenue trends.
* **Inventory Management:** Analyzing current stock levels and identifying dead stock.
* **Product Performance:** Comparing cost, profit, and revenue across products using advanced visuals.

## 💡 Key Business Insights

* **Top Product:** Titan Gaming Chair generated the highest revenue (1690) among all products.
* **Dead Stock:** Titan Gaming Chair and Noise-Cancel Headset had the highest unsold stock (90 and 71 units respectively), signalling overstocking.
* **Revenue Trend:** Daily revenue peaked at 1150 on 12/4/2025 before a sharp drop to 285 on 12/8/2025.
* **Profit vs Cost:** 32" Curved Monitor and Standing Desk Pro showed the highest profit margins relative to unit cost.

## 🖥️ Dashboard Preview

### Page 1 — Sales Overview
<img width="776" height="593" alt="Sales Overview" src="https://github.com/user-attachments/assets/7550214f-5103-4f09-abe7-a9519b8eba11" />

### Page 2 — Product Performance Analysis
<img width="727" height="584" alt="Performace Analyser" src="https://github.com/user-attachments/assets/4c0ee086-ae1a-4ed1-8c9e-e3917cc970d0" />


### Page 3 — Dead Stock Analysis
<img width="770" height="587" alt="Dead Stock " src="https://github.com/user-attachments/assets/22fb82e1-e498-44dc-9174-40d08f3b081a" />


## 🛠️ Tech Stack

* **Tool:** Power BI Desktop
* **Data Modelling:** Power Query (data transformation)
* **Custom Measures:** DAX (calculated columns and measures)
* **Data Source:** Included in repository

## 🔍 DAX Highlights

Custom DAX measures written for this project include:

* `Total Revenue` — aggregated revenue across all transactions
* `Total Current Stock` — sum of remaining inventory per product
* `Profit` — calculated as Revenue minus Cost per product

## 📊 Visuals Used

| Visual | Purpose |
|---|---|
| Pie Chart | Ratio of current stock by product |
| Bar Chart | Top 3 products by revenue |
| Line Chart | Revenue trend over dates |
| Bubble/Scatter Chart | Cost vs Profit vs Revenue analysis |
| Treemap | Dead stock identification |
| KPI Cards | Total stock, units sold, total revenue |

## 🚀 Getting Started

1. **Clone the Repository**
```bash
   git clone https://github.com/bsanghvi78/Sales-Report.git
   cd Sales-report
```

2. **Open the Dashboard**
   * Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   * Open `Sales-Report.pbix` to explore the interactive dashboard

---

## 📁 Repository Structure

* **`Sales-Report.pbix`** — Complete Power BI file with data model, DAX measures, and all report pages
* **`screenshots/`** — Dashboard preview images for all 3 report pages

> 📌 Dataset is embedded within the `.pbix` file and included in this repository.
