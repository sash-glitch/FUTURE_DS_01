# 📊 Online Retail Dashboard – Revenue, Customers & Cancellations Analysis

## 🔍 Project Overview

This project analyzes transactional data from an online retail business to uncover actionable insights on **revenue performance, product popularity, customer behavior, and order cancellations**.

The goal was to build an **interactive Power BI dashboard** that enables:

* High-level KPI monitoring
* Drill-through analysis into products and customers
* Tracking completed vs cancelled orders
* Data-driven recommendations for business improvement

---

## 📁 Dataset Description

The dataset contains transactional retail data with the following key columns:

| Column        | Description                                                |
| ------------- | ---------------------------------------------------------- |
| `InvoiceNo`   | Unique invoice ID (prefixed with “C” for cancelled orders) |
| `StockCode`   | Product identifier                                         |
| `Description` | Product description                                        |
| `Quantity`    | Number of units sold                                       |
| `UnitPrice`   | Price per unit                                             |
| `InvoiceDate` | Transaction date                                           |
| `CustomerID`  | Unique customer identifier                                 |
| `Country`     | Country of the customer                                    |

---

## 🎯 Business Questions Answered

* What is the **total revenue and trend** over time?
* Which **products generate the most revenue** and cancellations?
* Who are the **highest-value customers** and what is their behavior?
* How does revenue vary **across countries**?
* How do **cancellations impact revenue** per customer and per month?
* Which customers/products/countries should be prioritized for retention or intervention?

---

## 📊 Key Metrics (KPIs)

* **Total Revenue:** $9.726M
* **Total Goods Sold:** 142K
* **Average Order Value (AOV):** $375.52
* **Revenue per Customer:** $2,224
* **Average Sales per Invoice:** $233.05
* **Cancelled Orders Revenue:** $276K
* **Completed Orders Revenue:** $10.62M
* **Cancellation Rate:** Variable per customer/country/product

---

## 🧠 Key Insights

### Product Insights

* **Top Revenue Product:** Dotcom Postage ($291 revenue, 2 unique customers, only 1 cancellation)
* Jumbo Bag Red Retro Sports was #5 in popularity among top 10 products
* Large quantity orders are **more likely to be cancelled**, especially for paid orders

### Customer Insights

* Anonymous customers bring in **most revenue (~$1.42M)** but also **most cancellations**
* Frequent high-value customers (e.g., 14096) should be considered for **retention strategies**
* High-risk customers (e.g., 14,911) canceled 3,000 goods (~$11K loss)

### Country Insights

* **UK dominates revenue (~$8M)** and cancellations (~81K goods, $261K lost revenue)
* Top 10 revenue countries are European; Saudi Arabia has lowest revenue (~1 customer)
* Other concerning countries for cancellation loss: Singapore ($12.16K), EIRE ($5.037K), Hong Kong (~$5.575K)

### Cancellation Insights

* Completed orders: $10.62M
* Cancelled orders: $276K
* Average revenue per cancelled order: $562.51
* Average order value of cancelled orders: $233.05
* Highest loss month due to cancellations: December ($279,818)

---

## 🖥️ Dashboard Features

* **Interactive KPIs:** Total revenue, total goods sold, AOV, revenue per customer, average sales per invoice
* **Revenue Trend Line Chart:** Month-by-month analysis
* **Top 10 Products Bar Chart:** Revenue per product
* **Customer Revenue Analysis:** Top customers and cancellation patterns
* **Country Revenue Matrix:** Revenue and cancellation comparison by country
* **Invoice Status Drill-Through:** Click on Completed or Cancelled to view product-level impact
* **What-If Parameter Analysis:** Scenario testing for revenue changes

---

## 📸 Dashboard Visuals

### Online Dashboard Overview
![Main Dashboard](https://github.com/sash-glitch/FUTURE_DS_01/raw/ea884a2f47cae27d79861708ae61ce35f70c8bfd/ONLINE%20DASHBOARD%20OVERVIEW/main-dashboard.png)

### Cancelled Orders Overview
![Cancelled Orders](https://github.com/sash-glitch/FUTURE_DS_01/raw/ea884a2f47cae27d79861708ae61ce35f70c8bfd/CANCELLED%20ORDERS%20OVERVIEW/cancelled-orders.png)

### Completed Orders Overview
![Completed Orders](https://github.com/sash-glitch/FUTURE_DS_01/raw/ea884a2f47cae27d79861708ae61ce35f70c8bfd/COMPLETED%20ORDERS%20OVERVIEW/completed-orders.png)

### Drill Through Page
![Drill Through](https://github.com/sash-glitch/FUTURE_DS_01/raw/ea884a2f47cae27d79861708ae61ce35f70c8bfd/DRILL%20THROUGH%20PAGE/drill-through-page.png)

---

## 📌 Recommendations

* Offer discounts or loyalty programs to **high-value frequent customers**
* Monitor **anonymous customers** to balance revenue vs cancellation risk
* Focus marketing and inventory strategies on **high-revenue countries (UK, Europe)**
* Identify and manage **high-risk customers/products** to reduce revenue loss
* Consider order quantity limits or verification for **large orders** to reduce cancellations

---

## 🚀 Tools & Technologies

* **Power BI Desktop** – for interactive dashboard creation
* **Power Query** – for data cleaning and transformation
* **DAX** – for calculated columns, measures, and advanced metrics

---

## 👤 Author

**Sasha**
Data Analyst | Power BI | Business Intelligence

---

## 📂 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter by:

   * Date
   * Invoice Status (Completed / Cancelled)
3. Right-click on visuals for **drill-through analysis**

