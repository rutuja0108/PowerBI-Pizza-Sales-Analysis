# 🍕 Pizza Sales Analysis | MySQL + Power BI

## 📌 Project Overview

The **Pizza Sales Analysis** project is a data analytics and business intelligence project based on raw pizza sales data.

The main objective of this project is to analyze pizza sales performance, understand customer ordering patterns, identify the best-selling and worst-selling pizzas, and present meaningful insights through an interactive **Power BI dashboard**.

In this project, I worked with raw pizza sales data and followed a complete data analytics workflow:

**Raw Data → Data Cleaning & Manipulation using MySQL → SQL Analysis → MySQL Connection with Power BI → Dashboard Development → Business Insights**

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze pizza sales data.
- Clean and transform raw data using MySQL.
- Create required columns and perform data manipulation.
- Write SQL queries to analyze sales performance.
- Identify the **Top 5 Best-Selling Pizzas**.
- Identify the **Bottom 5 Pizzas**.
- Analyze pizza quantity and order performance.
- Analyze sales based on pizza category and size.
- Connect MySQL with Power BI.
- Create an interactive Power BI dashboard.
- Present business insights in an easy-to-understand visual format.

---

## 🗂️ Dataset

The project uses a raw pizza sales dataset containing information related to pizza orders.

The dataset contains information such as:

- Order ID
- Order Date
- Order Time
- Pizza Name
- Pizza Category
- Pizza Size
- Pizza Quantity
- Pizza Price
- Total Price

The raw dataset was first processed and analyzed using **MySQL** before connecting it to Power BI.

---

# 🔄 Project Workflow

## 1. 📥 Data Collection

First, I collected the raw pizza sales dataset.

The raw data contained different details about pizza orders, including order information, pizza details, quantity, price, category, and size.

The raw dataset was then imported into **MySQL** for cleaning, transformation, and analysis.

---

## 2. 🧹 Data Cleaning & Manipulation using MySQL

After importing the raw data into MySQL, I performed data cleaning and manipulation operations.

Some of the tasks included:

- Checking the structure of the dataset.
- Checking for missing or incorrect values.
- Modifying data types where required.
- Creating additional columns.
- Extracting useful information from date and time columns.
- Calculating total sales/revenue.
- Preparing the data for analysis.
- Organizing the dataset for Power BI visualization.

MySQL was used to prepare the raw data before connecting it with Power BI.

---

## 3. 🧮 SQL Analysis

After cleaning the data, I created multiple SQL queries to analyze pizza sales.

The analysis included:

### 🍕 Top 5 Best-Selling Pizzas

Identified the top five pizzas based on sales/quantity/order performance.

This helps determine which pizzas are most popular among customers.

### 📉 Bottom 5 Pizzas

Identified the five pizzas with the lowest sales performance.

This helps understand which products may require further analysis or improvement.

### 📦 Pizza Quantity Analysis

Analyzed how many pizzas were sold and compared the quantity across different pizzas.

### 💰 Sales/Revenue Analysis

Analyzed pizza sales and revenue to understand which products contribute most to overall business performance.

### 🏷️ Category Analysis

Analyzed sales performance across different pizza categories.

### 📏 Size Analysis

Analyzed customer preferences based on different pizza sizes.

---

# 🔗 4. MySQL → Power BI Connection

After completing the data cleaning and SQL analysis, I connected the **MySQL database directly to Power BI**.

The processed data was loaded into Power BI for visualization and dashboard development.

This allowed me to use the cleaned and prepared data for creating interactive reports.

---

# 📊 5. Power BI Dashboard

Using Power BI, I created an interactive dashboard to present the results of the analysis.

The dashboard contains different sections/pages, including:

## 🏠 Home Dashboard

The Home page provides an overview of the pizza sales performance.

It includes important KPIs and visualizations such as:

- Total Revenue
- Total Orders
- Total Pizza Quantity
- Average Order Value
- Sales trends
- Pizza category analysis
- Pizza size analysis

The purpose of the Home page is to provide a quick overview of the overall business performance.

---

## ⭐ Best Seller Dashboard

The Best Seller section focuses on pizza-level performance.

It shows:

- Top 5 Best-Selling Pizzas
- Bottom 5 Pizzas
- Pizza Quantity
- Sales/Revenue
- Pizza Category
- Pizza Size
- Order performance

This page helps identify which pizzas are performing well and which pizzas have comparatively lower performance.

---

# 📈 Key Insights

The analysis helps answer important business questions such as:

- Which are the **Top 5 Best-Selling Pizzas**?
- Which are the **Bottom 5 Pizzas**?
- Which pizza has the highest quantity sold?
- Which pizzas generate the most revenue?
- Which pizza category performs best?
- Which pizza size is most popular?
- Which pizzas have lower sales performance?
- How are overall pizza sales performing?

These insights can help businesses understand customer preferences and make better decisions regarding their products and sales strategies.

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **MySQL** | Data cleaning, transformation and SQL analysis |
| **SQL** | Querying and analyzing the dataset |
| **Power BI** | Data visualization and dashboard creation |
| **Power Query** | Data transformation in Power BI |
| **DAX** | Calculations and measures |
| **CSV** | Raw dataset |
| **Git & GitHub** | Project version control and portfolio |

---

# 🧠 Skills Demonstrated

Through this project, I demonstrated practical skills in:

- Data Cleaning
- Data Manipulation
- SQL
- MySQL
- Data Analysis
- Power BI
- Power Query
- DAX
- Data Visualization
- Dashboard Development
- Business Intelligence
- Data-driven Decision Making
- Git & GitHub

---

# 📁 Project Structure

```text
PowerBI-Pizza-Sales-Analysis/
│
├── Pizza Dashboard.pbix
├── pizza_sales.csv
├── SQL Queries/
│   └── Pizza Sales SQL Queries.sql
│
├── screenshots/
│   ├── home-dashboard.png
│   └── best-seller-dashboard.png
│
└── README.md
