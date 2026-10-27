# Shopify Analytics Dashboard – Power BI

## 📊 Project Overview

**Shopify Analytics Dashboard** is an interactive **Power BI dashboard** designed to analyze Shopify stock data over time. It provides key performance indicators, historical comparisons, yearly trends, and date-based analysis.

The dashboard helps users quickly understand stock closing prices and compare current values with previous-year and year-to-date values.

## 🎯 Objectives

* Analyze Shopify stock price data.
* Track closing prices over different dates.
* Compare current closing prices with the previous year.
* Calculate average closing prices.
* Analyze Year-to-Date (YTD) performance.
* Provide an interactive and easy-to-understand dashboard.

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query** – Data transformation and preparation
* **DAX** – Creating measures and calculations
* **Shopify Stock Dataset**
* **Data Visualization**

## 📌 Dashboard Features

### 1. KPI Cards

The dashboard contains important KPI cards:

* **Latest Close** – Displays the latest available closing price.
* **Close LY** – Displays the closing value for the previous year.
* **Avg Close** – Displays the average closing price.
* **Close YTD** – Displays the Year-to-Date closing value.

### 2. Stock Closing Price Chart

The **Sum of Close by Date** chart displays the closing price based on the selected date.

### 3. Stock Data Table

The table provides date-wise information such as:

* Date
* Close LY
* Latest Close
* Average Close

### 4. Date Filter

A date hierarchy is provided to filter the dashboard using:

* Year
* Quarter
* Month
* Date

This allows users to analyze the data for a specific period.

### 5. Average Close Chart

A column chart is used to visualize the **Average Closing Price**.

### 6. Comparison Chart

A pie/donut chart compares different calculated measures such as:

* Latest Close
* Close LY
* Average Close
* Close Previous Year
* Close YTD

## 📈 DAX Measures

The dashboard uses calculated measures such as:

```DAX
Avg Close
```

```DAX
Close LY
```

```DAX
Close YTD
```

```DAX
Latest Close
```

These measures help perform calculations and display dynamic results based on the selected date filters.

## 📂 Data Fields

The main Shopify stock table contains fields such as:

* `date`
* `open`
* `high`
* `low`
* `close`
* `adj_close`
* `volume`

A separate **Date** table is used for time-based analysis.

## 🔄 Dashboard Workflow

```text
Shopify Stock Data
        ↓
Data Cleaning & Transformation
        ↓
Create Date Table
        ↓
Create DAX Measures
        ↓
Build Visualizations
        ↓
Add Filters & Interactions
        ↓
Shopify Analytics Dashboard
```

## 💡 Key Insights

The dashboard can be used to:

* Monitor Shopify's closing price.
* Identify changes in stock prices over time.
* Compare current performance with previous-year performance.
* Understand average stock performance.
* Analyze YTD performance.
* Filter and explore stock data by different dates.

## 🚀 How to Use

1. Open the Power BI `.pbix` file.
2. Refresh the dataset if required.
3. Use the **Date filter** to select a specific period.
4. View the KPI cards for a quick summary.
5. Explore the charts for visual analysis.
6. Use the table to view detailed date-wise values.

## 📷 Dashboard Preview

The dashboard contains a clean Power BI interface with KPI cards, charts, a detailed data table, and interactive date filters.
