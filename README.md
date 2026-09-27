# Retail Store Sales SQL Analysis

## Project Overview

This project focuses on analyzing retail store sales data using SQL to generate meaningful business insights.

The analysis covers customer behavior, sales performance, product and category revenue, payment methods, salesperson performance, and monthly sales trends.

## Business Objectives

The project answers key business questions such as:

- Which city generates the highest sales?
- Which product category generates the highest revenue?
- Which salesperson generates the maximum revenue?
- Which payment mode is most preferred?
- Which customers have placed multiple orders?
- What are the monthly sales trends?
- Which products generate the highest sales?

## Dataset

The project uses a single table named `store_sales` containing retail transaction data.

Key fields include:

- Order Date
- Customer Name
- Gender
- Age
- City
- State
- Product Name
- Category
- Quantity
- Unit Price
- Discount
- Total Amount
- Payment Mode
- Salesperson

## SQL Concepts Used

- CREATE DATABASE
- CREATE TABLE
- INSERT
- SELECT
- WHERE
- ORDER BY
- LIMIT
- DISTINCT
- LIKE
- BETWEEN
- IN
- Aggregate Functions
- GROUP BY
- HAVING
- Date Functions
- Business KPI Reporting

## Analysis Performed

### Basic Analysis
- Display and filter sales records
- Filter customers by city and age
- Identify Electronics products
- Sort sales by amount
- Find customers based on name patterns
- Identify unique cities

### Sales & Revenue Analysis
- Total sales revenue
- Average sales amount
- Maximum and minimum sales
- City-wise sales
- Category-wise revenue
- Salesperson-wise revenue
- Payment mode analysis
- Customer order frequency

### Advanced Analysis
- Highest-sales city
- Highest-revenue category
- Monthly sales revenue
- Top 5 sales transactions
- Product-wise quantity sold
- Average sales by city
- Gross amount before discount
- UPI customers
- Most popular payment mode
- Furniture products above ₹20,000
- Age-based customer analysis
- Gender-wise customer count
- State-wise revenue
- Salesperson with maximum revenue

## Business KPIs

The project also includes a business KPI report covering:

- Total Orders
- Total Revenue
- Average Order Value
- Highest Sale
- Lowest Sale

## Tools Used

**Database:** MySQL  
**Language:** SQL

│
├── retail_store_sales.sql
