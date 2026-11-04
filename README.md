# Ecommere-Sales-Analysis-Excel
E-commerce sales data analysis using Microsoft Excel, PivotTables, charts, and business insights.
E-Commerce Sales Analysis Using Microsoft Excel

Project Overview

This project analyzes e-commerce sales data using Microsoft Excel to identify business trends and performance.

Tools Used

- Microsoft Excel
- PivotTables
- Charts
- Data Cleaning
- Data Analysis

Key Activities

- Cleaned and organized raw sales data.
- Created PivotTables for regional, product category, and payment method analysis.
- Analyzed sales and profit.
- Created charts to visualize business performance.
- Calculated total sales, total profit, average order value, and profit margin.

Key Insights

- Total Orders: 4,280
- Total Sales: ₹26,68,94,969
- Total Profit: ₹5,00,20,895
- Average Order Value: ₹62,358.64
- Profit Margin: 18.74%
- Highest Sales Region: South
- Lowest Sales Region: Central

Project File
Ecommerce_Sales_Analysis.xlsx
Author
R.Kiran Kumar
------day-3-------
# 🧹 Retail Sales Data Cleaning Project

## 📌 Project Overview
This project focuses on cleaning and preparing a real-world retail orders dataset for accurate analysis.

The dataset contains retail order information with 20 columns, covering orders from January 2020 to December 2024.

The main objective was to identify and handle missing values, duplicate records, inconsistent formats, invalid values, and incorrect sales calculations.

## 📂 Dataset Information
- **Dataset:** Retail Order Data
- **Source File:** DOC-20261102-WA0001.csv
- **Total Columns:** 20
- **Original Rows:** 4,310
- **Cleaned Rows:** 4,200
- **Date Range:** 2020–2024

## 🛠️ Data Cleaning Tasks Performed
1. Removed 30 completely empty rows.
2. Removed 80 exact duplicate records.
3. Standardized multiple date formats into YYYY-MM-DD.
4. Standardized gender values (Male, Female, Other).
5. Standardized order status values.
6. Handled invalid age values.
7. Corrected negative shipping costs.
8. Handled invalid and missing quantity values using product-wise median.
9. Handled missing age, discount percentage, and shipping days using median imputation.
10. Corrected inflated sales and profit values caused by placeholder quantity 999.
11. Preserved missing customer satisfaction ratings instead of inventing values.
12. Added cleaning notes to maintain data traceability.

## 📊 Before vs After Cleaning

| Metric | Before | After |
|---|---:|---:|
| Total Rows | 4,310 | 4,200 |
| Total Sales | 266,894,969 | 232,651,921 |
| Largest Order | 17,360,314 | 1,182,709 |
| Date Formats | 3 | 1 |
| Columns with Missing Values | 5 | 1 |

## 🔍 Data Quality Checks
- Verified unique order IDs.
- Checked date formats and date ranges.
- Verified return flags against order status.
- Checked missing values.
- Reconciled the final row count.
- Maintained cleaning notes for corrected records.

## ⚠️ Key Observations
- 239 customers were under 16 years old.
- 87 customer IDs appeared with multiple customer names.
- The dataset contained approximately 34% Other gender values.
- Sales amount did not always exactly match quantity × unit price × (1 − discount), possibly because of taxes or additional charges.

## 💡 Key Learnings
- Practical data cleaning techniques.
- Handling missing and duplicate values.
- Data validation and quality checks.
- Median imputation techniques.
- Standardizing inconsistent data.
- Improving data accuracy and reliability.

## 📁 Project Files
- `Data_Cleaning_Report.pdf` – Detailed data cleaning report.
- `README.md` – Project documentation.

## 🎯 Conclusion
Successfully cleaned 4,310 raw records and retained 4,200 unique retail orders. The project improved data consistency, reliability, and quality, making the dataset more suitable for further analysis.

---
**Project Category:** Data Analytics | Data Cleaning  
**Role:** Data Analyst – Fresher Portfolio Project
