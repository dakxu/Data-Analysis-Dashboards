# Data-Analysis-Dashboards
An interactive Excel dashboard built on the **DataCo Supply Chain Dataset**, analyzing over **180,000 orders** across sales, shipping, customers, and products to uncover business insights on performance, delivery, and profitability.

## 📊 Overview

This project transforms a large, raw supply chain dataset into a clean, decision-ready dashboard using **PivotTables, PivotCharts, and formulas** in Excel — no external BI tool required.

The dashboard answers key business questions such as:
- How are sales trending month-over-month and year-over-year?
- Which regions and markets generate the most revenue?
- What are the most common payment types and order statuses?
- How is delivery performance split between on-time and late shipments?
- Which products and customer segments drive the most sales?

## 📁 Dataset source
This project uses the **DataCo Smart Supply Chain for Big Data Analysis** dataset, originally published on 
<https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis>

## :camera: Dashboard Overview
<img width="1871" height="715" alt="Dashboard" src="https://github.com/user-attachments/assets/c7f92494-6789-4abf-8ec1-812f618b2c24" />


## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| `DataCoSupplyChainDataset` | Raw dataset — 180,000+ rows, 54 columns covering orders, customers, products, shipping, and sales |
| `Pivot` | PivotTables summarizing sales/quantity by year, region, payment type, delivery status, department, and order status |
| `Dashboards` | Consolidated visual dashboard built from the PivotTables |

## 📈 Dashboard Highlights

The dashboard includes 15+ charts, such as:

- **Yearly Sales Trend** — line chart of total sales by year
- **Monthly Sales Trend** — seasonality view across months
- **Region-wise Sales** — revenue breakdown by market/region
- **Department-wise Sales** — pie chart by department
- **Customer Segment Analysis** — Consumer vs. Corporate vs. Home Office
- **Payment Type Breakdown** — Debit, Credit, Cash, Payment
- **Order Status Overview** — Complete, Pending, Canceled, Suspected Fraud, etc.
- **Shipment Performance** — Advance, Late, On-Time, and Canceled shipments
- **Top 10 Products by Sales**

## 🧠 Key Insights
- Sales were flat 2015–2017 (~$12M/yr each) — the apparent 2018 drop is a data artifact (dataset ends Jan 31, 2018), not a real decline.
- 54.8% of shipments are late, driven by unrealistic SLAs — First Class (1-day promise, ~2-day actual) is late 95% of the time vs. 38% for Standard Class.
- Fan Shop dominates revenue at $17.1M — more than Apparel, Golf, and Footwear combined.
- Consumer segment drives 63% of revenue ($19.1M) vs. Corporate ($11.2M) and Home Office ($6.5M).
- 18.7% of orders are unprofitable (–$3.88M total), though overall margin stays positive at 10.78%.
- Discounting isn't the margin problem — discount rate shows near-zero correlation with profit ratio.
- Europe and LATAM outsell USCA (US/Canada) in total revenue — $10.9M and $10.3M vs. $5.1M.

## 🛠️ Tools & Techniques Used

- Microsoft Excel
- PivotTables & PivotCharts
- Data cleaning and formatting
- Dashboard design principles (layout, color coding, KPI callouts)

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Book1.xlsx` in Microsoft Excel.
3. Navigate to the **Dashboards** sheet to view the interactive dashboard.
4. Use slicers/filters (if included) to explore data by year, region, or segment.

## 📌 Author

Dakxu




