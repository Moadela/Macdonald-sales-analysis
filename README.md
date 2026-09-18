# McDonald's Egypt — Power BI Data Analysis

## 📌 Project Overview

This project is a Power BI data analysis project based on a simulated dataset representing McDonald's sales and customer data in Egypt.

The project was created to simulate a real-world business analytics scenario and demonstrate the process of transforming business data into interactive dashboards and actionable insights.

The analysis focuses on sales performance, customer behavior, branch performance, products, payment methods, orders, and profitability.

---

## 📊 Dataset

The dataset used in this project is a simulated dataset designed to represent McDonald's operations in Egypt.

It does not represent actual internal McDonald's data.

The dataset includes information related to:

- Customers
- Orders
- Products
- Branches
- Sales
- Payment Methods
- Dates
- Customer demographics

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Data Storytelling

---

## 🔄 Data Preparation

The data was prepared and transformed using Power Query before building the dashboards.

The main steps included:

- Data cleaning
- Data type transformations
- Handling data inconsistencies
- Creating calculated columns
- Creating an Hour column from order time
- Creating age groups
- Preparing data for analysis and visualization

---

## 🗄️ Data Modeling

A Snowflake-style data model was created in Power BI to organize the data and establish relationships between the different tables.

The model includes customer, product, branch, date, and order-related data.

Relationships were created between the tables to support analysis across different business dimensions.

---

## 📈 DAX & KPIs

DAX was used to create measures and KPIs for the analysis.

The project includes metrics such as:

- Total Sales
- Total Orders
- Total Profit
- Average Order Value
- Customer Metrics
- Branch Performance
- Product Performance

---

## 📊 Power BI Dashboards

The project contains three interactive Power BI dashboards.

### 1. Executive Dashboard

Provides a high-level overview of business performance.

It includes:

- Total Sales
- Total Orders
- Total Profit
- Sales trends
- Monthly performance
- Branch performance
- Key KPIs

### 2. Customer Dashboard

Focuses on customer behavior and demographics.

It includes:

- Customer analysis
- Age distribution
- Payment methods
- Customer behavior
- Order analysis
- Customer-related KPIs

### 3. Branch & Product Dashboard

Focuses on branch and product performance.

It includes:

- Branch sales
- Order counts
- Product/category performance
- Sales by category
- Profitability
- Product performance

---

## 🔍 Interactivity & Data Storytelling

The dashboards were designed to provide an interactive user experience.

Features include:

- Interactive slicers
- Page navigation
- KPI cards
- Charts and visualizations
- Drill-down analysis
- Interactive filters
- Dashboard navigation buttons

The design was also focused on clear data storytelling and presenting insights in a business-friendly way.

---

## 💡 Key Insights

Some of the key findings from the analysis include:

- Month 2 recorded the highest sales performance.
- Month 4 showed a decrease in sales and order volume that could be investigated further.
- Month 8 recorded the highest profit despite not having the highest number of orders.
- Month 1 recorded the lowest sales performance.
- Burger and Meals were among the top-performing categories in the analysis.
- Branch performance varied across different locations.
- Payment methods and customer demographics were analyzed to better understand customer behavior.

---

## 📄 Insights Report

A detailed PDF report containing the main business insights from the analysis is included in the repository.

---

## 📁 Repository Structure

```text
McDonalds-Egypt-PowerBI-Analysis/
│
├── PowerBI/
│   └── McDonalds_Egypt_Analysis.pbix
│
├── Screenshots/
│   ├── Executive_Dashboard.png
│   ├── Customer_Dashboard.png
│   └── Branch_Product_Dashboard.png
│
├── Insights/
│   └── McDonalds_Insights.pdf
│
└── README.md
