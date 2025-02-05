# E-Commerce Sales Analytics

## Overview

The objective of this project is to develop an interactive Power BI dashboard to analyse e-commerce sales data, providing actionable insights on product performance, customer behaviour, and profitability. The dataset contains transactional sales records from an online retail store, covering purchases from customers across different regions.

## Objectives

The project addresses the following questions:

**1. Identifying top-selling products by analysing both sales volume and revenue generation**

**2. Understanding UK consumer behaviour, including purchasing patterns and frequency**

**3. Determining the most profitable products, distinguishing between high-revenue and high-margin itemS**

**4. Analysing sales trends and seasonality, identifying peak periods and purchase behaviour over times**

**5. Measuring customer retention, tracking how many customers return after their first purchase and their lifetime value (CLV)**


## Insights

COMING SOON


## Data cleaning

Before visualisation, the dataset was cleaned and transformed in Power Query:

- Removed null & missing values (especially CustomerID)
- Filtered out negative quantities (potential returns)
- Created a 'Total Revenue' column (Revenue = Quantity * UnitPrice).
- Ensured unique product identifiers (StockCode)
- Checked for duplicate transactions and grouped data properly


## Tools & technologies used

- 🔵 Power BI → Data visualization & dashboard design
- 📊 Power Query → Data cleaning & transformation
- 📈 DAX (Data Analysis Expressions) → Custom measures & calculations
- 📁 Excel → Initial data storage & exploration
