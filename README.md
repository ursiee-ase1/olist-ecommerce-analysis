# Olist E-Commerce Performance Analysis

## Project Overview

This project analyzes the Olist Brazilian E-Commerce dataset to evaluate business performance and identify opportunities for growth. The analysis combines Python for data preparation and feature engineering with Power BI for interactive dashboard development.

The goal is to answer one central business question:

> **How is Olist performing, and where are the biggest opportunities to improve?**

The project was completed as part of a data analytics mentorship program and demonstrates an end-to-end analytics workflow—from raw data processing to business intelligence reporting.

---

## Business Objectives

The dashboard is designed to help stakeholders:

- Monitor sales performance over time
- Understand customer purchasing behavior
- Evaluate delivery efficiency
- Identify high-performing sellers and product categories
- Support data-driven business decisions

---

## Dashboard Pages

### 1. Sales Overview

Provides an overall picture of business performance.

**Key Metrics**
- Total Revenue
- Total Orders
- Average Order Value
- Monthly Sales Trend

**Key Questions Answered**
- How has revenue changed over time?
- Which months generate the highest sales?
- What payment methods do customers prefer?

---

### 2. Customer Analysis

Explores customer behavior and purchasing patterns.

**Key Metrics**
- Customers by State
- RFM Segmentation
- Repeat vs One-Time Customers

**Key Questions Answered**
- Where are customers located?
- Which customers are most valuable?
- How many customers return to purchase again?

---

### 3. Delivery Performance

Evaluates shipping efficiency and delivery reliability.

**Key Metrics**
- Average Delivery Time
- On-Time Delivery Rate
- Late Deliveries by State

**Key Questions Answered**
- How long does delivery typically take?
- Which regions experience more delays?
- What percentage of orders arrive on time?

---

### 4. Seller & Product Analysis

Examines seller performance and product trends.

**Key Metrics**
- Top Sellers
- Best-Selling Categories
- Review Scores by Category

**Key Questions Answered**
- Which sellers generate the most revenue?
- Which product categories perform best?
- How do customer reviews vary across categories?

---

## Project Workflow

```
Raw CSV Files
        │
        ▼
Python (Pandas)
Data Cleaning
Data Integration
Feature Engineering
        │
        ▼
Clean CSV Outputs
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## Dataset

The project uses the **Olist Brazilian E-Commerce Public Dataset**, which contains information on:

- Orders
- Customers
- Sellers
- Products
- Payments
- Reviews
- Geolocation
- Order Items
- Product Categories

The dataset consists of **9 relational tables**, requiring data integration before analysis.

---

## Data Preparation

Python was used to perform:

- Data cleaning
- Handling missing values
- Joining multiple tables
- Date formatting
- Feature engineering
- Revenue calculations
- Delivery delay calculations
- Monthly sales aggregation
- Customer RFM segmentation

The cleaned datasets were exported as CSV files for visualization in Power BI.

---

## Repository Structure

```
olist-ecommerce-analysis/
│
├── README.md
│
├── data/
│   └── raw/
│       ├── olist_customers_dataset.csv
│       ├── olist_orders_dataset.csv
│       ├── ...
│
├── notebooks/
│   └── 01_data_preparation.ipynb
│
├── outputs/
│   └── cleaned/
│       ├── sales_summary.csv
│       ├── customer_analysis.csv
│       ├── delivery_performance.csv
│       └── seller_product_analysis.csv
│
└── dashboard/
    └── olist_dashboard.pbix
```

---

## Key Features Engineered

- Revenue per Order
- Revenue by Month
- Delivery Duration
- Delivery Delay
- RFM Scores
- Customer Segments
- Seller Revenue
- Average Review Rating
- On-Time Delivery Indicator

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Modeling
- Feature Engineering
- Business Intelligence
- Dashboard Design
- Data Visualization
- Business Storytelling
- Python (Pandas)
- Power BI

---

## Dashboard Preview

*(Add screenshots here after completing the dashboard.)*

Example:

```
dashboard/images/sales_overview.png
dashboard/images/customer_analysis.png
dashboard/images/delivery_performance.png
dashboard/images/seller_analysis.png
```

---

## Future Improvements

- Build an interactive forecasting model
- Perform customer churn prediction
- Develop seller performance scoring
- Add geographic mapping using latitude and longitude data
- Deploy the dashboard online using Power BI Service

---

## Author

**Ursula Amoaku**

Business Information Technology Student

Aspiring Data Analyst | Business Intelligence | Cloud & Analytics

GitHub: *(Add your GitHub profile)*

LinkedIn: *(Add your LinkedIn profile)*
