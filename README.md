# Data-Analysis-Dashboards
An interactive Excel dashboard built on the **DataCo Supply Chain Dataset**, analyzing over **180,000 orders** across sales, shipping, customers, and products to uncover business insights on performance, delivery, and profitability.
Dashboard Overview <https://github.com/dakxu/Data-Analysis-Dashboards/blob/main/Dashboard.png>

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

- Sales peaked in **2015–2016** before declining in later years.
- **Late deliveries** make up a significant share of total shipments, signaling a logistics bottleneck.
- A small number of **product categories (Fan Shop, Apparel, Footwear)** drive the majority of revenue.
- **Consumer segment** customers contribute the largest share of sales compared to Corporate and Home Office.

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

Daksh




