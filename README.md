# 🐍 Python for Data Analysis

This repository contains all my Python-based data analysis projects, where I apply techniques in data cleaning, aggregation, and visualization to uncover meaningful business insights.

---

## 📁 Projects

---

### 📦 Project 1: Analyzing Amazon Sales Data

This project analyzes a large Amazon sales dataset (128,975 records) to extract key business insights through structured data cleaning, exploration, and aggregation.

---

### 🧹 Tasks Completed

#### Data Cleaning
- Handled missing values (particularly in `Amount`, `Currency` fields)
- Verified and corrected data types for analysis
- Created cleaned subsets for different analytical purposes

#### Data Exploration
- Examined basic statistics and data distributions
- Identified key characteristics across sales dimensions
- Analyzed sales patterns by product categories

#### Data Aggregation & Business Analysis
- Identified 13,332 sales with amounts exceeding ₹1,000
- Found 3 sales in the "Top" category with quantity = 3
- Calculated total sales by product category — highest in "Set" (₹39,204,124)
- Analyzed average sales amount by category and order status
- Summarized total sales by fulfillment method and shipment type

---

### 📌 Key Insights
- The **"Set"** category generates the highest revenue (₹39,204,124), followed by **"Blouse"** (₹21,757,954)
- **Amazon-fulfilled orders** have higher average order values than Merchant-fulfilled ones
- Items in the **"Dress"** category with `"Shipped - Damaged"` status have the highest average sale value
- Most sales volume comes from **Amazon-fulfilled 'Shipped' items** (₹50,331,934)

---

### 📂 Files
- `Amazon Project.ipynb` – Main Jupyter notebook with cleaning, analysis, and visualizations
- Generated Excel summaries:
  - `average_sales_by_category_and_status.xlsx`
  - `total_sales_by_ship_and_fulfil.xlsx`

---

## 🛠 Technologies Used
- **Pandas** – data manipulation and aggregation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – visualizations (if applicable)
- **Excel** – data import/export for reporting

---



 ## Project 2: Analyzing Olist Ecommerce Orders Data

This project explores customer payment behavior using Olist’s ecommerce datasets from Brazil, with a focus on how customers pay and whether credit card usage is disproportionately high.

---

### 🧹 Tasks Completed

#### Data Cleaning
- Merged `orders.xlsx`, `order_payment.xlsx`, and `customers.xlsx`
- Handled missing values and removed duplicates
- Filtered data by payment type and customer state for targeted insights

#### Data Exploration & Aggregation
- Created time-based features (year, month, week) for trend analysis
- Analyzed total monthly payment values
- Grouped and aggregated data by payment type and time

#### Data Visualization
- **Line chart** showing total payment value by month  
- **Stacked bar chart** showing monthly payment method breakdown  
- **Scatter plot** showing payment value vs. number of installments  
- **Box plot** comparing payment value ranges across payment methods

---

### 📌 Key Insights
- **Credit cards** are the most dominant payment method across the dataset.
- Customers using credit cards tend to make **higher-value purchases** and use **more installments**.
- A small segment of users opt for **60+ installment payments**, indicating potential credit risk.
- Payment activity **peaked in late 2017**, followed by a decline in mid-2018.

---

### 📂 Files
- `Olist Analytics.ipynb` – Main notebook for data cleaning, analysis, and visualization  
- *Note:* This project uses Olist’s public datasets. Raw files (`orders.xlsx`, `order_payment.xlsx`, `customers.xlsx`) are used locally and are not included in the repo.  
  ➤ [View the source dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

### 🛠 Technologies Used
- **Pandas** – data manipulation and aggregation  
- **Seaborn / Matplotlib** – data visualization  
- **Jupyter Notebook** – interactive analysis environment





