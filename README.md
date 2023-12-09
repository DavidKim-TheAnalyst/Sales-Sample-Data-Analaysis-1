# SQL Query Samples: Sales Sample Data Analysis 1

## Overview

Explore a comprehensive analysis of sales data conducted on the "sample_sales_data_1" database from January 10th, 2003, to September 9th, 2004. This collection of SQL queries unveils insights into customer behaviors, temporal trends, global market dynamics, product performance, and deal size classification.

## Key Actions

- **Data Cleaning**: Addressed null values and transformed the 'ORDERDATE' column to datetime.
- **Customer Insights**: Analyzed 92 unique customers placing 2,823 orders with average quantities and sales amounts.
- **Temporal Analysis**: Explored yearly and monthly order trends, advising on production strategies.
- **Global Market Overview**: Examined orders from 19 countries, identifying market share trends.
- **Product Performance**: Evaluated the top 10 products, emphasizing Classic cars' exceptional performance.
- **Deal Size Classification**: Classified orders into 'Small,' 'Medium,' and 'Large' based on sales volume.

## Data Source

The sales data is sourced from [Kaggle](https://www.kaggle.com/kyanyoga/sample-sales-data).

## Code Highlights

Explore SQL queries that cover:

- Cleaning and transforming data for analysis with code (`ALTER TABLE`, `UPDATE`, `STR_TO_DATE`).
- Customer insights and top customer analysis (`COUNT`, `AVG`, `SUM`).
- Temporal trends at yearly and monthly levels (`YEAR`, `MONTH`, `COUNT`, `SUM`).
- Global market overview and market share trends (`COUNT`, `SUM`, `ROUND`, `JOIN`).
- Product performance analysis for the top 10 products (`SELECT`, `AVG`, `ROUND`, `SUM`).
- Deal size classification based on sales volume (`MIN`, `MAX`, `AVG`).


## Conclusion

Provided actionable insights into customer behaviors, temporal trends, global market dynamics, product performance, and deal size classification. These insights aid strategic decision-making for business enhancement.
