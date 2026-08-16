# Sales Performance Dashboard — Excel Analytics Project

## Overview

This project is an **Excel-based Sales Performance Dashboard** built from a 500-record sales dataset. It combines structured sales data, PivotTables, and interactive dashboard charts to analyze revenue performance across time, regions, customer segments, managers, categories, and products.

The workbook is provided as `Sales_Target_performance.xlsm` and contains three main worksheets:

- **Dashboard** — visual summary of sales performance and business KPIs.
- **Data** — source sales dataset containing 500 orders and 18 fields.
- **Pivot** — PivotTables that aggregate the source data and feed the dashboard.

## Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | ₹71,178,664 |
| Total Target | ₹41,693,329 |
| Overall Achievement | 170.72% |
| Total Orders | 500 |
| Units Sold | 2,716 |

## Dashboard Analysis

The dashboard provides the following views:

- **Monthly Sales Trend** — compares actual sales with monthly targets.
- **Sales by Region** — compares performance across East, North, South, and West.
- **Sales by Manager** — evaluates sales contribution by manager.
- **Category Contribution** — shows the contribution of each product category.
- **Top Products by Sales** — ranks products based on sales value.

## Major Findings

- Overall sales of **₹71.18M** exceeded the total target of **₹41.69M**.
- Overall sales achievement is approximately **170.72%** of target.
- **Electronics** generated the highest category sales at approximately **₹20.51M**.
- **Wholesale** was the largest customer segment at approximately **₹26.58M**.
- **East** was the highest-performing region at approximately **₹18.67M**.
- **Manager_1** contributed the highest sales among managers at approximately **₹10.98M**.
- Among the products shown in the workbook, **Headphones** generated the highest sales at approximately **₹10.37M**.

## Dataset

The source table is named `tblSales`.

Main fields include:

`Date`, `Month`, `Order ID`, `Region`, `State`, `City`, `Sales Manager`, `Salesperson`, `Channel`, `Customer Segment`, `Product Category`, `Product Name`, `Units Sold`, `Unit Price`, `Sales Amount`, `Target Sales`, `Lead ID`, and `_Year_`.

## Tools & Technologies

- Microsoft Excel
- Excel Tables
- PivotTables
- PivotCharts
- Slicers / dashboard controls
- Excel formulas and calculated metrics

## How to Use

1. Open `Sales_Target_performance.xlsm` in Microsoft Excel.
2. Go to the **Dashboard** sheet for the visual summary.
3. Use the available filters/slicers to explore the dashboard.
4. Open the **Pivot** sheet to inspect the underlying aggregations.
5. Open the **Data** sheet to review or append source records.
6. Refresh the PivotTables after changing the source data.

> **Note:** Because the workbook is macro-enabled (`.xlsm`), open it in Microsoft Excel rather than a basic spreadsheet viewer. If Excel displays a security prompt, only enable content/macros if you trust the workbook source.

## Project Structure


Sales-Performance-Dashboard/
│
├── Sales_Target_performance.xlsm
├── README.md
└── Screenshot 2026-08-17 040919.png


## Purpose

The project demonstrates how raw sales data can be transformed into business-ready insights using Excel analytics. It is suitable as a portfolio project for demonstrating skills in **Excel, data analysis, PivotTables, dashboard design, KPI reporting, and business intelligence**.
