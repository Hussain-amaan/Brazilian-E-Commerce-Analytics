# 📊 Brazilian E-Commerce Analytics Dashboard

An end-to-end Business Intelligence project built using the Brazilian E-Commerce Public Dataset (Olist). This project demonstrates the complete analytics workflow—from data cleaning and feature engineering in Python to interactive dashboard creation in Power BI using DAX.

## 📌 Project Overview

The objective of this project is to analyze sales, customers, products, logistics, and payment performance of an e-commerce platform. The project transforms raw transactional data into actionable business insights through interactive dashboards and KPI reporting.

## 🚀 Features

- Data cleaning and preprocessing using Python
- Feature engineering for business metrics
- Merging multiple relational datasets into a master dataset
- Interactive Power BI dashboard
- DAX measures for business KPIs
- Sales trend analysis
- Product category performance
- Customer geographic analysis
- Payment method analysis
- Business insights and KPI reporting

---

## 🛠️ Tech Stack

### Programming
- Python

### Libraries
- Pandas
- NumPy

### Business Intelligence
- Power BI
- DAX (Data Analysis Expressions)

### Tools
- Jupyter Notebook
- Git
- GitHub

---

## 📂 Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

The dataset contains information about:

- Customers
- Orders
- Order Items
- Products
- Sellers
- Payments
- Reviews
- Product Categories

---

## 📁 Project Structure

```
Brazilian-Ecommerce-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_data_merging.ipynb
│   └── 05_exploratory_data_analysis.ipynb
│
├── powerbi/
│   └── Brazilian_Ecommerce_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
└── README.md
```

---

## 📊 Dashboard KPIs

The dashboard includes the following key performance indicators:

- 💰 Total Revenue
- 📦 Total Orders
- 👥 Total Customers
- 💵 Average Order Value
- ⭐ Average Customer Rating
- 🚚 Average Delivery Time
- 📈 Product Category Performance
- 💳 Payment Method Distribution

---

## 📈 Dashboard Visuals

- Revenue Trend by Month
- Revenue by Quarter
- Top Product Categories
- Top Products by Revenue
- Revenue by Customer State
- Payment Method Distribution

---

## 🔍 Data Processing Workflow

### 1. Data Loading
- Imported all CSV files
- Explored dataset structure
- Checked data quality

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted date columns
- Standardized product categories

### 3. Feature Engineering
Created new business features including:

- Delivery Days
- Delivery Delay
- Purchase Month
- Purchase Quarter
- Purchase Weekday
- Product Volume
- Product Weight
- Review Sentiment

### 4. Data Integration
Merged multiple tables into a single master dataset for analysis.

### 5. Dashboard Development
Created interactive Power BI dashboards using DAX measures and visualizations.

---

## 📊 Key Business Insights

- Health & Beauty is one of the highest revenue-generating product categories.
- Credit Cards are the most preferred payment method.
- Revenue varies significantly across customer states.
- Average Order Value provides insight into customer purchasing behavior.
- Quarterly and monthly revenue trends help identify seasonal demand.

---



## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Brazilian-Ecommerce-Analytics.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open

- Jupyter Notebook for data processing
- Power BI Desktop for dashboard visualization

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Business Intelligence
- Dashboard Design
- DAX
- KPI Development
- Data Visualization
- Business Analytics

---


