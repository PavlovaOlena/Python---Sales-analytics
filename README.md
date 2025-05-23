# 📊 Sales Data Analysis Project

## Overview

This project focuses on analyzing sales data from a company operating in the global market, with sales taking place both in physical retail stores and online. The dataset contains information spanning several years and consists of three main tables:

- **`events.csv`** — Sales data over several years  
- **`products.csv`** — Product categories and their corresponding codes  
- **`countries.csv`** — Country, region, and location codes  

The **main goal** is to clean the data, perform exploratory data analysis (EDA), and uncover valuable business insights.

---

## 🛠️ Project Stages

### 1. Data Overview

- Load all three datasets and explore their structure.
- Understand the meaning of each column and describe them.
- Identify key fields to join the tables properly.

---

### 2. Data Cleaning

- **Missing Values**  
  - Check for missing data in each table.  
  - Estimate the proportion and potential causes.  
  - Fill in or remove missing data with proper justification.

- **Data Types**  
  - Ensure all columns have appropriate data types.  
  - Convert incorrect types and explain why.

- **Duplicates**  
  - Identify duplicate entries.  
  - Pay attention to:
    - Extra spaces or hidden characters
    - Case sensitivity (UPPER/lower)
    - Similarities between Cyrillic and Latin letters  
  - Clean the data to remove any duplicates.

- **Anomalies**  
  - Explore the dataset for anomalies or outliers.  
  - Try to understand and document their origin.

---

### 3. Data Analysis & Visualization

- Merge the three tables into a single clean DataFrame.
- Remove unnecessary columns and rename others if needed.

#### 📌 Key Metrics

Start with core business metrics such as:

- ✅ Total number of orders  
- 💰 Total profit  
- 🌍 Number of countries reached  
- ➕ Other relevant metrics of your choice  

#### 🛒 Sales Analysis

Analyze and visualize sales performance across:

- **Product categories**
- **Geographical location** (countries, regions)
- **Sales channels** (online vs offline)

Focus on revenue, costs, profit, and product popularity.

#### 🚚 Shipping Time Analysis

Analyze time between order placement and shipping:

- Group by **product category**, **country**, and **region**
- Create visualizations to display patterns and insights

Check whether shipping time affects profitability with suitable aggregations and visuals.

#### 📅 Time Series Trends

Study sales over time to identify key trends by:

- Product category  
- Country  
- Region  

Use time-series visualizations to show dynamics and tendencies.

#### 📆 Weekly & Seasonal Patterns

Analyze daily sales to detect patterns:

- Are there weekly cycles (e.g., higher sales on weekends)?
- Can some products be classified as seasonal?

Use the `.day_name()` method to extract weekday names from dates.

---

## 📋 Reporting

Prepare a **Google Colab** report that includes:

- Clean and well-documented code
- Visualizations with meaningful labels
- Business insights and conclusions

This report can be used as a **portfolio project** for your resume to demonstrate your skills in real-world data analysis.

---

## ✅ Tools & Technologies

- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn, Plotly)
- Google Colab / Jupyter Notebook
