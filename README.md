# High-Value Invoice Analysis for Financial Reporting

This project showcases advanced Excel skills through an analysis of invoice data extracted from a non-store online retail dataset. The focus is on identifying high-value invoices, detecting anomalies, and visualizing key business metrics for financial reporting.

---

## Project Overview

This analysis uses Excel to highlight business insights and financial trends using features such as:
- **Pivot Tables**
- **Charts & Graphs**
- **Conditional Formatting**
- **Data Sorting & Filtering**
- **Data Validation**
- **VLOOKUP**
- **Formulas**
- **Cell Formatting**
- **Cleaning etc**

The purpose of this project is to demonstrate proficiency in Excel-based reporting and dashboarding to support **insightful financial decision-making**.

---

## Dataset Summary

- **Source**: Online Retail Transaction Dataset  
- **Period Covered**: December 1, 2010 – December 9, 2011  
- **Instances**: 541,909  
- **Features**: 8

| Variable     | Type         | Description |
|--------------|--------------|-------------|
| InvoiceNo    | Categorical  | Unique invoice ID (starts with 'C' if canceled) |
| StockCode    | Categorical  | Unique product code |
| Description  | Categorical  | Product name |
| Quantity     | Integer      | Number of items sold |
| InvoiceDate  | Date         | Timestamp of transaction |
| UnitPrice    | Continuous   | Price per unit (in sterling) |
| CustomerID   | Categorical  | Unique customer ID |
| Country      | Categorical  | Country of residence |

---

## Excel Workbook Structure of Mine

The workbook consists of **10 well-organized tabs**:

1. **Online Retail Raw Data**
2. **Invoices with Error** – Negative or zero quantity detection
3. **Bad Data** – Filtered out problematic entries
4. **Cleaned Data** – Clean version for analysis
5. **Top 5 Invoices (Highest Revenue)**
6. **Top 10 Customers (Total Revenue)**
7. **Top 10 Selling Products** – Based on quantity sold
8. **Monthly Sales Trend**
9. **Total Revenue per Country**
10. **Outlier Detection** – For unusually high/low unit prices

---
# **Key Findings & Visualizations**
---

## 1️Top 5 Invoices with Highest Revenue  

**Invoice #581483** alone generated $168,469.60, followed by others with significantly lower values — showing large revenue disparity. Recognizing high-revenue invoices helps in tracking large client orders, potential fraud, or billing errors. Implement a system to monitor exceptionally large invoices and verify their validity for audit and risk control.

<p align="center">  
  <img src="https://github.com/user-attachments/assets/cd3db49f-77d8-4be9-a8e4-409ccc0e9156" width="600">  
</p>

---

## 2️Top 10 Customers by Total Revenue 

- **Customer ID 14646** is the top spender with $280,206.02, contributing significantly more than others — followed by 18102 and 17450. Enables businesses to reward loyal customers and tailor personalized experiences to top buyers. Analyze these customers’ purchase behavior to design loyalty or subscription-based models.

<p align="center">  
  <img src="https://github.com/user-attachments/assets/24b57908-a739-414c-922e-f964a802e44f" width="600">  
</p>

---

## 3 Top 10 Selling Products 

- **JUMBO BAG RED RETROSPOT"** tops the list with 46,078 units sold, followed closely by "WHITE HANGING HEART T-LIGHT HOLDER". Business Benefit: Pinpoints the highest-moving inventory, helping optimize stock levels and reduce storage costs. Monitor for seasonal demand trends and consider bundling high-performing products.

<p align="center">  
  <img src="https://github.com/user-attachments/assets/25b97ec1-c486-4b6e-9c04-0f3783df71b1" width="600">  
</p>

---

## 4 Monthly Sales Trend

- **November 2011** had the highest sales at $11.56M, with consistent growth visible in the second half of the year. Reveals peak months to optimize promotions, workforce, and logistics. Plan inventory and marketing efforts ahead of known peak months to capitalize on demand.
  
<p align="center">  
  <img src="https://github.com/user-attachments/assets/cd382785-c1ae-46b0-beeb-d49bbd1b9958" width="600">  
</p>

## Visual Insights

- Tree Maps and Pie Charts for **geographic revenue** distribution
- Bar Charts for **customer and product performance**
- Line Chart for **monthly sales trends**
- Heatmap & conditional formatting to detect **outliers**
  
---

## ✅ Key Takeaways

This project demonstrates the ability to:
- Clean and prepare raw transactional data
- Create powerful visuals using Excel
- Derive actionable insights from large datasets
- Build professional-quality dashboards for stakeholders

---
