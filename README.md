⛽ Gas Station Sales Analysis & Forecasting
**Project Overview:**

This project analyzes 6 years of transaction data (2020–2025) from a gas station convenience store to identify sales trends, understand product performance, and predict future sales using data analytics and machine learning techniques.

The goal of this project was to help the store manager better understand business performance and make data-driven decisions for inventory planning and sales improvement.

This analysis follows the data analytics workflow: Ask → Prepare → Process → Analyze → Share → Act.

**Business Problem:**

The store manager recently took over operations and wanted to answer several key questions:

When does the store experience the highest and lowest sales activity?

Which product departments generate the most revenue?

Which products generate low sales and may require inventory adjustments?

What strategies could increase revenue during slow months?

Can historical sales data be used to predict future sales trends?

**Dataset:**

The dataset used in this project was exported from the store's POS transaction system and includes approximately six years of sales data.

Data fields include

Transaction date

Product category

Item description

Sales amount

To protect business privacy, the dataset has been anonymized and cleaned before analysis.

**Tools & Technologies:**
This project uses the following tools:

Microsoft Excel

Data cleaning

Pivot tables

Data summarization

Visualization

Python

Data preprocessing

Exploratory data analysis

Machine learning model for sales prediction

Libraries used

pandas

numpy

matplotlib

scikit-learn

**Data Cleaning & Preparation:**

Before analysis, several preprocessing steps were performed:

Removed duplicate records

Checked and handled missing values

Standardized category labels

Removed unnecessary columns

Created pivot tables to summarize yearly and monthly sales

These steps ensured that the dataset was clean, consistent, and ready for analysis.

**Exploratory Data Analysis:**

The analysis focused on identifying sales patterns across multiple dimensions:

Yearly Sales Trends
Year	Total Sales
2020	$127,684
2021	$238,108
2022	$425,090
2023	$403,354
2024	$377,026
2025	$409,205

Sales increased significantly between 2020 and 2022, followed by stabilization in later years.

**Monthly Sales Trends:**

Analysis of monthly data revealed seasonal patterns:

Higher sales during spring and fall months

Lower sales during winter months

These trends suggest seasonal demand influenced by travel and customer activity.

**Department Revenue Analysis:**

The top-performing departments include:

Regular Gas

Cigarettes

Lottery Sales

Beer

Tobacco

Regular gas generates the highest revenue, which is expected for gas stations. However, convenience store products play an important role in overall sales.

**Machine Learning Model:**

A sales forecasting model was developed using Python to predict future sales based on historical trends.

The model helps the store manager:

Forecast future revenue

Improve inventory planning

Identify potential demand changes

**Key Insights:**

Sales grew significantly from 2020 to 2022

Gas sales dominate total revenue

Convenience items such as cigarettes, beer, and lottery tickets generate consistent sales

Winter months show reduced sales activity

Some product categories generate very low revenue and may require inventory adjustments

**Business Recommendations:**

Based on the analysis, several strategies could improve sales performance:

1. Promote High-Margin Store Items

Encourage customers purchasing fuel to buy drinks, snacks, or coffee through bundled promotions.

2. Increase Winter Sales

Introduce seasonal promotions during slower months to increase customer purchases.

3. Optimize Inventory

Reduce stock of low-performing items and prioritize high-demand products.

4. Use Predictive Models

Leverage sales forecasting models to support better inventory and purchasing decisions.

**Project Structure:**
gas-station-sales-analysis
├── notebooks
│   └── future_sales_prediction_model.ipynb
│
├── visuals
│   └── sales_trends.png
│
├── case-study.pdf
│
└── README.md
Skills Demonstrated

Data Cleaning

Exploratory Data Analysis

Data Visualization

Business Insight Development

Sales Trend Analysis

Machine Learning for Forecasting
