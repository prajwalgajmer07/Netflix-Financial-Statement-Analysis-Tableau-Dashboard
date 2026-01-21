# 📊 Netflix Financial Statement Analysis — Tableau Dashboard

## 📌 Project Overview

This project is an **end-to-end financial performance analysis dashboard** built using **Tableau Desktop (Public Edition)**.
The dashboard represents a **Profit & Loss (P&L) statement structure** and visualizes key financial metrics such as:

* Gross Profit (GP)
* EBITDA
* Operating Profit (OP)
* PBIT
* Net Profit (NP)
* Sales
* Profit Margins (GPM & NPM)
* Marketing Expenses

The project is designed to analyze **company profitability, cost behavior, and margin performance over time** and across different regions and countries.

> ⚠️ *Note:* The dataset is taken from Kaggle and structured in the format of Netflix-style financial statements for learning and analytical purposes. This is not official Netflix financial data.

---

## 🎯 Business Objective

To build a **financial analytics dashboard** that helps in:

* Monitoring profitability at multiple levels (GP, EBITDA, OP, PBIT, NP)
* Comparing **sales growth vs operating and marketing expenses**
* Tracking **profit margins over time**
* Analyzing financial performance across:

  * Regions
  * Countries
  * Quarters
  * Months

This type of analysis is commonly used in **FP&A (Financial Planning & Analysis)** and business finance teams.

---

## 🧩 Data Model

The project uses a **multi-table financial data model**, which includes:

* **General Ledger (GL)** — transaction-level financial amounts
* **Chart of Accounts** — accounting hierarchy (Class, Subclass, Account)
* **Calendar Table** — date, month, quarter, and year breakdown

These tables are connected using appropriate keys to enable:

* Accurate financial aggregation
* Time-based analysis
* Proper Profit & Loss statement structure

This data model supports both **detailed financial reporting** and **high-level KPI analysis**.

---

## 📊 Key KPIs Displayed (Year-wise)

The dashboard highlights yearly KPI cards for:

* ✅ Gross Profit
* ✅ EBITDA
* ✅ Operating Profit
* ✅ PBIT (Profit Before Interest & Tax)
* ✅ Net Profit

KPIs are displayed for:

* **2018**
* **2019**
* **2020**

This allows quick comparison of financial growth and profitability trends across years.

---

## 📈 Worksheets & Analysis

### 🧾 1. Profit & Loss Statement (Tabular View)

A complete accounting-style P&L structure including:

* **Trading Account**

  * Sales
  * Sales Returns
  * Cost of Sales
  * Gross Profit

* **Operating Account**

  * Administration Expenses
  * Marketing Expenses
  * Sales & Distribution
  * Depreciation & Amortization

* **Non-Operating Income**

  * Dividend Income
  * Interest Income
  * Exchange Gains

* **Interest & Tax**

  * Interest Expense
  * Taxation

* Final **Net Profit**

This mirrors real-world income statement reporting formats.

---

### 📊 2. Sales | Gross Profit | Net Profit (Time Series)

A stacked bar chart showing:

* Sales (Top-line)
* Gross Profit
* Net Profit (Bottom-line)

Used to analyze:

* Revenue growth trend
* Profit generation from sales
* Fluctuations in net profitability despite increasing sales

---

### 📈 3. Gross Profit | EBITDA | Operating Profit

A stacked area chart comparing:

* Gross Profit
* EBITDA
* Operating Profit

Used to understand:

* Impact of operating and administrative expenses
* Difference between core profitability and operating performance

---

### 📉 4. Sales vs Marketing Expense

An area chart showing:

* Sales above zero
* Marketing expenses below zero

Used to analyze:

* Relationship between marketing spend and revenue growth
* Marketing efficiency over time

---

### 📊 5. Sales with GPM & NPM

A dual-axis combination chart:

* Bars → Sales
* Lines → Gross Profit Margin (GPM) & Net Profit Margin (NPM)

Used to analyze:

* Profitability quality of sales
* Periods where margins drop despite strong revenue

This helps in evaluating **cost control and pricing effectiveness**.

---

## 📊 Final Dashboard Overview

The final dashboard integrates:

* ✅ KPI summary cards (GP, EBITDA, OP, PBIT, Net Profit)
* ✅ Full P&L statement table
* ✅ Sales vs expense comparison
* ✅ Profitability trend analysis
* ✅ Margin analysis with sales

### 🎛 Interactive Filters Included:

* 🌍 Region
* 🏳️ Country
* 📅 Quarter
* 📆 Month

This allows users to:

* Compare financial performance by geography
* Analyze seasonal behavior
* Drill down into specific markets and time periods

The dashboard provides a **complete financial snapshot with drill-down capability**, similar to real business reporting dashboards.

---

## 🧠 Skills Demonstrated

### 📊 Tableau Skills

* Measure Names & Measure Values
* Dual-axis charts
* KPI cards
* Area charts & stacked bar charts
* Time hierarchy (Year → Quarter → Month)
* Interactive dashboard filters
* Financial statement layout design

### 📈 Financial & Business Analysis

* Profit & Loss statement structure
* Multi-level profitability analysis
* Expense vs revenue comparison
* Margin analysis (GPM, NPM)
* Financial KPI tracking

### 📁 Data Handling

* Kaggle financial dataset
* Multi-table financial data model
* Accounting hierarchy usage
* Time-based aggregation

---

## 📁 Repository Structure

```
📁 Dataset/
   └─ Financial dataset files (Kaggle)

📁 Screenshots/
   └─ Worksheet and dashboard images

📁 Tableau File/
   └─ Tableau workbook (.twbx)

📝 README.md
```
