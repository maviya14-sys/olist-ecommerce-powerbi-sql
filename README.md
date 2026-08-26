# Olist E-Commerce Executive Overview

## Project Overview

This project presents an interactive E-Commerce Executive Overview Dashboard built using Microsoft Power BI, supported by SQL-based data preparation and analysis.

The dashboard analyzes Olist e-commerce performance across sales, products, categories, customers, logistics, reviews, payments, sellers, and geographic performance.

The project combines SQL-based data preparation with Power BI data modeling, DAX measures, interactive visuals, KPIs, maps, charts, tables, filters, and drill-through analysis.

---

## Dashboard Preview

### 📊 Full 9-Page Power BI Dashboard

[**👉 Open Full 9-Page Dashboard in Browser**](https://docs.google.com/gview?embedded=1&url=https://github.com/maviya14-sys/olist-ecommerce-powerbi-sql/raw/refs/heads/main/E-Commerce%20Executive%20Overview.pdf)

The complete 9-page Power BI dashboard is available as a PDF.

Click the link above to view the complete dashboard directly in the browser.

---

## Dashboard Pages

### 1. Overview — Executive Dashboard

Provides a high-level business overview including:

- Total Orders
- Total Revenue
- Revenue Trend
- Orders by Month
- Top Categories by Revenue
- Revenue by State
- Order Status Share
- Interactive Filters

### 2. Sales Trends

Analyzes sales and revenue trends using:

- Revenue vs Last Year
- Rolling 30 Days Revenue
- Revenue YTD
- Category Performance by Year
- Interactive Filters

### 3. Category & Product

Provides category-level analysis through:

- Average Order Value by Category
- Top Categories by Rating
- Category Revenue Share
- Top Categories by Revenue

### 4. Customer Geo

Analyzes geographic customer performance using:

- Revenue by Customer State
- Top Customer States by Revenue
- Top Customer Cities by Revenue
- Customer State and Category Analysis

### 5. Delivery & Logistics

Analyzes delivery performance through:

- Average Delivery Days by Category
- Late Percentage by Customer State
- Late Orders by Month
- On-Time Delivery Performance

### 6. Reviews

Analyzes customer review performance using:

- Rating Distribution
- Average Rating by Late vs On-Time Orders
- Average Rating by Category
- Review-related KPIs

### 7. Payments

Analyzes payment behavior through:

- Payment Type Share
- Average Installments by Payment Type
- Payment Value Trend
- Top Categories by Payment Value

### 8. Seller

Analyzes seller performance using:

- Top Sellers by Revenue
- Revenue by Seller State
- Seller State and Category Analysis
- Seller-level Revenue Performance

### 9. Drill Through

Provides detailed category-level analysis including:

- Category-level KPIs
- Revenue Trend
- Top Customer States by Revenue
- Total Orders
- Total Revenue
- Category Performance

---

## SQL Analysis

SQL was used for data preparation and analytical processing before visualization in Power BI.

The SQL project contains analytical views covering:

- Product Dimension
- Order Fact
- Sales Fact
- Latest Review Fact
- Order-level Payment Summary

These views prepare the data for business intelligence analysis and Power BI reporting.

---

## Data Model

The project integrates multiple Olist datasets including:

- Customers
- Orders
- Order Items
- Products
- Product Categories
- Sellers
- Payments
- Reviews
- Geolocation

The prepared data is modeled in Power BI for interactive business analysis.

---

## Key Business Analysis Areas

The dashboard focuses on:

- Sales Performance
- Revenue Trends
- Order Performance
- Product Categories
- Customer Geography
- Delivery Performance
- Customer Reviews
- Payment Behavior
- Seller Performance
- Business KPIs

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- PostgreSQL
- SQL
- Data Modeling
- Data Visualization
- Business Intelligence

---

## Project Workflow

```text
Olist Data
    ↓
PostgreSQL
    ↓
SQL Data Preparation
    ↓
Analytical Views
    ↓
Power BI Data Model
    ↓
DAX Measures
    ↓
Interactive Dashboard
    ↓
Business Insights
Repository Structure
olist-ecommerce-powerbi-sql/
│
├── README.md
│
├── E-Commerce Executive Overview.pdf
├── E-Commerce Executive Overview.pbix
│
└── Olist_db.sql
Project Objective

The objective of this project is to transform Olist e-commerce data into an executive-level Business Intelligence solution.

The project demonstrates how SQL-based data preparation and Power BI visualization can be combined to analyze sales, customers, products, logistics, payments, sellers, reviews, and overall business performance.

Author

Maviya Khan
