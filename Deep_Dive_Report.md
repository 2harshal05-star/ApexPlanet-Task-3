# Task 3: Deep-Dive Analysis & Interactive Dashboard

## 1. Project Overview

This project analyzes sales data using Microsoft Power BI. The objective is to identify sales patterns, understand customer and product performance, and present key business metrics through an interactive dashboard.

## 2. Key Performance Indicators (KPIs)

The following four KPIs are used:

| KPI | Formula | Business Purpose |
|---|---|---|
| Total Revenue | SUM(Total_Sales) | Measures overall sales generated |
| Average Sales | AVERAGE(Total_Sales) | Measures average sales value per record |
| Total Quantity | SUM(Quantity) | Measures total units sold |
| Total Customers | DISTINCTCOUNT(Customer_ID) | Measures the number of unique customers |

## 3. Deep-Dive Analysis: Sales by Category

Sales were analyzed across five product categories:

- Electronics
- Education
- Grocery
- Furniture
- Fashion

### Key Findings

- Electronics generated the highest revenue among the five categories.
- Education was the second-highest category.
- Grocery and Furniture generated relatively similar sales.
- Fashion had the lowest revenue among the five categories.

This analysis helps identify the product categories contributing most to overall revenue.

## 4. City-Wise Sales Analysis

Sales were also compared across different cities.

The dashboard shows that Patna, Kolkata, Bengaluru, and Mumbai are among the stronger-performing cities. The city comparison helps identify geographical differences in sales performance.

## 5. Tools Used

- Microsoft Power BI
- Power BI DAX
- GitHub
- Excel dataset

## 6. Dashboard Features

The interactive dashboard includes:

- KPI cards for important business metrics.
- Sales by City chart.
- Sales by Category chart.
- Sales by Year chart.
- City slicer to filter dashboard results.

## 7. Conclusion

This project provided practical experience in KPI creation, sales analysis, data visualization, and interactive dashboard development using Power BI.

The analysis highlights Electronics as the leading sales category and demonstrates how dashboards can help businesses understand sales performance.

## 8. Project File

The Power BI dashboard file is available in this GitHub repository:

`Task3_Sales_Dashboard.pbix`
