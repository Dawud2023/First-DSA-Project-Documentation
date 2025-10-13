# 📘 Documentation

This documentation outlines the process of building my **Data Analysis Portfolio**.  
The portfolio demonstrates my ability to **gather, clean, analyze, and visualize data** using tools such as **Excel, Power BI, and SQL**.  
It serves as both a **learning record** and a **professional showcase** of my analytical capabilities.

---

## 🎮 Project Topic
**Gaming Console Sales Analysis**

---

## 🎯 Project Overview
The goal of this project is to analyze **global video game sales data** to identify **key market trends**, **top-performing platforms**, and **customer segment performance**, as well as **monthly sales trends** influencing game sales across different regions.  
The analysis aims to provide **actionable insights** for **game publishers, marketers, and investors** looking to understand the dynamics of the gaming industry.

---

## 🧾 Dataset Description
**Source:** Kaggle – Video Game Sales Dataset  

### Data Fields
- **Platform** (e.g., Nintendo Switch, Xbox Series X, PlayStation 5)  
- **Year of Release**  
- **North America, Europe, Asia, South America, and Africa, Global Sales (in millions)**  

---

## 🧰 Tools and Technologies Used
- **Data Cleaning & Analysis:** Excel  
- **Visualization:** Excel  
- **Data Preparation:** Excel for initial exploration  
- **Documentation & Hosting:** GitHub  

---

## 🔍 Process Summary

### 📂 Data Collection
- Imported the dataset from **Kaggle** into **Excel** for analysis.

### 🧹 Data Cleaning
- Creating a **Month** column for simplifying the analysis process and using an Excel function to convert date to month:  
  ```excel
  =TEXT(B2,"mmm")
- Creating another column for Customer ID by using an Excel function:
  ```excel
  ="CUST-" & TEXT(ROW(A1),"000")

 ### Exploratory Data Analysis (EDA)

- Used summary statistics and visualizations to explore global sales distribution.

- Identified top-selling games, platforms, customer segments, and regions.

- Analyzed monthly sales trends to see the rise and fall of gaming platforms over time.

### 📈 Data Visualization

   💡 Created dashboards in Excel showing:

- Global Sales by Platform (Retail vs Online)

- Monthly Sales Trend (JAN–DEC)

- Regional Comparison: NA vs EU vs SA vs ASIA vs AFRICA

- Total Revenue, Marketing Budget, Product Cost, and Units Sold by Console Brands

### Insights Generation

Extracted insights on which customer segments and platforms are dominated by each region.

Compared regional sales and their contribution to global sales.

### 🔑 Key Findings & Insights

Top Platform: PlayStation 5 (PS5) recorded the highest global sales among all platforms.

Most Turnover Regionally: Europe led sales across all regions.

Most Sales Channel: Online

Sales Trend: Peak in video game sales occurred in December

### 🏁 Outcome

The analysis provided a comprehensive overview of the gaming industry’s evolution, highlighting market opportunities for developers focusing on region, customer segment, and sales trend.
Insights from this project could help guide marketing strategies and platform investments.

