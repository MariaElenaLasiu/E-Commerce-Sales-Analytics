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

**1. Revenue and profitability:**

  The total annual revenue reached **$9.73M**, with a **clear Q4 peak** driven by seasonal demand.   Profitability followed a similar trend, with **$3M in total profits**, highest in **November and December**. Weekly trends showed **Thursdays as the best-performing day**, while **Sundays had the lowest revenue**.

These trends suggest the need to:
- **Increase inventory and marketing efforts** ahead of Q4 to capitalise on peak demand,
- **Leverage Thursday**s for major promotions and explore **Sunday-exclusive incentives** to boost weaker performance.

**2. Customer trends:**

  A total of **25K orders** were placed, with **4,373 customers** driving sales. Returning customers became a larger share of revenue over time, showing **strong loyalty trends**.

It is advisable to: 
- Introduce **loyalty programmes** to incentivise repeat purchases,
- **Attract new customers** with first-time discounts or referral offers.

**3. Managing returns and refunds:**

Refunds remain a **challenge**, totaling **$10M** and **spiking in Q4**, likely linked to holiday purchases.

It remains key to:
- **Identify frequently returned products** and investigate quality concerns,
- Adjust **return policies** (e.g., restocking fees, clearer descriptions) to reduce revenue loss.

**4. Top revenue generator:** 

The top-selling products included:

1. **Regency cake stand 3 tier** – $163,347
2. **White hanging heart t-light holder** – $99,298
3. **Party bunting** – $97,972
4. **Jumbo bag red retrospot** – $92,015
5. **Rabbit night light** – $66,461

These products account for a significant share of total revenue, making inventory management and pricing optimisation key to sustaining profitability. To maximise their impact:

- **Ensure stock availability for top-performing products**, especially leading up to Q4,
- **Optimise pricing strategies** to increase margins on high-demand items.

**5. Geographical performance:**

Regionally, the **UK dominates sales** (85% of total revenue - $8.24M), followed by **Netherlands** ($283K), **Ireland** ($259K), **Germany** ($200K), and **France** ($182K).

While the UK remains the core market, there is **potential to** optimise domestic growth while strategically **expanding into high-performing EU markets**.




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

