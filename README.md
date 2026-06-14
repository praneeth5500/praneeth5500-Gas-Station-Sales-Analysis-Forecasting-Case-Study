 ⛽ Gas Station Sales Analysis & Forecasting – Case Study

## 1. Project Overview

This project analyzes six years of point‑of‑sale (POS) transaction data from a gas station convenience store to uncover sales trends, understand product performance, and forecast future revenue using data analytics and machine learning.[page:13]  

The goal is to help the store manager make data‑driven decisions about inventory planning, promotions, and revenue optimization.[page:13]  
The workflow follows the standard analytics lifecycle: **Ask → Prepare → Process → Analyze → Share → Act**.[page:13]  

---

## 2. Business Problem

A new store manager wants to quickly understand and improve store performance.  
Key questions include:[page:13]  

- When does the store experience the highest and lowest sales activity?  
- Which product departments generate the most revenue?  
- Which items are consistently low‑performing and may require inventory adjustments?  
- How do sales vary across months and seasons?  
- Can historical sales data be used to predict future revenue and support planning?[page:13]  

---

## 3. Dataset

The dataset was exported from the store’s POS system and contains approximately **six years of transactional data (2020–2025)**.[page:13]  

Core fields include:[page:13]  

- `transaction_date`  
- `product_category` / department  
- `item_description`  
- `sales_amount`  

For privacy, all sensitive information has been anonymized and cleaned before analysis.[page:13]  

---

## 4. Tools & Technologies

**Excel**[page:13]  
- Data cleaning and quick checks  
- Pivot tables for summarization  
- Initial visualizations  

**Python**[page:13]  
- Data preprocessing and feature engineering  
- Exploratory Data Analysis (EDA)  
- Machine learning model for sales forecasting  

**Python libraries**[page:13]  
- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `matplotlib` – visualizations  
- `scikit-learn` – modeling and evaluation  

---

## 5. Data Cleaning & Preparation

Before analysis, the following steps were performed to ensure data quality:[page:13]  

- Removed duplicate records  
- Checked and handled missing values  
- Standardized category and department labels  
- Dropped unused or irrelevant columns  
- Created summary tables (yearly and monthly) using Excel pivot tables and Python group‑bys[page:13]  

These steps produced a consistent, analysis‑ready dataset for EDA and modeling.[page:13]  

---

## 6. Exploratory Data Analysis

### 6.1 Yearly Sales Trends

Yearly sales totals (2020–2025) were computed to understand overall growth:[page:13]  

- Revenue increased strongly from 2020 to 2022.  
- After 2022, sales stabilized with moderate fluctuations across 2023–2025.[page:13]  

*(See `visuals/sales_trends.png` and the notebook for charts.)*[page:13]  

### 6.2 Monthly & Seasonal Patterns

Monthly aggregation revealed clear seasonality:[page:13]  

- Higher sales during spring and fall months  
- Lower sales during winter months  

These patterns suggest seasonal demand driven by travel volume and customer activity.[page:13]  

### 6.3 Department / Category Performance

Top‑performing departments include:[page:13]  

- Regular Gas  
- Cigarettes  
- Lottery Sales  
- Beer  
- Tobacco  

As expected, **fuel sales dominate total revenue**, but convenience products make a meaningful contribution and are a major lever for margin and basket size.[page:13]  

---

## 7. Forecasting Model

A machine learning model was built in Python to forecast future sales based on historical trends.[page:13]  

High‑level steps:[page:13]  

1. Aggregate daily/weekly sales from transaction‑level data.  
2. Engineer time‑based features (month, day of week, etc.).  
3. Split data into train/test sets.  
4. Train a regression‑based forecasting model using `scikit‑learn`.  
5. Evaluate model performance on hold‑out data.  

The model is used to:[page:13]  

- Forecast future revenue  
- Support inventory planning  
- Highlight potential demand changes (e.g., seasonal dips and peaks)[page:13]  

Implementation details are in the notebook:  
`notebooks/future_sales_prediction_model.ipynb`.[page:13]  

---

## 8. Key Insights

From the analysis and forecasting work:[page:13]  

- Sales grew significantly from 2020 to 2022, then stabilized in later years.  
- Gas sales are the primary revenue driver, but convenience items (cigarettes, beer, lottery) generate consistent, complementary income.  
- Winter months show noticeably reduced sales activity.  
- Several product categories contribute very low revenue and may warrant inventory reduction or replacement.[page:13]  

---

## 9. Business Recommendations

Based on the findings, the following actions are recommended to the store manager:[page:13]  

1. **Promote high‑margin store items**  
   - Use pump‑top ads, in‑store signage, and bundles (fuel + drink/snack) to increase basket size.  

2. **Boost winter sales**  
   - Introduce targeted promotions (e.g., hot drinks, comfort snacks) during slower months to offset seasonal dips.  

3. **Optimize inventory**  
   - Reduce stock for consistently low‑performing items.  
   - Reinvest shelf space into high‑demand or higher‑margin categories.  

4. **Operationalize forecasting**  
   - Use the sales forecasting model as a regular input into purchasing and staffing decisions.  
   - Continuously retrain the model with new data to keep forecasts up‑to‑date.[page:13]  

---

## 10. Project Structure

```bash
gas-station-sales-analysis
├── notebooks
│   └── future_sales_prediction_model.ipynb
├── visuals
│   └── sales_trends.png
├── case-study.pdf
└── README.md
```
[page:13]  

---

## 11. Skills Demonstrated

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Sales trend and seasonality analysis  
- Data visualization (Excel & Python)  
- Business insight generation and storytelling  
- Machine learning for sales forecasting  
- Translating analytics into actionable recommendations for stakeholders[page:13]  
