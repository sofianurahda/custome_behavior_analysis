# Customer Behavior Data Analytics Project

## 📌 Overview

This project focuses on analyzing customer shopping behavior using a combination of Python, SQL, and Power BI. The goal is to extract meaningful insights from the dataset and present them through an interactive dashboard that supports data-driven decision making.

---

## 📊 Dataset

The dataset contains customer transaction data, including:

* Customer ID
* Age and Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Review Rating
* Subscription Status
* Shipping Type
* Previous Purchases

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy) → Data cleaning & EDA
* **PostgreSQL** → Data storage & SQL queries
* **Power BI** → Data visualization & dashboard
* **Jupyter Notebook** → Analysis workflow
* **Gamma** → Presentation slides

---

## 🔄 Project Steps

### 1. Data Loading

* Loaded dataset using Pandas in Jupyter Notebook
* Checked structure and initial data quality

### 2. Data Cleaning

* Standardized column names
* Handled missing values
* Fixed data types

### 3. Exploratory Data Analysis (EDA)

* Analyzed purchase behavior
* Identified trends by category, gender, and age group
* Calculated key metrics such as average purchase and ratings

### 4. SQL Analysis

* Imported dataset into PostgreSQL
* Wrote SQL queries to:

  * Segment customers (New, Returning, Loyal)
  * Analyze discount usage
  * Identify top-performing categories

### 5. Dashboard Development

* Built an interactive Power BI dashboard
* Key features:

  * KPI cards (Average Purchase, Rating, Customers)
  * Category and subscription analysis
  * Filters (Category, Shipping Type)

### 6. Reporting

* Summarized findings into insights
* Created presentation slides using Gamma

---

## 📈 Dashboard Highlights

* Average Purchase Amount
* Average Review Rating
* Customer Segmentation
* Revenue by Category
* Subscription vs Non-subscription behavior

---

## 🔍 Key Insights

* Certain product categories dominate revenue contribution
* Discount usage significantly influences purchase behavior
* Returning customers contribute a large portion of total purchases

---

## ▶️ How to Run

1. Clone this repository
2. Open Jupyter Notebook and run the analysis file
3. Ensure PostgreSQL is running and update connection credentials
4. Run SQL scripts to create tables and queries
5. Open Power BI file (.pbix) to explore the dashboard

---

## 💡 Notes

This project demonstrates end-to-end data analytics workflow from raw data to business insights, combining multiple tools commonly used in real-world scenarios.
