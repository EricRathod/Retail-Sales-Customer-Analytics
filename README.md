# 📊 Retail Sales & Customer Analytics Dashboard

An end-to-end Business Data Analytics project analyzing retail sales, customer behavior, product performance, regional performance, and customer value segments using **Python, SQL, SQLite, and Power BI**.

The project transforms raw retail transaction data into meaningful business insights and an interactive Power BI dashboard to support data-driven decision-making.

---

## 📌 Project Overview

Retail businesses generate large amounts of transactional data, but raw data alone does not provide meaningful business insights.

This project was developed to analyze retail sales data and answer important business questions such as:

- How much revenue and profit is the business generating?
- Which product categories generate the most revenue?
- Which products perform best?
- Which regions contribute the most revenue?
- How does revenue change over time?
- Who are the most valuable customers?
- Which customer groups should the business prioritize?

The project combines **data analysis, customer segmentation, SQL database development, visualization, and business intelligence reporting**.

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Clean and prepare retail transaction data
- Calculate important business KPIs
- Analyze monthly sales performance
- Compare product and category performance
- Evaluate regional sales performance
- Analyze customer purchasing behavior
- Segment customers based on their total value
- Store analytical data in a SQLite database
- Build an interactive Power BI dashboard
- Convert analytical results into business insights

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and analytics |
| Pandas | Data cleaning, transformation, and aggregation |
| NumPy | Numerical operations and dataset generation |
| Matplotlib | Data visualization |
| SQL | Data querying and structured analysis |
| SQLite | Analytical database |
| Power BI | Interactive dashboard and business reporting |
| Google Colab / Jupyter | Analysis and development environment |

---

## 📂 Dataset

The project analyzes **5,000 retail transactions** across multiple customers, products, categories, and Canadian regions.

The dataset contains information such as:

- Order ID
- Order Date
- Customer ID
- Customer Segment
- Region
- Product Category
- Product
- Quantity
- Unit Price
- Discount
- Revenue
- Cost
- Profit

Additional date and profitability features were created during the analysis.

---

## 📈 Key Performance Indicators

The analysis produced the following overall business KPIs:

| KPI | Result |
|---|---:|
| 💰 Total Revenue | $6.33M |
| 💵 Total Profit | $1.98M |
| 🧾 Total Orders | 5,000 |
| 👥 Total Customers | 990 |
| 🛒 Average Order Value | $1,266.76 |
| 📊 Profit Margin | 31.30% |

---

## 📊 Power BI Dashboard

The interactive Power BI dashboard provides a consolidated view of retail performance.

### Dashboard Components

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin
- Monthly Revenue Trend
- Revenue by Product Category
- Revenue by Region
- Top 10 Products by Revenue
- Customer Value Segments
- Sales Transaction Details

### Dashboard Preview

![Retail Sales Dashboard](images/dashboard.png)

---

## 📅 Monthly Revenue Analysis

Monthly revenue was analyzed from **2023 through 2025** to identify changes in sales performance over time.

The analysis allows business users to identify:

- High-performing months
- Revenue fluctuations
- Potential seasonal patterns
- Periods requiring further investigation

![Monthly Revenue Trend](images/monthly_revenue_trend.png)

---

## 🛍️ Product Category Analysis

Revenue was compared across four major product categories:

- Electronics
- Furniture
- Clothing
- Office Supplies

### Category Revenue

| Category | Revenue |
|---|---:|
| Electronics | $4.20M |
| Furniture | $1.53M |
| Clothing | $379.86K |
| Office Supplies | $217.81K |

**Electronics is the dominant revenue category**, generating approximately two-thirds of total business revenue.

![Revenue by Product Category](images/revenue_by_category.png)

---

## 🏆 Top Products

Product-level analysis was performed to identify the highest revenue-generating products.

Some of the strongest products include:

- Keyboard
- Mouse
- Headphones
- Laptop
- Monitor

This analysis helps identify which products contribute most strongly to overall business performance.

![Top 10 Products](images/top_10_products.png)

---

## 🌎 Regional Analysis

Sales performance was analyzed across five Canadian regions:

| Region | Revenue |
|---|---:|
| Manitoba | $1.40M |
| British Columbia | $1.29M |
| Quebec | $1.28M |
| Ontario | $1.22M |
| Alberta | $1.15M |

Manitoba generated the highest overall revenue in the dataset.

Regional analysis can help management identify stronger markets and investigate opportunities for improving performance in lower-revenue regions.

---

## 👥 Customer Analytics

Customer-level analysis was performed using:

- Total Orders
- Total Revenue
- Total Profit
- Average Order Value
- Last Purchase Date
- Recency

Customers were then divided into four value groups:

- Low Value
- Medium Value
- High Value
- VIP

---

## 💎 Customer Value Segmentation

Customer segmentation was created using customer-level total revenue.

| Segment | Customers | Revenue |
|---|---:|---:|
| Low Value | 248 | $396.77K |
| Medium Value | 247 | $1.03M |
| High Value | 247 | $1.74M |
| VIP | 248 | $3.17M |

One of the most important findings is that **VIP customers represent approximately 25% of customers but generate around half of total revenue**.

This suggests that customer retention and personalized engagement strategies for high-value and VIP customers could have a significant business impact.

![Customer Value Segments](images/customer_segments.png)

---

## 💡 Key Business Insights

### 1. Electronics Drives Revenue

Electronics generated approximately **$4.20M**, making it the largest revenue contributor among all product categories.

### 2. VIP Customers Are Highly Valuable

Approximately one-quarter of customers belong to the VIP segment, yet this group contributes approximately **$3.17M in revenue**.

### 3. Regional Revenue Is Relatively Distributed

Revenue is distributed across all five analyzed Canadian regions, with Manitoba producing the highest total revenue.

### 4. Product Performance Is Concentrated

Several electronics products appear among the highest revenue-generating products, reinforcing the importance of the Electronics category.

### 5. Revenue Changes Significantly by Month

Monthly analysis shows noticeable fluctuations in revenue, highlighting the importance of monitoring trends and investigating seasonal or operational factors.

---

## 🗄️ SQLite Database

The analytical outputs were also stored in a SQLite database:

`retail_sales_analytics.db`

The database contains the following tables:

- `sales_transactions`
- `business_kpis`
- `monthly_sales`
- `category_summary`
- `product_summary`
- `region_summary`
- `customer_summary`
- `customer_segment_summary`

This demonstrates how the analytical workflow can support both **database querying and BI reporting**.

---

## 📁 Project Structure

```text
Retail-Sales-Customer-Analytics/
│
├── README.md
├── Eric_Rathod_Project2_Retail_Sales_Customer_Analytics.ipynb
├── dashboard.pbix
├── retail_sales_analytics.db
│
├── data/
│   ├── retail_sales_data.csv
│   ├── retail_kpis.csv
│   ├── monthly_sales.csv
│   ├── category_summary.csv
│   ├── product_summary.csv
│   ├── region_summary.csv
│   ├── customer_summary.csv
│   └── customer_segment_summary.csv
│
└── images/
    ├── dashboard.png
    ├── monthly_revenue_trend.png
    ├── revenue_by_category.png
    ├── top_10_products.png
    └── customer_segments.png
```

---

## 🔄 Analytics Workflow

```text
Retail Transaction Data
        ↓
Data Cleaning & Preparation
        ↓
Python / Pandas Analysis
        ↓
Business KPI Calculation
        ↓
Product & Regional Analysis
        ↓
Customer Analytics
        ↓
Customer Value Segmentation
        ↓
SQLite Database
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

## ▶️ How to Run

1. Clone this repository.

2. Open the Jupyter Notebook:

```text
Eric_Rathod_Project2_Retail_Sales_Customer_Analytics.ipynb
```

3. Run the notebook cells sequentially.

4. The notebook generates analytical CSV files, visualizations, and the SQLite database.

5. Open:

```text
dashboard.pbix
```

using Microsoft Power BI Desktop to explore the interactive dashboard.

---

## 💼 Skills Demonstrated

- Business Data Analysis
- Data Cleaning
- Exploratory Data Analysis
- KPI Development
- Customer Analytics
- Customer Segmentation
- Product Performance Analysis
- Regional Analysis
- Python
- Pandas
- SQL
- SQLite
- Power BI
- Data Visualization
- Dashboard Development
- Business Intelligence
- Data Storytelling

---

## 👤 Author

**Eric Rathod**

Master's Student in Artificial Intelligence – Design & Development  
Seneca Polytechnic, Toronto, Canada

Interested in opportunities involving:

**Data Analytics | Business Intelligence | Artificial Intelligence | Machine Learning**

---

## ⭐ Project Purpose

This project was developed as part of my data analytics portfolio to demonstrate an end-to-end workflow from **data preparation and analysis to database development, visualization, and business intelligence reporting**.
