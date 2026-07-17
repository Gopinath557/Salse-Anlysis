# E-Commerce Sales Dashboard (Tableau)

## Overview
Interactive Tableau dashboard for analyzing e-commerce sales.

## KPIs
- Total Revenue
- Total Orders
- Average Customer Rating
- Average Delivery Days

## Visualizations
- Revenue Trend
- Revenue by Category
- Revenue by Region
- Payment Method Distribution
- Revenue vs Discount
- Customer Rating Distribution
- Top Categories

## Filters
- Order Date
- Region
- Product Category
- Payment Method

## Calculated Fields
- Total Revenue = SUM([Revenue])
- Total Orders = COUNT([Order ID])
- Avg Rating = AVG([Customer Rating])
- Avg Delivery Days = AVG([Delivery Days])
- Average Order Value = SUM([Revenue])/COUNT([Order ID])

## Technologies
- Tableau Desktop / Tableau Public
- CSV Dataset

## How to Build
1. Open Tableau.
2. Connect to `ecommerce_sales_analytics_5000.csv`.
3. Create the calculated fields above.
4. Build each worksheet and assemble the dashboard.
