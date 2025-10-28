# FUTURE_DS_01
E-Commerce Sales Performance Dashboard | Power BI project analyzing sales, profit, and revenue trends — built as part of Data Analytics Internship at Future Interns.


# 🛒 FUTURE_DS_01 – E-Commerce Sales Performance Dashboard

## 🎯 Overview
This repository contains **Task 1** of my **Data Science & Analytics Internship** at **Future Interns**.  
The objective of this project was to analyze e-commerce sales data to identify revenue trends, product performance, and profit insights using Power BI.

## 🧠 Objectives
- Analyze total sales, profit, and revenue growth  
- Study product and category-wise performance  
- Visualize regional sales distribution across India  
- Calculate KPIs using DAX for better business decisions  

## 🧰 Tools & Technologies
- **Power BI** – Data cleaning, modeling, and dashboard building  
- **Excel / CSV** – Dataset preparation  
- **DAX (Data Analysis Expressions)** – for creating key measures  

## 📊 Key Insights
- Total Sales: 16M  
- Total Profit: 3M  
- Average Order Value: 25K  
- Profit Margin: 20%  

## 🧮 Key DAX Measures
```DAX
Total Sales = SUM('Ecommerce_Sales_Data'[Sales])
Total Profit = SUM('Ecommerce_Sales_Data'[Profit])
Avg Order Value = DIVIDE([Total Sales], DISTINCTCOUNT('Ecommerce_Sales_Data'[Order ID]), 0)
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
