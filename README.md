# Amazon Sales KPI Dashboard (Power BI)

## Project Overview

This project presents a Power BI dashboard that analyzes Amazon product sales data using key business performance indicators. The goal of the dashboard is to track overall sales performance, product demand, and customer engagement through a set of important KPIs.

The dataset contains product level information such as product category, price, customer reviews, shipment details, and order dates. Using this data, the dashboard provides insights into sales trends across different time periods.

## Key KPIs

The Power BI dashboard focuses on the following metrics:

**YTD Sales**
Total sales generated from the beginning of the year up to the current date.

**YTD Reviews**
Total number of customer reviews received during the year.

**YTD Products Sold**
Total number of products sold from the start of the year.

**QTD Sales**
Sales generated in the current quarter.

These KPIs help monitor business performance and track how sales evolve throughout the year.

## Dataset Information

The dataset contains approximately **89,000 records** and includes the following fields:

* Product Category
* Product Description
* Price (Dollar)
* Number of Reviews
* Shipment Information
* Order Date

The order date field is used to compute time based KPIs such as YTD and QTD metrics.

## Tools and Technologies

* Power BI
* Power Query
* DAX Measures
* Excel Dataset

## Dashboard Features

* KPI cards for YTD and QTD metrics
* Time based sales analysis
* Product performance tracking
* Customer review insights
* Interactive filtering and visualization

## Dashboard Preview
<img width="1854" height="1038" alt="Home UI" src="https://github.com/user-attachments/assets/03e099ac-f7c4-449f-b7c8-b25aebbca890" />
<img width="1848" height="1028" alt="Qtr 4 with particular Slicers" src="https://github.com/user-attachments/assets/b81d21f7-e2ba-490a-942a-2757e4d25ca6" />



## Repository Structure

```
amazon-sales-kpi-powerbi-dashboard

Amazon_Sales_KPI_Dashboard.pbix
Amazon_Combined_Data.xlsx
README.md
dashboard_preview/
```

## How to Use

1. Download the `.pbix` file from the repository
2. Open it using **Power BI Desktop**
3. Refresh the dataset if needed
4. Explore the dashboard and interact with filters

## Business Use Case

This dashboard can be useful for:

* Monitoring yearly sales performance
* Tracking customer engagement through reviews
* Understanding product demand trends
* Supporting data driven decision making for e-commerce platforms
