# 🍔 Food Delivery Analytics — Power BI Report

An interactive **Power BI Business Intelligence dashboard** designed to analyze food delivery performance, revenue, orders, discounts, product categories, operational areas, promotions, and demand trends.

The project demonstrates an end-to-end **Data Analytics & Business Intelligence workflow** using **Power Query, Data Modeling, DAX, and Power BI visualizations** to transform raw business data into actionable insights.

---

## 📊 Project Overview

The Food Delivery Power BI Report provides an interactive analytical view of a food delivery business.

The dashboard is designed to help business stakeholders answer questions such as:

* How many orders are being generated?
* How is revenue performing?
* What is the impact of discounts on sales?
* Which product categories generate the highest sales?
* How does operational area influence order volume?
* How effective are promotional activities?
* Does revenue follow the **Pareto Principle (80/20 rule)**?
* What can historical demand data indicate about upcoming weeks?

---

## 🎯 Business Objectives

The main objectives of this project are to:

* Track important business KPIs.
* Analyze order and revenue performance.
* Evaluate discount effectiveness.
* Identify top-performing categories.
* Analyze operational-area performance.
* Understand promotional effectiveness.
* Perform Pareto analysis.
* Analyze demand trends.
* Support data-driven business decisions through interactive reporting.

---

## 🛠️ Tools & Technologies

| Technology             | Purpose                                         |
| ---------------------- | ----------------------------------------------- |
| **Microsoft Power BI** | Dashboard development & data visualization      |
| **Power Query**        | Data cleaning and transformation                |
| **DAX**                | Measures, KPIs and analytical calculations      |
| **Data Modeling**      | Structuring relationships between business data |
| **Power BI Visuals**   | Interactive business analysis                   |
| **PDF Export**         | Report sharing and presentation                 |

---

## 🔄 Data Analytics Workflow

```text
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Data Modeling
   ↓
DAX Measures & Calculations
   ↓
Interactive Power BI Visualizations
   ↓
Business Insights
```

---

# 📈 Key Dashboard Features

## 1. 📦 Order Analysis

Provides an overview of order performance using interactive KPIs and visualizations.

Key analysis includes:

* Total Orders
* Order trends
* Orders by category
* Orders by operational area
* Date-based analysis
* Interactive filtering

---

## 2. 💰 Revenue Analysis

Analyzes revenue performance across different business dimensions.

The dashboard enables analysis of:

* Total Revenue
* Revenue trends
* Revenue by category
* Revenue contribution
* Revenue by operational area
* Performance comparison using interactive filters

---

## 3. 🏷️ Discount Analysis

Analyzes the impact of discounts on business performance.

Key metrics include:

* Total Discounted Value
* Overall Discount %
* Discount contribution
* Revenue vs. discount analysis
* Category-level discount analysis

This helps understand the relationship between promotional pricing and revenue generation.

---

## 4. 📊 Pareto Analysis

The dashboard includes **Pareto Analysis** to evaluate revenue concentration.

The analysis helps identify:

* High-revenue centres/categories
* Cumulative revenue contribution
* Revenue concentration
* Contribution of top-performing segments

### Pareto Principle

The analysis is based on the concept that a relatively small proportion of business segments can contribute a significant proportion of total revenue.

This provides a useful framework for identifying high-value areas that deserve closer business attention.

---

## 5. 🏆 Top 5 Selling Categories

A dedicated analysis identifies the **Top 5 selling categories**.

This helps answer:

> Which product categories contribute most to overall demand?

Interactive filters allow users to explore category performance across different dimensions.

---

## 6. 📍 Operational Area Analysis

The report analyzes the relationship between **operational areas and order volume**.

This can help stakeholders understand:

* High-order operational areas
* Low-order areas
* Distribution of demand
* Operational performance differences

---

## 7. 📧 Promotion Effectiveness

The dashboard evaluates promotional factors such as:

* Email promotions
* Homepage/product-feature promotions
* Their relationship with sales/orders

This provides a data-driven view of promotional effectiveness.

---

## 8. 🔮 Demand Forecasting

The report also includes analysis of expected demand for upcoming weeks.

Forecasting can help businesses with:

* Demand planning
* Inventory management
* Fulfilment planning
* Resource allocation
* Operational preparation

---

# 🧮 DAX & Analytical Calculations

A major component of this project is the use of **DAX (Data Analysis Expressions)** to create dynamic business metrics.

DAX was used to build analytical calculations such as:

* Total Orders
* Total Revenue
* Discount calculations
* Discount %
* Average metrics
* Ranking calculations
* Category analysis
* Cumulative values
* Pareto calculations
* KPI measures
* Time-based analysis

### Example DAX Pattern

```DAX
Total Orders =
COUNTROWS(Orders)
```

### Revenue Example

```DAX
Total Revenue =
SUM(Orders[Revenue])
```

### Discount Percentage

```DAX
Discount % =
DIVIDE(
    [Total Discount],
    [Total Revenue],
    0
)
```

> The exact column/table names should be adjusted according to the underlying data model.

---

# 🧹 Power Query & Data Transformation

Power Query was used as part of the ETL process to prepare the data for analysis.

Typical transformations include:

* Data cleaning
* Removing unnecessary fields
* Handling missing values
* Data type conversion
* Column transformations
* Data preparation
* Creating analysis-ready tables

---

# 🧩 Data Modeling

The project demonstrates the importance of structuring business data before building analytical reports.

The model supports:

* Relationships between datasets
* Filter propagation
* Dimension-based analysis
* Dynamic DAX calculations
* Interactive report filtering

---

# 🎨 Dashboard & Visualization Features

The report focuses on creating an interactive and business-friendly experience using:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Ranking Visuals
* Pareto Analysis
* Interactive Slicers
* Dynamic Filtering
* Comparative Visualizations
* Business-focused dashboard layouts

---

# 📌 Key Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis
* Business KPI Analysis
* Revenue Analysis
* Sales Analysis
* Trend Analysis
* Category Analysis
* Operational Analysis

### Power BI

* Dashboard Development
* Interactive Reports
* Data Visualization
* KPI Design
* Slicers & Filters
* Business Intelligence

### DAX

* Measures
* Aggregations
* DIVIDE
* Ranking
* Cumulative calculations
* Percentage calculations
* Business logic

### Power Query

* ETL
* Data Cleaning
* Data Transformation
* Data Preparation

---

# 📂 Repository Contents

```text
Food-delivery---power-BI-report/
│
├── food delivery.pbit
├── food delivery.pdf
├── Screenshot of overview page.png
└── README.md
```

---

# 🚀 How to Use

### 1. Clone the repository

```bash
git clone https://github.com/Gurvinder-singh28/Food-delivery---power-BI-report.git
```

### 2. Open the project

Open the `.pbit` Power BI template using **Microsoft Power BI Desktop**.

### 3. Load/refresh the data

Follow the data-source prompts and refresh the dataset if required.

### 4. Explore the dashboard

Use the available slicers, filters, KPIs, and visualizations to explore the analysis.

---

# 📷 Dashboard Preview

![Food Delivery Power BI Dashboard](Screenshot%20of%20overview%20page.png)

---

# 💡 Business Value

This project demonstrates how raw business data can be transformed into an interactive BI solution that supports:

**Data → Analysis → Insights → Business Decisions**

The dashboard brings together operational, financial, promotional, and demand-related analysis in one Power BI report.

---

# 👨‍💻 Author

**Gurvinder Singh**

AI/ML Engineer | Generative AI Engineer | Data Analyst | Power BI

GitHub:
https://github.com/Gurvinder-singh28

---

## ⭐ If you find this project useful

Feel free to explore the repository, review the Power BI report, and connect with me for discussions around **Data Analytics, Power BI, AI/ML, and Generative AI**.

#PowerBI #DAX #PowerQuery #DataAnalytics #BusinessIntelligence #DataVisualization #Dashboard #DataAnalysis
