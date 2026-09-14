# Procurement Spend & Supplier Performance Analytics Dashboard

## 📊 Project Overview

This project is an interactive Procurement Analytics Dashboard developed using Microsoft Power BI to provide insights into procurement spend, supplier performance, purchase orders, payments, delivery performance, and category-wise purchasing trends.

The dashboard is designed from a procurement business perspective, helping procurement teams monitor spending patterns, evaluate suppliers, identify payment risks, analyze delivery performance, and understand category-level procurement activity.

## Business Problem :

The objective of this project was to provide the procurement team with a centralized view of procurement spend, supplier performance, purchase order status, payment status, and category-wise spending.

In a typical procurement process, data can be spread across Excel files and different operational reports, making it difficult to quickly identify high-spend suppliers, delayed orders, pending payments, or categories with significant procurement spend.
So, I developed a Power BI dashboard to consolidate this information and help procurement managers monitor performance and make data-driven decisions.

## 🎯 Business Objectives

The dashboard helps procurement teams:

- Identify high-spend suppliers and categories
- Monitor supplier delivery performance
- Track outstanding and overdue payments
- Analyze procurement spending trends
- Compare supplier performance
- Identify category-level purchasing patterns
- Support data-driven procurement decisions

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Star Schema

## 🧮 Key DAX Measures

Some of the key measures developed include:

- Total Spend
- Total Orders
- Total Quantity Ordered
- Paid %
- Pending Payment
- Overdue Amount
- Average Lead Time
- On-Time Delivery %
- Cost Savings
- MoM Spend Variance
- YoY Spend Variance

## 📁 Dashboard Pages

### 1. Procurement Overview
Provides a high-level view of:
- Total Procurement Spend
- Purchase Orders
- Quantity Ordered
- Payment Status
- Paid Percentage
- Monthly Spend Trends
- Spend by Supplier
- Spend by Category
- Spend by Location

### 2. Supplier Performance
Analyzes supplier-level performance using:
- On-Time Delivery %
- Total Spend by Supplier
- Average Lead Time
- Purchase Order Count
- Payment Performance
- Supplier Performance Matrix

### 3. Order Status
Provides visibility into:
- Delivered Orders
- Delayed Orders
- Pending Orders
- Cancelled Orders
- Orders by Category
- Orders by Location
- Purchase Order Details

### 4. Payment Analysis
Analyzes:
- Paid vs Pending Payments
- Overdue Amount
- Payment Status by Supplier
- Payment Terms
- Supplier-wise Payment Exposure

### 5. Category Analysis
Provides category-level insights into:
- Spend by Category
- Purchase Orders by Category
- Monthly Spend Trends
- Average Unit Price
- Cost Savings
- Category Contribution to Total Spend

## 📐 Data Model

The dashboard follows a **Star Schema** consisting of:

- Procurement Data – Fact Table
- Suppliers – Supplier Dimension
- Date Table – Date Dimension

Relationships are established between dimension tables and the procurement transaction fact table to support efficient filtering and analysis.

Snapshot/Screenshot of the project :

Overview Preview page : 
![Report page preview](https://github.com/saiprasanna-analytics/Procurement_analytics_report/blob/main/Snapshot%20of%20Overview%20report%20page.png)

