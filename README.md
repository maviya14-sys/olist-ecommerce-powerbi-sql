# Olist E-Commerce Executive Overview

## Project Overview

This project presents an interactive E-Commerce Executive Overview Dashboard built using Microsoft Power BI, supported by SQL-based data preparation and analysis.

The dashboard analyzes Olist e-commerce performance across sales, products, categories, customers, logistics, reviews, payments, sellers, and geographic performance.

The project combines SQL-based analytical views with Power BI data modeling, DAX measures, interactive visuals, KPIs, maps, charts, tables, slicers, and drill-through analysis.

---

## Dashboard Preview

📊 **[View Full 9-Page Dashboard PDF](./Dashboard_Preview/E-Commerce_Executive_Overview.pdf)**

The PDF contains the complete Power BI dashboard including all report pages.

---

## Dashboard Pages

### 1. Overview — Executive Dashboard

Provides a high-level business overview including:

- Total Orders
- Total Revenue
- Revenue Trend
- Orders by Month
- Top 10 Categories by Revenue
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

- AOV vs Orders by Category
- Top 10 Categories by Rating
- Category Revenue Share
- Top 20 Categories

### 4. Customer Geo

Analyzes geographic customer performance using:

- Revenue by Customer State
- Top 10 Customer States by Revenue
- Top 10 Customer Cities by Revenue
- Customer State × Category Analysis

### 5. Delivery & Logistics

Analyzes delivery performance through:

- Average Delivery Days by Category
- Late Percentage by Customer State
- Late Orders by Month
- Total Orders
- Logistics Performance

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

- Top 10 Sellers by Revenue
- Revenue by Seller State
- Seller State × Category Analysis
- Seller-related KPIs

### 9. Drill Through

Provides detailed category-level drill-through analysis including:

- Category Title
- Revenue Trend
- Top Customer States by Revenue
- Total Orders
- Total Revenue
- Category-level KPIs

---

## SQL Analysis

SQL was used to prepare analytical views for the Power BI dashboard.

The SQL project includes the following business intelligence views:

### Product Dimension

`bi_dim_product`

Combines product information with the English product category translation and calculates product volume.

### Latest Review Fact

`bi_fact_review_latest`

Selects the latest review record for each order.

### Order Fact

`bi_fact_order`

Combines order and customer information and calculates:

- Purchase Date
- Purchase Month
- Delivered Date
- Estimated Delivery Date
- Delivery Days
- Late Order Flag
- Customer Information
- Customer Geography

### Sales Fact

`bi_fact_sales`

Combines:

- Order Items
- Orders
- Customers
- Products
- Reviews
- Payments
- Sellers

This creates a consolidated analytical dataset for Power BI.

### Payment Summary

`bi_payments_order`

Aggregates payment information at the order level including:

- Order Payment Value
- Payment Installments
- Primary Payment Type

---

## Data Model

The project integrates multiple Olist datasets covering:

- Customers
- Orders
- Order Items
- Products
- Product Categories
- Sellers
- Payments
- Reviews
- Geolocation

The SQL layer prepares the data before it is analyzed and visualized in Power BI.

---

## Key Business Analysis Areas

The dashboard focuses on:

- Sales Performance
- Revenue Trends
- Product Categories
- Customer Geography
- Delivery Performance
- Customer Reviews
- Payment Behavior
- Seller Performance
- Order Performance
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
Olist Raw Data
      ↓
PostgreSQL
      ↓
SQL Data Preparation
      ↓
Business Intelligence Views
      ↓
Power BI Data Model
      ↓
DAX Measures
      ↓
Interactive Dashboard
      ↓
Business Insights

## Author
Maviya Khan
