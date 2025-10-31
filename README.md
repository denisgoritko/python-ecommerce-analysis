# Global E-Commerce Sales Analysis (Python)

This repository contains a full data analysis project on a global e-commerce dataset. The primary goal is to clean the data, conduct exploratory data analysis (EDA), and uncover valuable business insights.

The complete analysis, code, visualizations, and business conclusions are available in the [Sales_Analysis.ipynb](Sales_Analysis.ipynb) notebook.

##  Project Goal

To clean and analyze sales data from a global company (with both physical and online stores) to find actionable insights regarding sales performance, customer behavior, and logistics.

##  Project Stages

The analysis was conducted in several distinct stages:

### 1. Data Overview
* Loaded the three datasets into Pandas DataFrames.
* Examined the content, data types, and structure of each table.
* Identified the key fields for joining the tables.

### 2. Data Cleaning
* **Missing Values:** Assessed the proportion of missing data in each table, investigated potential causes, and applied appropriate imputation or removal strategies.
* **Data Types:** Corrected any columns with incorrect data types (e.g., dates as strings).
* **Duplicates:** Identified and removed duplicate records, handling issues like trailing spaces and case sensitivity.
* **Anomalies:** Investigated data for anomalies or outliers and determined their cause.

### 3. Data Analysis & Visualization
* Joined the three tables (`events`, `products`, `countries`) into a single, comprehensive DataFrame for analysis.
* Calculated key business metrics (e.g., total orders, total profit, total countries).
* Analyzed sales (revenue, profit, product popularity) segmented by:
    * Product Categories
    * Geography (Countries, Regions)
    * Sales Channel (Online vs. Offline)

### 4. Specific Analyses & Insights
* **Logistics:** Analyzed the time interval between order placement and shipping, visualized by category, country, and region.
* **Profit vs. Shipping:** Investigated the relationship between profit margins and shipping time.
* **Time-Series:** Analyzed sales dynamics over time (by category, country) to identify trends.
* **Seasonality:** Conducted a day-of-week analysis (`day_name()`) to check for weekly patterns.

## 🛠️ Tools Used

* **Python 3**
* **Pandas:** For data manipulation and cleaning.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook / Google Colab:** For the analysis report.
