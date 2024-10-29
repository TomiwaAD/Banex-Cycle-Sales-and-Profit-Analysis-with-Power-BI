Here's a refined README for your *Cycles Sales and Profit Analysis Dashboard* project, structured with **Introduction**, **Problem Statement**, **Skills Demonstrated**, and **Data Transformation**, including the best elements from our previous versions:

---

# Cycles Sales and Profit Analysis Dashboard

## Introduction
This project is part of the requirement to complete my Advanced Power Bi certificate from Udemy,.It delivers an in-depth analysis of sales and profit for a Banex cycling product company. I designed a dynamic and insightful dashboard to explore key performance indicators (KPIs) such as revenue, cost, profit margin, and sales quantities across multiple product categories and regions. This dashboard showcases skills in DAX calculations, interactive visualizations, and data modeling, empowering stakeholders with actionable insights for strategic decision-making.

## Problem Statement
The primary objectives of this analysis are:
- To evaluate product and regional performance against a targeted revenue goal of $50 million.
- To identify top-performing products and subcategories by revenue, profit margin, and quantity sold.
- To assess monthly trends and regional performance, providing actionable insights for data-driven strategies.

This approach enables the business to focus on high-performing areas, optimize for profitability, and monitor revenue targets across the Pacific, North America, and Europe regions.

## Skills Demonstrated
1. **Advanced DAX Calculations**: Developed sophisticated DAX measures to compute KPIs including Total Revenue, Total COGS, Profit Margin, and month-over-month comparisons. Key calculations:
   - **Total Revenue**: Sum of `Quantity_Sold` multiplied by `Unit_Price` from related products.
   - **Profit Margin**: Calculated as Total Revenue minus Total COGS, offering insights into overall profitability.
   - **Top-N Ranking**: Dynamic rankings for products and subcategories based on user-defined values.

2. **Data Modeling**: Implemented a star schema data model for optimized reporting:
   - **Fact Table**: The core *FactTable* contains transaction data, including quantities sold and relevant keys to dimension tables.
   - **Dimension Tables**: Separate tables for *Products*, *Categories*, *Regions*, and *Calendar*, allowing detailed filtering and aggregation of metrics.
   - **Relationships**: Built one-to-many relationships from dimension tables to the Fact Table, supporting efficient queries and reliable calculations.

3. **Data Transformation and Cleaning**: Used Power Query to clean and transform raw data:
   - Handled missing values, standardized formats, and ensured data integrity before loading into Power BI.
   - Added calculated columns to streamline analysis, including formatted date fields and custom product categories.

4. **Interactive Dashboard Design**: Created a user-friendly dashboard with adjustable parameters:
   - **Top-N Selection**: Allows users to define the number of top products to view by revenue.
   - **Monthly Performance Tracking**: Displays revenue, COGS, and profit margin with month-over-month trends.
   - **Region-Specific Insights**: Offers clear, color-coded indicators for each region’s performance against the target, enabling quick identification of strengths and areas for improvement.

## Data Transformation
In Power Query, I performed multiple transformation steps to prepare the data for analysis:
- **Merging and Cleaning**: Merged separate tables for products, subcategories, and regions with sales data, ensuring consistency in labels and categories.
- **Custom Date Table**: Generated a calendar table using `CALENDARAUTO()` with custom columns for Year, Quarter, and Month, enabling temporal analysis.
- **Formatting and Data Types**: Standardized currency and number formats, ensuring that data types were appropriate for calculations and visualizations.

## Conclusion
The *Cycles Sales and Profit Analysis Dashboard* showcases my skills in Power BI, including advanced DAX, effective data modeling, and transformative data preparation. This project not only highlights my analytical abilities but also demonstrates my ability to design actionable and dynamic visualizations, providing valuable insights for data-driven decision-making.
