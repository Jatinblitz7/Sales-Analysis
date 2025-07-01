# 📊 USA Regional Sales Analysis (2014–2018)

A comprehensive Exploratory Data Analysis (EDA) of **Acme Co.’s** sales performance across the United States from 2014 to 2018. This notebook-driven project investigates trends, anomalies, and key drivers of revenue and profit to inform business strategy and dashboard development.

---

## 🧭 Objective

Leverage EDA to extract **actionable insights** from Acme Co.’s historical sales data to:

- Identify top-performing **products**, **sales channels**, and **regions**
- Detect **seasonal patterns** and **sales anomalies**
- Analyze **pricing**, **profit margins**, and **budget variances**
- Support **pricing**, **promotion**, and **market expansion** strategies
- Inform the structure and KPIs of a Power BI dashboard for leadership use

---

## 📁 Dataset Summary

- **Source:** Internal Acme Co. records (2014–2018)
- **Key Columns:** `Date`, `Region`, `Channel`, `Product`, `Customer Segment`, `Units Sold`, `Revenue`, `Cost`, `Profit`, `Budget`
- **Data Size:** ~20K transactions across 5 years

---

## 🔍 Project Highlights

### 🧹 Data Profiling & Cleaning
- Validated schema and ensured type consistency
- Handled missing values (especially in `Budget`) using forward-fill and median strategies
- Parsed `Date` column for time-series decomposition

### 📈 Univariate & Bivariate Analysis
- Explored distribution of key metrics: `Revenue`, `Profit Margin`, `Unit Price`
- Grouped performance by `Product`, `Channel`, `Region`, and `Customer Segment`
- Highlighted high-volume but low-margin segments

### 📆 Trend & Seasonality
- Charted **monthly** and **yearly** revenue trends
- Detected consistent **seasonal spikes** (e.g., Q4 peaks)
- Assessed month-over-month and YoY growth patterns

### 🚨 Outlier Detection
- Identified unusually high/low `Revenue` and `Unit Price` transactions
- Flagged potential **data entry errors** and **pricing anomalies**

### 📊 Correlation & Segmentation
- Measured inter-feature relationships using correlation heatmaps
- Segmented customers by **Revenue vs. Profitability** quadrants

---

## ❓ Problem Statement

> Analyze Acme Co.’s 2014–2018 USA sales data to identify key revenue and profit drivers across products, channels, and regions; uncover seasonal trends and outliers; and align performance against budgets. Use these insights to optimize pricing, promotions, and market expansion for sustainable growth and reduced concentration risk.

---

## 🛠️ Tools & Libraries Used

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- **Jupyter Notebook**: For exploratory analysis
- **Power BI (planned)**: For dashboard visualization based on insights

---

## 📌 Next Steps

- Develop an interactive **Power BI dashboard** showcasing key KPIs
- Incorporate **forecasting** and **budget tracking** visuals
- Automate data pipeline for monthly refresh and insight tracking

---

