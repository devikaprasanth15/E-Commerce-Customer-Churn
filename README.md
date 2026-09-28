# E-Commerce Customer Churn Analysis

## Overview

This project analyzes e-commerce transactional data in MySQL to identify customer churn patterns and drivers, serving as a 
hands-on exercise to practice database management, data cleaning, feature engineering, and writing complex SQL queries with 
aggregations, subqueries, and relational joins.

##  Repository Structure

```text
├── customer_churn_analysis.sql  # Complete SQL script (Data Cleaning, Transformation, & Insights)
└── README.md                    # Project documentation (this file)
```

## What I Did & Learned

* **Data Cleaning & Imputation:** Handled missing values by calculating and imputing mean and mode metrics, and removed operational outliers like warehouse distances exceeding 100km.
* **Data Standardization:** Resolved text inconsistencies and standardized categorical entries (e.g., mapping "Phone" to "Mobile Phone" and "COD" to "Cash on Delivery").
* **Schema Transformation:** Renamed columns for consistency, engineered new binary flags using CASE WHEN logic, and dropped redundant fields to streamline the table schema.
* **Business Analytics & Joins:** Wrote SQL queries using aggregations, subqueries, distance binning, and multi-table JOIN operations to analyze customer behavior and churn drivers.

---
