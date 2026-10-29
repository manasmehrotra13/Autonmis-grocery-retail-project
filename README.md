# Grocery Retail: Data Warehouse and Strategic Analysis

Project from my data analyst internship at **Autonmis** (early 2025). All the data is generated (made up), so it is safe to share.

## The goal
Design a data warehouse for a grocery business, and use it to track sales, customers, inventory, forecasts and marketing.

## What I did
1. **Designed the data model:** 13 fact tables (for example sales, customer engagement, loyalty, inventory, web traffic, promotions, feedback, forecasts and churn) and 13 dimension tables (customers, products, stores, channels, campaigns, suppliers, time and more).
2. **Generated realistic data in Python** (pandas, Faker and Mimesis): about 425,000 rows across 2023–24, with seasonality, missing values, duplicates and late-arriving rows added on purpose.
3. **Loaded the data:** CSV files into PostgreSQL, then PostgreSQL to Snowflake with the Sling tool.
4. **Transformed it with SQL:** cleaned text with regular expressions, added reorder-status logic and forecast accuracy, and built 3 analysis tables (sales and marketing performance, customer insights, inventory and demand forecast).
5. **Analysed and reported:** about 20 analysis queries and a 21-chart dashboard, plus a written report.

## Tools
Python (pandas, Faker, Mimesis), PostgreSQL (Neon), Snowflake, Sling, SQL, the Autonmis platform.

## Files
- `latestretail.ipynb`: the Python notebook
- `Grocery retail data model.pdf` and `Retail Data Model.txt`: the data model
- `transformation changes.txt`: notes on the SQL transformations
- `Grocery Retail Sales Dashboard.pdf`: the dashboard
- `Grocery retail document.pdf`: the written report
- `Datasets.zip`: the generated data
- two images of the analysis

*Note: some product and category names are random placeholder text from the data generator.*
