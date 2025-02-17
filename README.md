# E-Commerce Sales Analytics

## Overview

This project involves the development of an **interactive Power BI dashboard** to analyse e-commerce sales data, providing actionable insights on **product performance, customer behaviour, and profitability**. The dataset contains transactional sales records from an online retail store, covering purchases from customers across different regions.

## Objectives

The primary aim of this project is to extract meaningful insights from e-commerce sales data to support data-driven decision-making. The analysis focuses on:

**1. Sales Performance Analysis**

- Measuring overall revenue, profits, and returns over time
- Identifying sales trends and seasonal variations
  
**2.Product Performance Evaluation**

- Determining the top revenue-generating and best-selling products
  
**3.Customer Behaviour Insights**

- Understanding purchasing habits and frequency
- Analysing new vs. returning customer trends
- Measuring customer retention and estimating Customer Lifetime Value (CLV)

**4.Geographical Sales Distribution**

- Identifying key revenue-contributing regions
- Assessing market concentration and growth opportunities


## Insights

**1. Revenue & Profitability:**

- **Total revenue:** £9.73M (Dec 2010 - Dec 2011), with a peak in November 2011
- **Total profits:** £3M, following a similar trend to revenue

**2. Returns & Refunds:**

- **Total refunds**: £10M, indicating a high return rate, though it declines towards the year’s end.

**3. Customer Trends:**

- **Total customers**: 4,373, with a steady increase in returning customers. Indicates growing customer loyalty.

**4. Best-Selling Products:**

**Top revenue generator:** "Regency Cake Stand 3 Tier" (£163,348 in revenue).

Other high-performing products:

- "White Hanging Heart T-Light Holder"
- "Party Bunting"
- "Jumbo Bag Red Retrospot"
- "Rabbit Night Light"

**5. Geographical Performance:**

- The UK dominates revenue contribution, followed by other European countries.

**6. Sales Trends & Seasonality:**

- Thursday is the most profitable day of the week.
- Q4 has the highest revenue, indicating strong seasonal effects.


## Data cleaning

A **structured, professional data cleaning and transformation proces**s was executed in Power Query, ensuring high data integrity, consistency, and optimised performance. The process included:

**1. Handling Missing Values with a Business Perspective:**

- Null CustomerID values were retained as guest users to avoid data loss
- Ensured no blank Invoice IDs, guaranteeing completeness in transaction records

**2. Returns & Refund Handling:**

- Created a separate table to track first purchases
- Implemented a new vs. returning customer classification based on purchase date and first purchase date

**3. Deduplication & Ensuring Data Integrity:**

- Removed exact duplicate transactions based on StockCode, InvoiceDate, CustomerID, and InvoiceNo
- Did not apply fuzzy matching or partial merging, prioritising transaction clarity over approximation

**4. Data Modelling & Structuring for Scalability:**

- Developed a Products table with aggregated metrics (average price, total quantity, and total revenue per product)
- This table is dynamically updated, ensuring real-time tracking of product performance

**5. Standardisation & Formatting Improvements:**

- Applied text-to-numeric conversions where necessary to enhance calculation efficiency
- Standardised product descriptions (trimmed and uppercased) for consistency

**6. Power Query Transformations & DAX Calculations:**

- Used Power Query to reshape and clean data but did not leverage parameterised queries or custom functions


## Tools & technologies used

- 🔵 Power BI → Data visualization & dashboard design
- 📊 Power Query → Data cleaning & transformation
- 📈 DAX (Data Analysis Expressions) → Custom measures & calculations
- 📁 Excel → Initial data storage & exploration


## Upcoming steps
**1. Enhancing Dashboard Design:** Improve the aesthetics for better readability.

**2. Deeper Customer Behaviour Analysis:** Identify purchasing patterns and frequency.

**3. Measuring Customer Retention:** Develop metrics to track long-term customer value (CLV).

**4.Performance Optimisation:** Implement indexing, automated updates for aggregated tables, and refined deduplication methods.

**5.Fraud & Return Analysis:** Develop KPIs to track return rates and suspicious return behaviour.


## Dashboard Preview
![E-Commerce Sales Dashboard gif](https://github.com/user-attachments/assets/461a5f36-85d3-4976-b95b-ddeb84d2fd70)


## How to access the dashboard
1. Download the Power BI file (.pbix).

2. Open it in Power BI Desktop.

3. Interact with filters and visualisations to explore the insights.

