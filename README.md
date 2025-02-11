# Car Sales Analysis Report - Power BI

## Overview
This project presents an interactive **Car Sales Analysis Dashboard** created in **Power BI**. The report provides insights into **total sales, average sales price, car models sold, and sales trends by company, dealer region, and body style**.

## Features
- 📊 **Year-to-Date (YTD) and Month-to-Date (MTD) Sales Analysis**
- 🚗 **Car Sales Breakdown by Model, Body Style, and Color**
- 🌍 **Dealer-wise and Region-wise Sales Insights**
- 📈 **Company-wise Sales Trends**
- 📉 **Growth Analysis & Sales Difference Calculation**
- 🔍 **Comparison of Sales Across Different Time Periods**
- 🛠️ **Dynamic Filtering and Drill-through Analysis**

## DAX Measures Used
The following **DAX formulas** were implemented:
1. **Max Point** - Identifies the highest sales point.
2. **YTD (Year-To-Date Sales)** - Calculates cumulative sales from the start of the year.
3. **AVG (Average Sales Calculation)** - Computes the average sales value per transaction.
4. **CALENDAR.MTD (Month-To-Date Sales)** - Computes sales from the beginning of the current month.
5. **PYTD (Previous Year-To-Date Sales)** - Compares sales with the previous year’s performance.

## Data Cleaning Process
- Removed incorrect **date entries** for company **SAAB**.
- Corrected spelling of **Overhead Engine**.
- Standardized formatting for company names, car models, and dealer names.
- Removed duplicate records and validated data accuracy.

## Project Files
📂 **Detailed Report:** [Car Sales Analysis - Detailed Report](./reports/Car%20SalesAnalysis%20Details.pdf)  
📂 **Project Overview:** [Car Sales Analysis - Overview](./reports/Car%20SalesAnalysis%20overview.pdf)  

## How to Use the Report
1. Open **Power BI Desktop** and load the dataset.
2. Navigate through the **Overview** and **Details** pages.
3. Use filters to analyze sales based on various criteria.
4. Drill down into specific sales trends.

## Technologies Used
- **Power BI** (Data Visualization & Reporting)
- **Excel / CSV** (Data Preprocessing)
- **DAX** (Data Modeling & Calculations)

## Author
👤 **Gaurav Maurya**  
🔗 [LinkedIn](https://www.linkedin.com/in/gauravmaurya156)
