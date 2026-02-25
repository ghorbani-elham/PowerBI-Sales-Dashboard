# Project Architecture

## Data Source
Sample sales dataset used for BI modeling.

## ETL Process (SSIS)
- Data extraction
- Data transformation
- Loading into data warehouse

## Data Warehouse Design
- Star schema
- Fact table: Sales
- Dimension tables: Date, Product, Customer

## Cube Design (SSAS)
- Measures: Sales, Profit, Order Quantity
- KPIs: Profit Margin, Revenue per Product
- MDX calculations implemented
