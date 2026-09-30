# 🛒 E-Commerce Customer, Product & Sales Analytics

## 📊 Project Overview

This project is an **E-Commerce Customer, Product & Sales Analytics** designed to analyze customer behavior, product performance, and sales trends.

The project uses three CSV datasets:

- `customers.csv`
- `products.csv`
- `sales.csv`

The dashboards were created to transform raw e-commerce data into interactive business insights that can help understand:

- Customer demographics and spending behavior
- Product and brand performance
- Sales trends and revenue distribution
- Customer and product segments
- Payment methods and order statuses
- Inventory and product ratings

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze customer demographics and purchasing behavior.
2. Identify high-value customer segments.
3. Analyze product sales and inventory performance.
4. Compare brands and product categories.
5. Track overall sales and revenue trends.
6. Analyze payment methods and order statuses.
7. Identify top-performing products and customers.
8. Generate actionable business insights from the data.

---

## 📁 Dataset

The project contains three main datasets.

### 1. `customers.csv`

Contains customer-related information used for customer analysis.

The dataset is used to analyze:

- Customer demographics
- Age groups
- Gender
- Location
- Customer tier
- Registration trends
- Customer spending

### 2. `products.csv`

Contains product-related information.

It is used to analyze:

- Product categories
- Brands
- Product ratings
- Product prices
- Discounts
- Stock quantity
- Product sales
- Product performance

### 3. `sales.csv`

Contains transaction and sales information.

It is used to analyze:

- Total sales
- Order quantity
- Order value
- Payment methods
- Order status
- Sales by state
- Sales by category
- Sales by brand
- Monthly sales trends
- Top-selling products

---

# 📈 Dashboard Pages

The project contains four major dashboard sections.

## 1. Customer Analysis Dashboard

The Customer Analysis Dashboard provides insights into customer demographics and spending behavior.

### Key Metrics

- Total Customers: **39.115K**
- Total Orders: **244K**
- Total Spending: **₹4,63,93,27,069.20**
- Average Customer Spending: **₹118.61K**

### Key Visualizations

- Customers by Age Group
- Total Spending by Customer Tier
- Customer Registration Trend
- Customers by City
- Customers by Customer Tier
- Customers by State
- Customers by Gender
- Top Customers by Spending

### Key Insights

- Platinum customers have the highest spending.
- The **26–35** age group has the highest number of customers.
- **Uttar Pradesh (UP)** has the highest customer count.
- Aditya Yadav is shown as the highest-spending customer in the dashboard.

---

## 2. Product Analysis Dashboard

The Product Analysis Dashboard focuses on product sales, inventory, brands, categories, pricing, and ratings.

### Key Metrics

- Total Products: **2K**
- Total Stocks: **2K**
- Total Categories: **7**
- Total Brands: **33**
- Average Rating: **4.40**
- Average Selling Price: **₹2.00K**

### Key Visualizations

- Stock by Category
- Sales by Brand
- Discount Analysis
- Quantity Sold by Product
- Original Price vs Selling Price
- Total Sales by Category
- Top 10 Products by Sales
- Product Rating Analysis
- Brand Performance by Sales
- Best-Selling Products
- Highest-Rated Products
- Products Needing Attention

### Key Insights

- Electronics is the highest-sales category, with approximately **₹4.35B** in sales.
- HP is shown as the highest-performing brand by sales.
- Noise Watch V1 is shown as the best-selling product.
- Stationery Set V5 is shown as one of the highest-rated products.
- Comics V3 and Lays Chips V6 have low stock levels and require inventory monitoring.

---

## 3. Sales Analysis Dashboard

The Sales Analysis Dashboard provides an overview of business sales and transaction performance.

### Key Metrics

- Total Sales: **₹5.99B**
- Total Discount: **₹62.50M**
- Shipping Cost: **₹1.23M**
- Average Order Value: **₹23.97K**
- Total Quantity Sold: **312K**
- Total Orders: **250K**

### Key Visualizations

- Sales by State
- Sales by Customer Tier
- Sales by Year / Month
- Sales by Category
- Sales by Brand
- Top 10 Customers by Sales
- Top 10 Products by Sales
- Payment Mode Analysis
- Order Status Analysis
- Sales Trend

### Key Insights

- March 2026 is shown as the highest sales month.
- Uttar Pradesh has the highest revenue among the displayed states.
- UPI is the most-used payment method.
- Delivered orders represent the largest order-status segment.
- Noise Watch V1, Samsung Mobile V4, and boAt Headphones V8 are among the top products by sales.

---

# 📌 Summary Dashboard

The Summary page combines the major findings from the Customer, Product, and Sales dashboards.

### Customer Insights

- Platinum customers have the highest spending.
- Customers aged 26–35 represent the largest customer age group.
- Uttar Pradesh has the highest customer count.
- Aditya Yadav is shown as the highest-spending customer.

### Product Insights

- Electronics is the highest-sales category.
- HP is the highest-performing brand by sales in the dashboard.
- Noise Watch V1 is the top-selling product.
- Stationery Set V5 is among the highest-rated products.
- Some products have low inventory and require monitoring.

### Sales Insights

- March 2026 has the highest monthly sales in the dashboard.
- Uttar Pradesh has the highest displayed revenue by state.
- UPI is the most-used payment method.
- Delivered orders represent the largest order-status segment.
- Noise Watch V1, Samsung Mobile V4, and boAt Headphones V8 are among the top-selling products.

---

# 🛠️ Tools & Technologies

The project uses:

- **Power BI** – Dashboard development and data visualization
- **CSV** – Data storage
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and analytical calculations
- **Data Visualization** – Interactive charts, KPIs, slicers, and tables

---

# 📂 Project Structure

```text
E-Commerce-Analytics/
│
├── data/
│   ├── customers.csv
│   ├── products.csv
│   └── sales.csv
│
├── dashboard/
│   └── E-Commerce-Analysis.pbix
│
├── screenshots/
│   ├── Customer Analysis Dashboard.png
│   ├── Product Analysis Dashboard.png
│   ├── Sales Analysis Dashboard.png
│   └── Summary.png
│
└── README.md
