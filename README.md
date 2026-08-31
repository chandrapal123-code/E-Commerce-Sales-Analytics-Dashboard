# E-Commerce-Sales-Analytics-Dashboard
Interactive E-Commerce Sales Analytics Dashboard built using Microsoft Power BI, Power Query, DAX, and data visualization techniques to analyze sales, profit, customers, products, and business performance.

#  E-Commerce Sales Analytics Dashboard

##  Project Overview

This project is an **E-Commerce Sales Analytics Dashboard** developed using **Microsoft Power BI**.

The main objective of this project is to analyze e-commerce business data and convert raw sales data into meaningful and interactive business insights.

The dashboard helps users understand:

* Overall sales performance
* Profit performance
* Order and quantity trends
* Customer behavior
* Product performance
* Regional performance
* Payment methods
* Category-wise sales
* Monthly sales trends
* Profit margins

---

##  Technologies Used

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Cleaning & Transformation**
* **Data Visualization**
* **Business Intelligence**

---

##  Dashboard Pages

### 1. E-Commerce Dashboard

The main dashboard provides an overall view of business performance.

### Key KPIs

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Average Sales
* Average Profit
* Profit Margin %

### Visualizations

* Sales by Category
* Profit by Region
* Payment Method Analysis
* Monthly Sales Trend
* Sales Performance Charts
* Interactive Slicers

---

### 2. Customer Analysis

This page focuses on customer-level analysis.

It helps analyze:

* Customer-wise sales
* Customer orders
* Customer performance
* Customer segmentation
* Customer-level details

Interactive filters and tables are used to make customer analysis easier.

---

### 3. Product Analysis

This page focuses on product performance.

It provides insights into:

* Product-wise sales
* Product performance
* Top-performing products
* Product-level comparison
* Product sales trends

---

### 4. Sales Analysis

The Sales page provides detailed sales performance analysis.

It includes:

* Monthly sales trends
* Sales comparison
* Sales by category
* Sales distribution
* Sales-related KPIs
* Interactive filtering

---

### 5. Profit Analysis

The Profit page focuses on understanding profitability.

It analyzes:

* Total Profit
* Average Profit
* Profit Margin %
* Regional Profit
* Profit trends
* Profit distribution
* Sales vs Profit relationship

---

##  Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Major steps included:

1. Imported the e-commerce dataset into Power BI.
2. Checked the data types of columns.
3. Cleaned and transformed the data.
4. Handled required data-quality issues.
5. Created calculated columns where required.
6. Extracted month information from date fields.
7. Created business categories for analysis.
8. Prepared the data for visualization.

---

##  DAX Measures

The dashboard uses DAX measures for important business KPIs.

### Total Sales

```DAX
Total Sales = SUM(Orders[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Orders[Profit])
```

### Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

### Total Quantity

```DAX
Total Quantity = SUM(Orders[Quantity])
```

### Average Sales

```DAX
Average Sales = AVERAGE(Orders[Sales])
```

### Average Profit

```DAX
Average Profit = AVERAGE(Orders[Profit])
```

### Profit Margin %

```DAX
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```

> Note: If the actual measure definitions in your PBIX differ, use the definitions from your Power BI model when documenting the project.

---

##  Key Business Questions

This dashboard can answer questions such as:

* What are the total sales?
* What is the total profit?
* How many orders were placed?
* Which category generates the highest sales?
* Which region generates the highest profit?
* Which products perform best?
* How are sales changing month by month?
* Which payment method is commonly used?
* What is the overall profit margin?
* Which customers contribute significantly to sales?
* What is the relationship between sales and profit?

---

##  Project Objectives

The major objectives of this project are:

1. Convert raw e-commerce data into useful business information.
2. Analyze sales and profitability.
3. Identify high-performing categories and products.
4. Analyze customer and regional performance.
5. Track sales trends over time.
6. Build an interactive business dashboard.
7. Support data-driven decision making.

---

##  Key Skills Demonstrated

Through this project, I demonstrated my knowledge of:

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* KPI Development
* Data Visualization
* Business Intelligence
* Sales Analysis
* Profit Analysis
* Customer Analysis
* Product Analysis
* Dashboard Development

---
## Business Insights

1. **Sales Performance**

   * The dashboard helps identify overall **sales, profit, orders, and quantity sold**.
   * Monthly sales trends help management understand which months perform better and plan sales strategies accordingly.

2. **Regional Performance**

   * The **Profit by Region** analysis identifies high-performing and low-performing regions.
   * The business can focus marketing and sales efforts on regions with strong growth potential.

3. **Category Analysis**

   * **Sales by Category** shows which product categories contribute the most revenue.
   * High-performing categories can receive more inventory and promotional attention.

4. **Top Products**

   * The **Top 10 Products** visual helps identify products generating the highest sales.
   * These products can be prioritized for inventory management and marketing campaigns.

5. **Sales vs Profit**

   * Comparing sales and profit helps identify products that generate high revenue but may have **low profit margins**.
   * This can support better pricing and discount decisions.

6. **Profitability**

   * **Profit Margin %** helps evaluate whether increasing sales is actually improving profitability.
   * Management can reduce unnecessary discounts or costs for low-margin products.

7. **Customer Insights**

   * The customer details section helps identify valuable customers and their purchasing behavior.
   * This can support **customer retention and targeted marketing campaigns**.

8. **Data-Driven Decision Making**

   * Power BI provides interactive **KPIs, charts, maps, and slicers**, allowing management to quickly monitor business performance and make faster decisions.

##  Project Type

**Data Analytics | Business Intelligence | Power BI Dashboard**

---

##  Project Highlights

-- Interactive Power BI dashboard
-- Multiple analytical pages
-- KPI-based business reporting
-- DAX measures
-- Power Query transformations
-- Customer analysis
-- Product analysis
-- Sales analysis
-- Profit analysis
-- Interactive slicers and visualizations
