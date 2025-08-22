# Vrinda-Store-2022-Sales-Dashboard


![Tool](https://img.shields.io/badge/Tool-Excel%20%2F%20Google%20Sheets-lightgreen?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Data%20Cleaning%20%7C%20EDA-blue?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Skill](https://img.shields.io/badge/Skill-PivotTables%20%26%20Dashboard-orange?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge&logo=check-circle&logoColor=white)
![SQL](https://img.shields.io/badge/Skill-SQL-00758F?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Database](https://img.shields.io/badge/Concept-Database-4CAF50?style=for-the-badge&logo=database&logoColor=white)
![Queries](https://img.shields.io/badge/Skill-Query%20Writing-F39C12?style=for-the-badge&logo=sql&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Skill-Data%20Analysis-6f42c1?style=for-the-badge&logo=tableau&logoColor=white)
![Problem Solving](https://img.shields.io/badge/Skill-Problem%20Solving-ff4500?style=for-the-badge&logo=leanpub&logoColor=white)
![Logical Thinking](https://img.shields.io/badge/Skill-Logical%20Thinking-009688?style=for-the-badge&logo=brain&logoColor=white)

Annual Sales Dashboard for Vrinda Store (2022) in Excel. Interactive dashboard visualizes sales trends, customer demographics, and operational metrics. Enables data-driven decisions with dynamic charts and filters. Includes data cleaning, analysis, and recommendations for growth and efficiency.

# Vrinda Store: 2022 Annual Sales Dashboard Report

## Table of Contents

- [Executive Summary](#executive-summary)
- [Problem Statement & Project Objectives](#problem-statement--project-objectives)
- [Dataset & Data Dictionary](#dataset--data-dictionary)
- [Methodology](#methodology)
- [Key Insights & Business Recommendations](#key-insights--business-recommendations)
- [How to Use the Dashboard](#how-to-use-the-dashboard)
- [Future Enhancements](#future-enhancements)
- [Contact & Credits](#contact--credits)

---

## Executive Summary

This repository presents a comprehensive sales analysis project for **Vrinda Store**, focusing on the fiscal year 2022. The primary deliverable is an interactive sales dashboard developed in **Microsoft Excel** that transforms raw sales data into actionable business intelligence. Stakeholders can understand key performance indicators, customer demographics, and market trends through detailed overviews, analytical methodology, key findings, and strategic recommendations.

---

## Problem Statement & Project Objectives

The owner of Vrinda Store required an annual sales report to help employees better understand company performance and the customer base.

**Key business questions addressed:**
- **Sales Performance Comparison:** How do total sales compare to order counts over time?
- **Seasonal Trends:** Which month had the highest sales and order volume?
- **Demographic Insights:** What is the breakdown of purchases by gender?
- **Operational Analysis:** What are the order statuses and their frequencies?

This project delivers answers and a visual, interactive tool for ongoing sales monitoring.

---

## Dataset & Data Dictionary

The analysis was conducted using all 2022 sales transactions. The data table includes:

| Column Name      | Description                                | Data Type |
|------------------|--------------------------------------------|-----------|
| Order_ID         | Unique identifier for each transaction      | String    |
| Date             | Date the order was placed                   | Date      |
| Product          | Name of the product purchased               | String    |
| Category         | Product category                            | String    |
| Quantity         | Number of units sold                        | Integer   |
| Price_per_Unit   | Price per single unit                       | Currency  |
| Gender           | Customer gender                             | String    |
| Order_Status     | Status (Delivered, Returned, Canceled)      | String    |

---

## Methodology

**Excel workflow:**
1. **Data Cleaning & Preprocessing**
    - Duplicate removal.
    - Uniform formatting.
    - Derived columns: *Total Sales* (`Quantity * Price_per_Unit`), and *Month* for time-series analysis.
2. **Exploratory Data Analysis (EDA)**
    - Used Pivot Tables to summarize sales, orders, and average values by month, product, and gender.
3. **Data Visualization & Dashboarding**
    - Combo chart for monthly sales and orders.
    - Bar chart for sales by gender.
    - Pie charts for order status distribution.
    - Slicers and Timeline for dynamic filtering.

---

## Key Insights & Business Recommendations

- **Seasonal Sales Performance:** December is the peak month.  
  *Recommendation:* Increase marketing and inventory in Q4.
- **Customer Demographics:** Women are the largest buying segment.  
  *Recommendation:* Tailor marketing to women for higher growth.
- **Product & Category Performance:** Dashboard shows real-time top-selling items.  
  *Recommendation:* Optimize inventory; inform promotions.
- **Operational Efficiency:** Most orders are delivered successfully.  
  *Recommendation:* Monitor returns/cancellations for potential issues.

---

## How to Use the Dashboard

1. Open the Excel file (`Vrinda_Store_Sales_Dashboard.xlsx`).
2. Use **Slicers** to filter by category or region.
3. Adjust the view with the **Timeline**.
4. Click a chart element to see corresponding filtered data.

---

## Future Enhancements

- Integration with live sales data for real-time reporting.
- Advanced analysis (e.g., customer lifetime value, return rates).
- Explore Power BI dashboards for enhanced modeling and visualizations.

---

## Contact & Credits

- **Author:** [Your Name]
- **Email:** [Your Email]
- **LinkedIn:** [Your LinkedIn Profile URL]
- **Project File:** `Vrinda_Store_Sales_Dashboard.xlsx`
