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
# 📊 ApexLark – Retail Sales Dashboard | Day 04

## 📌 Project Overview
This project focuses on analyzing retail sales data using Microsoft Excel to generate meaningful business insights. An interactive Retail Sales Dashboard was developed to track sales performance, profitability, customer behavior, regional performance, and product categories.

**Dataset Details:**
- Total Orders: 4,200
- Total Customers: 4,112
- Time Period: January 2020 – December 2024
- Data Source: Cleaned Retail Sales Dataset
- Currency: Indian Rupees (₹)

## 🎯 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Sales | ₹232.7M |
| Total Profit | ₹43.1M |
| Total Orders | 4,200 |
| Total Customers | 4,112 |
| Profit Margin | 18.5% |

## 🔍 Key Business Insights

1. **Regional Performance:** South region generated the highest sales of ₹53.1M (22.8%), while Central recorded the lowest sales of ₹38.4M.

2. **Category Performance:** Electronics contributed ₹138.4M, representing 59% of total sales. Electronics and Furniture together generated 84% of revenue.

3. **Monthly Sales Trend:** July was the strongest calendar month, generating ₹26.3M. August 2024 recorded the highest individual monthly sales of ₹7.4M.

4. **Customer Analysis:** Meera Kapoor was the top customer with ₹1.2M in purchases. The top 10 customers contributed only 4.2% of total sales.

5. **Sales Growth:** Sales increased from ₹38.4M in 2020 to ₹50.7M in 2024, representing approximately 7.2% CAGR.

6. **Profitability Analysis:** Beauty achieved a 45% profit margin and Books achieved 40%, compared with Electronics at 12% and Groceries at 8%.

7. **Returns and Cancellations:** Returned and cancelled orders accounted for 20.4% of total sales value, indicating an opportunity to reduce revenue leakage.

## 💡 Business Recommendations

- Review discount strategies and supplier pricing to improve Electronics profitability.
- Increase inventory and marketing campaigns before the May–August seasonal peak.
- Introduce festive offers and loyalty rewards during the October–January low season.
- Improve product descriptions and sizing information to reduce returns.
- Strengthen regional marketing strategies in the Central region.
- Promote high-margin categories such as Beauty, Books, and Clothing.

## 📈 Dashboard Features

- Interactive filters: Region, Category, Year, and Month.
- KPI cards for Sales, Profit, Orders, and Customers.
- Sales by Region chart.
- Monthly Sales Trend chart.
- Profit by Category chart.
- Category Share pie chart.
- Top 10 Customers analysis.
- Top 10 Products analysis.

## 🛠️ Tools & Skills Used

- Microsoft Excel
- Pivot Tables
- Excel Charts
- Data Analysis
- Data Visualization
- Interactive Dashboard Design
- Business Intelligence
- Business Insights Generation

## 📚 Key Learnings

- Understanding business KPIs.
- Analyzing regional and category-wise performance.
- Identifying seasonal sales patterns.
- Evaluating profitability and revenue leakage.
- Converting raw data into actionable business recommendations.
- Building interactive Excel dashboards.

## 🏁 Project Outcome

Successfully developed an interactive retail sales dashboard and identified important business opportunities related to sales growth, profitability improvement, seasonal demand, and customer retention.

**Project:** ApexLark Data Analytics Internship Program – Day 04

**Author:** Kiran Kumar
# 📊 Dynamic Business Performance Analysis | ApexLark – Day 05

## 📌 Project Overview
This project focuses on analyzing retail business performance using a dynamic Excel dashboard. The analysis covers sales, profit, orders, customers, regional performance, product categories, and customer behavior from **January 2020 to December 2024**.

The main objective is to identify business trends, understand revenue leakage, evaluate profitability, and provide actionable recommendations to improve business performance.

## 🎯 Project Objectives
- Analyze overall sales and profit performance.
- Identify the highest-performing regions.
- Evaluate product category sales and profitability.
- Identify top 10 customers and products.
- Analyze cancelled and returned orders.
- Discover business problems and provide data-driven recommendations.
- Build a dynamic, formula-driven Excel dashboard.

## 🛠️ Tools & Technologies
- Microsoft Excel
- Pivot Tables
- Excel Formulas
- XLOOKUP / INDEX-MATCH
- KPI Analysis
- Data Cleaning
- Data Visualization
- Business Analytics

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Sales | ₹232.65M |
| Total Profit | ₹43.05M |
| Total Orders | 4,200 |
| Total Customers | 4,112 |
| Profit Margin | 18.5% |
| Average Order Value | ₹55,393 |
| Revenue at Risk | ₹47.45M |

## 🔍 Key Business Insights

### 1. Regional Sales Performance
- South region generated the highest sales of ₹52.97M.
- West region contributed ₹48.47M.
- Central region recorded the lowest sales of ₹38.31M.
- Central achieved the highest profit margin of 19.3%.

### 2. Product Category Analysis
- Electronics generated the highest sales of ₹138.37M.
- Electronics contributed ₹16.67M in profit.
- Furniture generated ₹16.01M profit with a 28.2% margin.
- Beauty achieved a 45.1% profit margin.
- Groceries recorded the lowest margin at 8%.

### 3. Customer Analysis
- Meera Kapoor was the highest-selling customer, contributing ₹1.18M.
- The top 10 customers contributed only 4.2% of total sales.
- Customer ID inconsistencies make repeat-purchase analysis difficult.

### 4. Business Problems Identified
- 14.6% of orders were returned.
- 8.2% of orders were cancelled.
- ₹47.45M in revenue was at risk.
- High dependency on Electronics, contributing 59.5% of total sales.
- Groceries generated a low profit margin of 8%.
- Flat discounting of approximately 20% across categories.
- Customer data quality and satisfaction rating issues.

## 💡 Business Recommendations
1. Reduce product returns and cancellations, especially in Electronics.
2. Improve Electronics profit margins through supplier cost optimization.
3. Focus on high-margin categories such as Furniture, Sports, Beauty, and Clothing.
4. Replace flat discounts with targeted promotional strategies.
5. Increase sales in the Central region through regional campaigns.
6. Improve customer data accuracy and satisfaction feedback collection.
7. Prioritize high-value orders of ₹50,000 and above.

## 📊 Dashboard Features
- Dynamic year selection.
- Automatic KPI updates.
- Regional sales and profit comparison.
- Product category performance analysis.
- Top 10 customer analysis.
- Top 10 product analysis.
- Revenue-at-risk monitoring.
- Formula-driven reporting.

## 📚 What I Learned
- How to transform cleaned business data into meaningful insights.
- How to build dynamic Excel dashboards.
- How to use Excel lookup functions.
- How to analyze sales, revenue, profit, and margins.
- How to identify business problems using data.
- How to communicate findings through business reports.
- How to provide actionable recommendations based on data.

## 🚀 Conclusion
This project demonstrates how Excel-based business analytics can help organizations understand sales performance, monitor profitability, identify revenue leakage, and make better business decisions.

The analysis highlights opportunities to reduce returns, improve category profitability, strengthen regional performance, and enhance customer data quality.

**Project:** ApexLark Data Analytics Internship – Task Day 05  
**Report:** Dynamic Business Performance Analysis  
**Period:** January 2020 – December 2024
