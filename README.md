# 🛒 Amazon E-Commerce Sales Analytics Dashboard

## 📌 Project Overview

The **Amazon E-Commerce Sales Analytics Dashboard** is an interactive Business Intelligence solution developed using **Power BI** to analyze and visualize Amazon e-commerce sales data. The dashboard transforms raw transactional data into meaningful business insights through dynamic visualizations, KPI cards, and advanced DAX calculations.

This project enables stakeholders to monitor sales performance, customer purchasing behavior, product performance, delivery efficiency, payment preferences, and time-based business metrics. It also incorporates Time Intelligence functions to compare current performance with previous periods and identify business trends.

---

## 🎯 Project Objectives

- Analyze overall sales performance across different countries and states.
- Monitor customer purchasing behavior and order trends.
- Identify top-performing products and categories.
- Analyze payment methods and delivery performance.
- Track Month-to-Date (MTD), Quarter-to-Date (QTD), and Year-to-Date (YTD) performance.
- Generate meaningful business insights to support data-driven decision making.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Dashboard Design

---

# 📂 Dataset Information

The dataset consists of Amazon e-commerce transaction records containing:

- Order ID
- Order Date
- Customer ID
- Customer Name
- Product Name
- Product Category
- Quantity
- Unit Price
- Sales Amount
- Country
- State
- Payment Method
- Shipping Cost
- Order Status

---

# 📊 Dashboard Overview

The dashboard consists of **five interactive pages**, each focusing on a different business area.

---

# 🏠 1. Executive Dashboard


<img width="1123" height="641" alt="image" src="https://github.com/user-attachments/assets/42ef1d8b-655c-4519-a47f-69efc06c31be" />





### Purpose

Provides a high-level overview of business performance using key performance indicators and interactive visualizations.

### KPIs

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value

### Visualizations

- Revenue by Country
- Revenue by Product Category
- Monthly Revenue Trend
- Top Selling Products
- Payment Method Distribution

### Key Insights

- The United States contributes the highest revenue among all countries.
- Revenue is well distributed across multiple product categories.
- Credit Card is the most preferred payment method.
- Customer orders are consistent across different product categories.

---

# 📦 2. Product Performance Dashboard

<img width="1153" height="652" alt="Screenshot 2026-06-29 203813" src="https://github.com/user-attachments/assets/c8de9f48-fd87-4c90-b60d-1c79866acce5" />




### Purpose

Provides detailed analysis of product and category performance.

### KPIs

- Revenue per Product
- Revenue by Category
- Top Products
- State-wise Revenue

### Visualizations

- Revenue by Product
- Revenue by Category
- Top Revenue States
- Sales Trend

### Key Insights

- Memory Card, LED Desk Lamp and Mechanical Keyboard are among the top-selling products.
- Product revenue is evenly distributed, indicating a balanced portfolio.
- Texas and California contribute significantly to total product revenue.

---

# 🚚 3. Delivery & Payment Dashboard

<img width="1152" height="652" alt="Screenshot 2026-06-29 203835" src="https://github.com/user-attachments/assets/a425edc3-b02b-4039-ae77-1a9fd5b55456" />




### Purpose

Analyzes delivery operations, payment methods and shipping costs.

### KPIs

- Total Shipping Cost
- Average Shipping Cost
- Completed Order Revenue
- Completion Rate

### Visualizations

- Payment Method Distribution
- Order Status Distribution
- Shipping Cost vs Sales
- Country-wise Shipping Analysis

### Key Insights

- Most customers prefer digital payment methods.
- Delivered orders generate the majority of total revenue.
- Returns and cancelled orders represent only a small portion of total sales.
- Shipping costs remain relatively consistent across categories.

---

# 📅 4. Time Intelligence Dashboard

<img width="1160" height="657" alt="Screenshot 2026-06-29 203854" src="https://github.com/user-attachments/assets/1538831a-9ccc-474b-8a25-2e9c16d004ce" />




### Purpose

Monitors business performance across different time periods using DAX Time Intelligence calculations.

### KPIs

Current MTD

Previous MTD

MTD Growth %

Current QTD

Previous QTD

QTD Growth %

Current YTD

Previous YTD

YTD Growth %

### DAX Functions Used

- TOTALMTD()
- TOTALQTD()
- TOTALYTD()
- SAMEPERIODLASTYEAR()
- CALCULATE()
- DIVIDE()
- DATEADD()

### Key Insights

- Month-to-Date sales show a slight decline compared to the previous period.
- Quarter-to-Date performance remains relatively stable.
- Year-to-Date sales indicate a small decrease compared to the same period last year.
- Growth indicators help monitor overall business performance.

---

# 💡 5. Business Insights

<img width="1162" height="658" alt="Screenshot 2026-06-29 203914" src="https://github.com/user-attachments/assets/ff533a7b-ebda-4d6d-a7cd-0c01c5a9e20a" />




### Summary

The insights page provides a concise summary of the dashboard findings and highlights important business observations.

### Major Findings

- Total Revenue exceeded **91 Million**.
- More than **100K orders** were processed.
- Over **43K customers** contributed to total sales.
- The United States remains the highest revenue-generating country.
- Top-selling products contribute consistently to overall revenue.
- Digital payment methods dominate customer transactions.
- Delivery completion rate remains high.
- Current MTD, QTD and YTD performance indicate a slight decline compared to previous periods.

### Recommendations

- Increase promotional campaigns in underperforming regions.
- Focus marketing efforts on top-performing products.
- Improve customer retention strategies.
- Monitor declining sales trends using Time Intelligence metrics.
- Continue optimizing delivery operations.

---

# 📈 Data Model

The dashboard follows a **Star Schema** data model.

### Fact Table

- Sales

### Dimension Tables

- Date
- Customer
- Product
- Geography

This model enables efficient filtering and improves DAX calculation performance.

---

# ⚙️ Data Cleaning & Transformation

The following transformations were performed using Power Query:

- Removed duplicate records
- Handled missing values
- Corrected data types
- Renamed columns
- Created Date Table
- Added Year, Quarter and Month columns
- Cleaned categorical values

---

# 🧮 DAX Measures Implemented

## Sales Measures

- Total Revenue
- Total Orders
- Average Order Value
- Completed Order Revenue

## Time Intelligence

- Current MTD
- Previous MTD
- Current QTD
- Previous QTD
- Current YTD
- Previous YTD
- Same Period Last Year (SPLY)

## Growth Measures

- MTD Growth %
- QTD Growth %
- YTD Growth %

## Operational KPIs

- Completion Rate
- Return Rate
- Average Shipping Cost

---

# 🚀 Dashboard Features

- Interactive Slicers
- Cross Filtering
- Dynamic KPI Cards
- Time Intelligence Analysis
- Country-wise Analysis
- Product Performance Analysis
- Delivery & Payment Analysis
- Business Insights Page
- Professional Dashboard Navigation

---

# 📌 Key Business Insights

- Revenue exceeded **91.83 Million**.
- More than **100K customer orders** were analyzed.
- The United States generated the highest revenue.
- Revenue distribution across product categories is well balanced.
- Digital payment methods are preferred over Cash on Delivery.
- Delivered orders account for the largest share of sales.
- Slight declines in MTD, QTD and YTD indicate opportunities for improving sales performance.

---

# 🎓 Skills Demonstrated

- Power BI Dashboard Development
- Data Cleaning
- Power Query
- Data Modeling
- DAX Calculations
- Time Intelligence
- KPI Design
- Business Intelligence
- Data Visualization
- Business Analytics

---


# 📁 Repository Structure

```
Amazon-ECommerce-Sales-Analytics/
│
├── Amazon_ECommerce_Sales_Analytics.pbix
├── README.md
├── Dataset/
│   └── Amazon_Ecommerce_Sales.csv
│
├── Dashboards/
   ├── executive_dashboard.png
   ├── product_dashboard.png
   ├── delivery_dashboard.png
   ├── time_dashboard.png
   └── insights_dashboard.png

```

---

# 👩‍💻 Author

**Madhuri**

Power BI | SQL | Python | Data Analytics |

---

⭐ **If you found this project helpful, consider giving it a star on GitHub!**
