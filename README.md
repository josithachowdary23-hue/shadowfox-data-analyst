# 📊 ShadowFox Data Analyst Internship – Beginner Level

## Online Retail Sales Analysis using Microsoft Excel

![Data Analyst](https://img.shields.io/badge/Role-Data%20Analyst-blue)
![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-green)
![Level](https://img.shields.io/badge/Level-Beginner-orange)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20Online%20Retail-purple)

---

## 📌 Project Overview

This project was completed as part of the **ShadowFox Data Analyst Internship – Beginner Level**.

The objective of this project is to demonstrate the ability to work with real-world transactional data, organize and clean the dataset, perform spreadsheet analysis, identify trends, create visualizations, and convert analytical findings into meaningful business insights.

For this project, I used the **UCI Online Retail dataset**, which contains transactional data from a UK-based online retailer.

The analysis was performed using **Microsoft Excel**.

---

## 🎯 Project Objectives

The project was designed to satisfy the requirements of the ShadowFox Beginner-level Data Analyst task.

The main objectives are:

- Clean and organize a real-world dataset
- Perform basic spreadsheet analysis
- Calculate key summary metrics
- Analyze monthly sales trends
- Analyze product-level performance
- Analyze country-wise performance
- Create charts and visual summaries
- Build a simple business dashboard
- Identify important business observations
- Provide practical conclusions and recommendations
- Document the data-cleaning process

---

## 📂 Repository Contents

This repository contains the following files:

### 1. Raw Data

**`ShadowFox_Online_Retail_Raw_Data.xlsx`**

Contains the raw transaction data used as the starting point of the analysis.

The raw dataset contains fields such as:

- Invoice Number
- Stock Code
- Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

No analytical columns such as Revenue, Month, Transaction Type, or Return/Cancel flags are added to the raw-data file.

---

### 2. Sorted Data

**`ShadowFox_Online_Retail_Sorted_Data.xlsx`**

Contains the same transaction data organized chronologically.

The data is sorted by:

1. Invoice Date
2. Invoice Number
3. Stock Code

Sorting the data makes it easier to inspect transactions and understand the time-based structure of the dataset.

---

### 3. Complete Excel Analysis

**`ShadowFox_Beginner_Data_Analyst_Online_Retail_v2.xlsx`**

This is the main project workbook.

It contains the complete data-analysis workflow, including:

- Raw data
- Cleaned data
- KPI analysis
- Monthly trend analysis
- Product analysis
- Country analysis
- Quarterly analysis
- Cleaning log
- Business insights
- Dashboard

---

## 🔄 Analysis Workflow

The complete project follows this workflow:

**Raw Data → Data Sorting → Data Cleaning → KPI Analysis → Monthly Trend Analysis → Product Analysis → Country Analysis → Quarterly Analysis → Business Insights → Dashboard**

---

## 📑 Excel Workbook Structure

The main Excel workbook is divided into several sheets.

### 🗂 Raw_Data

Contains the original transaction data used for the analysis.

This sheet represents the starting point of the project before applying analytical transformations.

---

### 🧹 Cleaned_Data

Contains the organized dataset after data preparation.

Additional analytical fields were created to support the analysis:

- Revenue
- Month
- Transaction Type
- Is Cancelled
- Is Return

Revenue is calculated using:

**Revenue = Quantity × Unit Price**

---

### 📊 KPI_Summary

Contains important summary metrics used to understand overall business performance.

The key metrics include:

- Total Revenue
- Number of Invoices
- Number of Customers
- Number of Countries
- Average Revenue per Invoice
- Dataset Date Range

These metrics provide a high-level overview before performing detailed analysis.

---

### 📅 Monthly_Trend

Analyzes revenue performance over time.

The analysis includes:

- Monthly Revenue
- Month-over-Month Change
- Percentage Change
- Monthly performance observations

This analysis helps identify changes in sales performance and possible seasonal patterns.

---

### 🛍 Product_Analysis

Analyzes product-level performance.

The analysis helps identify:

- Top-performing products
- Products generating significant revenue
- Lower-performing products
- Products that may require additional attention

This can help businesses make better decisions regarding inventory and promotions.

---

### 🌍 Country_Analysis

Analyzes revenue across different countries.

The analysis helps identify:

- Major markets
- Strong-performing countries
- International markets
- Geographic revenue distribution

This provides an overview of where the business generates most of its revenue.

---

### 📊 Quarterly_Analysis

Groups revenue into quarterly periods.

Quarterly analysis helps identify broader sales patterns and makes it easier to compare business performance across different periods of the year.

---

### 🧽 Cleaning_Log

Documents the data-cleaning and preparation process.

The cleaning log explains:

- What was cleaned
- Why it was cleaned
- How it was handled
- Why each cleaning step is relevant to the analysis

This provides transparency about the transformation of the raw dataset.

---

### 💡 Business_Insights

Converts the numerical analysis into practical business observations.

This section includes:

- Observation
- Supporting evidence
- Business meaning
- Recommended action
- Priority

The goal is to move beyond simply reporting numbers and explain what the results mean for a business.

---

### 📊 Dashboard

Provides a simple business-oriented visual summary of the analysis.

The dashboard contains:

- KPI summary
- Monthly revenue chart
- Product performance chart
- Country performance chart
- Key business takeaways

The dashboard is designed to provide a quick overview of the most important findings.

---

## 🧹 Data Cleaning

The following data-preparation steps were performed or considered during the project.

### Date Standardization

Invoice dates were converted into a consistent date format so that monthly and quarterly analysis could be performed correctly.

### Revenue Calculation

Revenue was calculated using:

**Revenue = Quantity × Unit Price**

This creates a consistent measure for comparing transaction and product performance.

### Month Extraction

A separate month field was created from the invoice date.

This allows transactions to be grouped and compared by month.

### Returns

Transactions with negative quantities were identified as returns.

Returns were flagged separately so they could be distinguished from normal sales transactions.

### Cancellations

Invoices beginning with the letter `C` were identified as cancellation transactions.

These transactions were flagged separately to avoid confusing cancellations with normal sales.

### Customer Data

Customer IDs were examined for missing values.

Missing customer identifiers were not treated as product or revenue identifiers.

### Service Items

Postage and other service-related transaction lines were considered separately from merchandise when interpreting product performance.

This prevents service charges from being incorrectly treated as physical products.

---

## 📊 Key Business Metrics

The project focuses on the following key metrics:

| Metric | Purpose |
|---|---|
| Total Revenue | Measures overall sales value |
| Number of Invoices | Measures transaction volume |
| Number of Customers | Indicates customer reach |
| Number of Countries | Shows geographic reach |
| Average Revenue per Invoice | Measures average transaction value |
| Monthly Revenue | Identifies sales trends |
| Product Revenue | Identifies important products |
| Country Revenue | Identifies important markets |

---

## 📈 Trend Analysis

Monthly revenue was analyzed to identify changes in sales performance throughout the available period.

The analysis helps answer questions such as:

- Which month generated the highest revenue?
- Are there seasonal sales patterns?
- Are revenues increasing or decreasing?
- Which periods require further investigation?

The analysis indicates that **November 2011** was a particularly strong revenue period, suggesting a possible seasonal effect.

### Business Implication

The business could prepare inventory, staffing, and promotional campaigns in advance of high-demand seasonal periods.

---

## 🛍 Product Analysis

Product-level analysis was performed to identify products contributing significantly to revenue.

The analysis helps answer:

- Which products generate the most revenue?
- Which products appear to have weaker performance?
- Which products may deserve additional promotion?
- Which products should receive attention during inventory planning?

### Business Implication

High-performing products should receive appropriate inventory priority and promotional attention, while weaker products can be reviewed for pricing, demand, or promotional opportunities.

---

## 🌍 Country Analysis

Country-level revenue was analyzed to understand geographic performance.

The **United Kingdom** represents the dominant market in the dataset, while several international markets also contribute meaningful revenue.

Countries such as:

- Netherlands
- EIRE
- Germany
- France

represent important international markets for further analysis.

### Business Implication

The business can continue strengthening its primary market while evaluating opportunities for growth in strong international markets.

---

## 📊 Quarterly Analysis

Revenue was grouped into quarterly periods to provide a broader view of business performance.

Quarterly analysis helps:

- Compare performance across periods
- Identify seasonal patterns
- Understand broader revenue movements
- Support planning and forecasting

---

## 🔍 Business Questions Explored

The project attempts to answer several business questions.

### Sales Performance

- What is the overall revenue?
- How many invoices were generated?
- What is the average revenue per invoice?

### Time-Based Performance

- Which months generated the highest revenue?
- Are there seasonal sales patterns?
- How does revenue change from month to month?

### Product Performance

- Which products generate the most revenue?
- Which products contribute significantly to sales?
- Which products may require further investigation?

### Geographic Performance

- Which countries generate the most revenue?
- How important is the UK market?
- Which international markets show potential?

### Operational Performance

- How many transactions are returns?
- How many invoices are cancellations?
- How can returns and cancellations affect business reporting?

---

## 💡 Business Insights

Based on the analysis, several practical observations were identified.

### 1. Strong Seasonal Performance

Revenue varies considerably across months, with November showing particularly strong performance.

**Business Implication:**  
The business could prepare inventory, staffing, and promotional campaigns in advance of high-demand seasonal periods.

### 2. United Kingdom Is the Dominant Market

The UK contributes the largest share of revenue in the dataset.

**Business Implication:**  
The company should continue maintaining strong customer service and product availability in its primary market while evaluating opportunities in international markets.

### 3. Product Performance Is Concentrated

A relatively small number of products contribute significantly to revenue.

**Business Implication:**  
High-performing products should receive appropriate inventory priority and promotional attention.

### 4. Returns and Cancellations Require Monitoring

Negative quantities and cancelled invoices can affect revenue calculations.

**Business Implication:**  
Returns and cancellations should be monitored separately as operational KPIs to understand their impact on sales and customer experience.

### 5. Service Items Should Be Interpreted Separately

Items such as postage can generate revenue but do not represent merchandise sales.

**Business Implication:**  
Product-performance KPIs should distinguish merchandise from service-related transaction lines.

---

## 📌 Recommendations

Based on the findings, the following actions could be considered:

1. Prepare inventory for high-demand seasonal periods.
2. Monitor the performance of the highest-revenue products.
3. Investigate products with consistently weak revenue.
4. Track returns and cancellations as separate operational KPIs.
5. Continue strengthening the UK market.
6. Explore growth opportunities in strong international markets.
7. Separate merchandise revenue from service-related revenue when evaluating product performance.
8. Use monthly and quarterly trends to support future sales planning.

---

## 🛠 Tools & Skills Demonstrated

### Tools Used

- Microsoft Excel
- Excel Tables
- Excel Formulas
- Sorting and Filtering
- Charts
- Dashboarding
- Spreadsheet Analysis

### Data Analyst Skills

- Data Cleaning
- Data Organization
- Exploratory Data Analysis
- KPI Development
- Trend Analysis
- Product Analysis
- Geographic Analysis
- Data Visualization
- Business Interpretation
- Recommendation Generation

---

## 📚 Dataset

### UCI Online Retail Dataset

The project uses the **Online Retail** dataset from the **UCI Machine Learning Repository**.

The original dataset contains transactional records from a UK-based online retailer covering the period:

**1 December 2010 – 9 December 2011**

The dataset includes information about:

- Invoices
- Products
- Quantities
- Prices
- Customers
- Countries

### Dataset Source

**UCI Machine Learning Repository**

**Dataset:** Online Retail

**DOI:** 10.24432/C5BW33

**License:** CC BY 4.0

---

## 📋 Dataset Fields

The original dataset contains the following fields:

| Field | Description |
|---|---|
| InvoiceNo | Invoice number assigned to the transaction |
| StockCode | Product/item identification code |
| Description | Product description |
| Quantity | Number of units purchased |
| InvoiceDate | Date and time of transaction |
| UnitPrice | Price per unit |
| CustomerID | Customer identification number |
| Country | Customer's country |

---

## 🔄 End-to-End Project Process

The project follows a standard beginner-level data-analysis workflow:

**1. Obtain Real-World Dataset**

↓

**2. Store Raw Data**

↓

**3. Sort and Organize Data**

↓

**4. Clean and Prepare Data**

↓

**5. Create Derived Fields**

↓

**6. Calculate KPIs**

↓

**7. Analyze Monthly Trends**

↓

**8. Analyze Product Performance**

↓

**9. Analyze Country Performance**

↓

**10. Perform Quarterly Analysis**

↓

**11. Create Charts**

↓

**12. Build Dashboard**

↓

**13. Identify Business Insights**

↓

**14. Provide Recommendations**

---

## ✅ ShadowFox Requirement Checklist

| ShadowFox Beginner Requirement | Status |
|---|---|
| Cleaned and organized dataset | ✅ Completed |
| Basic spreadsheet analysis | ✅ Completed |
| Key summary metrics | ✅ Completed |
| Monthly trend analysis | ✅ Completed |
| Product-level analysis | ✅ Completed |
| Category/business-level analysis | ✅ Completed |
| Charts and visual summaries | ✅ Completed |
| Simple dashboard/report layout | ✅ Completed |
| Business-oriented observations | ✅ Completed |
| Business conclusions | ✅ Completed |
| Data-cleaning documentation | ✅ Completed |
| Practical recommendations | ✅ Completed |

---

## 📁 Repository Structure

```text
shadowfox-data-analyst/
│
├── README.md
│
├── ShadowFox_Online_Retail_Raw_Data.xlsx
│
├── ShadowFox_Online_Retail_Sorted_Data.xlsx
│
└── ShadowFox_Beginner_Data_Analyst_Online_Retail_v2.xlsx
