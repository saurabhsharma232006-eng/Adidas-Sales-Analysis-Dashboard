# 👟 Adidas Sales Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Analytics-orange)

## 📊 Project Overview

The **Adidas Sales Analysis Dashboard** is an interactive **Power BI business intelligence project** designed to analyze Adidas sales performance across products, retailers, regions, and sales methods.

The project transforms raw sales data into an interactive dashboard that enables users to monitor **revenue, profit, units sold, product performance, regional performance, and sales trends**.

The dashboard is designed from a business perspective to help identify high-performing areas and understand sales patterns.

---

## 🎯 Business Objectives

The main objectives of this project are:

* Analyze overall sales and profitability.
* Monitor key sales KPIs.
* Identify top-performing products.
* Compare sales performance across regions.
* Analyze retailer performance.
* Evaluate different sales methods.
* Identify monthly and yearly sales trends.
* Provide interactive filtering for business analysis.

---

## 🛠️ Tools & Technologies

| Tool              | Purpose                        |
| ----------------- | ------------------------------ |
| **Power BI**      | Dashboard & Data Visualization |
| **Power Query**   | Data Cleaning & Transformation |
| **DAX**           | Calculated Measures & KPIs     |
| **Excel / CSV**   | Data Source                    |
| **Data Modeling** | Organizing data for analysis   |

---

## 📂 Dataset

The dataset contains sales information including:

* Retailer
* Retailer ID
* Invoice Date
* Region
* State
* City
* Product
* Price per Unit
* Units Sold
* Total Sales
* Operating Profit
* Operating Margin
* Sales Method

---

## 🔄 Data Cleaning & Transformation

The raw dataset was prepared using **Power Query**.

### Key steps:

1. Imported the raw sales data.
2. Checked and corrected data types.
3. Identified missing and inconsistent values.
4. Removed unnecessary columns.
5. Cleaned and standardized categorical fields.
6. Created required calculated columns.
7. Prepared the dataset for data modeling.
8. Loaded the transformed data into Power BI.

---

## 🧮 DAX Measures

Several DAX measures were created to calculate important business KPIs.

### Total Sales

```DAX
Total Sales = SUM(Sales[Total Sales])
```

### Total Units Sold

```DAX
Total Units Sold = SUM(Sales[Units Sold])
```

### Total Profit

```DAX
Total Profit = SUM(Sales[Operating Profit])
```

### Average Sales

```DAX
Average Sales = AVERAGE(Sales[Total Sales])
```

### Profit Margin

```DAX
Profit Margin =
DIVIDE([Total Profit], [Total Sales], 0)
```

These measures were used throughout the dashboard to create dynamic KPIs and visualizations.

---

## 📈 Dashboard Highlights

### 🔹 KPI Analysis

The dashboard provides an overview of:

* **Total Sales**
* **Total Profit**
* **Total Units Sold**
* **Profit Margin**
* **Average Sales**

### 🔹 Sales Trend Analysis

Analyze sales performance over time using monthly and yearly trends.

### 🔹 Regional Analysis

Compare sales and profitability across different regions, states, and cities.

### 🔹 Product Analysis

Identify products with high sales and profit contributions.

### 🔹 Retailer Analysis

Compare sales performance among different retailers.

### 🔹 Sales Method Analysis

Analyze performance across different sales channels/methods.

### 🔹 Interactive Filters

Users can dynamically explore the dashboard using slicers and filters such as:

* Date
* Region
* Retailer
* Product
* Sales Method

---

## 📷 Dashboard Preview

### Main Dashboard

![Adidas Sales Dashboard](Images/dashboard.png)

> Replace `Images/dashboard.png` with your actual dashboard screenshot.

### Dashboard Demo

You can also add a GIF or screen recording preview of the interactive dashboard here.

```text
🎥 Interactive Dashboard Demo
```

---

## 💡 Key Business Insights

The dashboard helps answer important business questions such as:

* Which region generates the highest revenue?
* Which products are the best sellers?
* Which retailers contribute the most sales?
* Which sales method performs best?
* How does sales performance change over time?
* Which products generate the highest profit?
* Which regions have stronger profitability?

These insights can help businesses understand sales performance and identify areas for improvement.

---

## 📁 Project Structure

```text
Adidas-Sales-Analysis-PowerBI/
│
├── Dataset/
│   └── Adidas_Sales.csv
│
├── Dashboard/
│   └── Adidas_Sales_Analysis.pbix
│
├── Images/
│   ├── dashboard.png
│   └── dashboard_demo.gif
│
└── README.md
```

---

## 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Power Query Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Data Visualization
     ↓
Interactive Power BI Dashboard
     ↓
Business Insights
```

---

## 📚 Skills Demonstrated

**Technical Skills**

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Modeling
* Data Visualization
* KPI Development
* Business Intelligence
* Exploratory Data Analysis

**Business Skills**

* Sales Analysis
* Profitability Analysis
* Trend Analysis
* Regional Analysis
* Product Performance Analysis
* Retailer Performance Analysis

---

## 🎓 Project Outcome

This project demonstrates my practical ability to use **Power BI, Power Query, and DAX** to transform raw sales data into an interactive business dashboard.

It helped me strengthen my skills in **data preparation, analytical thinking, KPI development, visualization, and business-oriented data analysis**.

---

## 👨‍💻 Author

### Saurabh Sharma

**Data Analyst | Data Science**

📍 Aligarh, India

**Skills:**
`Power BI` `SQL` `Python` `Excel` `DAX` `Pandas` `Data Analysis`

---

## ⭐ If you found this project useful

Feel free to **star ⭐ the repository** and explore the project.
# Adidas-Sales-Analysis-Dashboard
