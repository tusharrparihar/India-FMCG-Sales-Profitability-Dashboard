# 📊 India FMCG Sales & Profitability Analytics Dashboard

## Overview

This project presents an end-to-end Power BI analytics solution built on FY 2023–24 FMCG sales data across India.

The dashboard helps business leaders, sales managers, and finance teams understand how revenue, profitability, customer segments, products, and discounting strategies influence overall business performance.

By transforming raw transactional data into interactive visual insights, the solution enables faster decision-making and highlights areas where profitability can be improved.

---

## 📊 Dashboard Preview

### Executive Overview

![Main Dashboard](https://github.com/user-attachments/assets/debeebbe-3836-4728-b79c-a23b432a3883)

---

## 📅 Quarterly Dashboards

### Q1 Analysis

![Q1 Dashboard](https://github.com/user-attachments/assets/22dbdb9f-39eb-4a06-87fe-0f4210d2cfb1)

### Q2 Analysis

![Q2 Dashboard](https://github.com/user-attachments/assets/b00fdc40-65dc-4678-bd99-2e3fd658ea82)

### Q3 Analysis

![Q3 Dashboard](https://github.com/user-attachments/assets/6066771f-a559-4200-9874-8f9db2111a6c)

### Q4 Analysis

![Q4 Dashboard](https://github.com/user-attachments/assets/3a556c50-128d-4a69-8c34-326bb1b79d69)


# Business Problem

FMCG organizations often face challenges in understanding profitability beyond top-line sales.

Key issues addressed in this project:

* No centralized view of sales and profit performance across states.
* Limited visibility into customer segment profitability.
* Discounting decisions impacting margins without proper monitoring.
* Manual quarterly reporting processes causing delays.
* Difficulty identifying high-performing products and regions.

---

# Project Objectives

✔ Analyze revenue and profitability across India

✔ Track profit contribution by state and customer segment

✔ Measure discount impact on margins

✔ Enable quarterly performance comparison (Q1–Q4)

✔ Identify profit-driving and loss-making business areas

✔ Deliver an executive-ready dashboard for business users

---

# Dataset Summary

| Metric          | Value             |
| --------------- | ----------------- |
| Coverage Period | FY 2023–24        |
| Total Revenue   | ₹94M              |
| Total Profit    | ₹16M              |
| Profit Margin   | 17%               |
| Units Sold      | 127K+             |
| Transactions    | 77                |
| Geography       | 30+ Indian States |

### Dimensions

* State
* Customer Segment
* Product Category
* Quarter
* Year

### Measures

* Net Sales
* Profit
* Profit Margin %
* Units Sold
* Discount %

---

# Tech Stack

| Tool          | Purpose                        |
| ------------- | ------------------------------ |
| Power BI      | Dashboard Development          |
| Power Query   | Data Cleaning & Transformation |
| DAX           | KPI & Business Logic           |
| Excel         | Source Dataset                 |
| Data Modeling | Star Schema Design             |

---

# Dashboard Features

## KPI Summary Cards

Provides a high-level business snapshot:

* Revenue
* Profit
* Margin %
* Units Sold
* Transaction Count

---

## Geographic Profit Analysis

### State Profit Contribution Treemap

Visualizes profit concentration across Indian states and highlights top-performing markets.

Business Question:

> Which states contribute the most profit?

---

## Customer Segment Analysis

### Profit Margin by Segment

Compares profitability across:

* Channel Partners
* Midmarket
* Government
* Small Business
* Enterprise

Helps identify profitable and underperforming customer groups.

---

## Product Performance Analysis

### Profit Margin by Product Category

Analyzes profitability across:

* Textiles
* Basmati Rice
* Pharmaceuticals
* Spices
* Steel Products

Highlights seasonal and category-level performance shifts.

---

## Discount Optimization Analysis

### Discount vs Profitability Scatter Plot

Evaluates the relationship between:

* Discount Rate
* Profit Margin

Helps identify discount thresholds that negatively impact profitability.

---

## State Ranking Analysis

Detailed performance table displaying:

* Sales
* Profit
* Margin %
* State Ranking

Supports drill-down and comparative analysis.

---

# Key Business Insights

## 1. Madhya Pradesh Leads Overall Profitability

* Largest contributor to total profit.
* Consistently ranked among top-performing states.

## 2. Channel Partners Deliver Exceptional Margins

* Highest margin segment at approximately 75%.
* More than double most other customer segments.

## 3. Enterprise Segment Is Loss-Making

* Negative profit margins observed across multiple quarters.
* Requires immediate commercial review.

## 4. Q1 Was the Strongest Quarter

| Quarter | Margin |
| ------- | ------ |
| Q1      | 22%    |
| Q2      | 19%    |
| Q3      | 17%    |
| Q4      | 13%    |

Profitability steadily declined throughout the year.

## 5. Higher Discounts Reduce Margins

Transactions with discounts above 5% consistently show margin compression.

## 6. Revenue Growth Does Not Always Mean Profit Growth

Q4 revenue increased significantly, but margins fell, indicating aggressive pricing or unfavorable product mix.

---

# Recommendations

### Improve Enterprise Segment Economics

* Review pricing strategy.
* Renegotiate contracts.
* Reassess customer acquisition costs.

### Establish Discount Controls

* Introduce a 5% discount threshold.
* Monitor profitability before approving exceptions.

### Expand High-Margin Channels

* Increase investment in Channel Partner relationships.
* Replicate successful sales models across other segments.

### Focus on High-Profit States

Prioritize growth initiatives in:

* Madhya Pradesh
* Goa
* Mizoram
* Daman & Diu

### Introduce Product-Level Margin Targets

Create profitability benchmarks for every major product category.

---

# Skills Demonstrated

### Business Intelligence

* KPI Design
* Executive Reporting
* Performance Analytics

### Power BI

* Interactive Dashboards
* Drill-Through Analysis
* Advanced Visualizations

### Data Modeling

* Star Schema Design
* Fact & Dimension Modeling

### DAX

* Profit Margin Calculations
* Ranking Measures
* Dynamic KPIs

### Data Preparation

* Power Query Transformations
* Data Cleaning
* Validation & Quality Checks

---

# Project Structure

```text
📂 India-FMCG-Sales-Profitability-Dashboard
│
├── Dashboard
|   └── India FMCG Sales & Profitability Analytics Dashboard.pbix
├── Data
|   └── India_Sales_FY2024.xlsx
├── Visuals
│   ├── Main_Dashboard.PNG
│   ├── QTR_1_Dashboard.PNG
│   ├── QTR_2_Dashboard.PNG
│   ├── QTR_3_Dashboard.PNG
│   └── QTR_4_Dashboard.PNG
├── Report
|   └── India FMCG Sales & Profitability Analytics Dashboard.pdf
├── Presentation
|   └── 
├── README.md

```

---

# Future Enhancements

* Sales Forecasting for FY25
* Customer-Level Profitability Analysis
* Discount Optimization Simulator
* What-If Scenario Modeling
* Automated Data Refresh using SQL

---

# Conclusion

This project demonstrates how business intelligence can transform transactional FMCG sales data into actionable insights. The dashboard identifies profitability drivers, highlights margin risks, and provides decision-makers with a clear view of performance across products, customer segments, and regions.

The analysis revealed several high-impact findings, including a loss-making enterprise segment, margin erosion caused by excessive discounting, and strong geographic concentration of profits—insights that can directly support strategic business decisions.

