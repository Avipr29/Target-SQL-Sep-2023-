# Target-SQL-Sep-2023-

Target Brazil: SQL Data Analysis

Overview

Target is a globally renowned retail brand operating in multiple regions, including Brazil. This project analyzes 100,000+ e-commerce orders placed between 2016 and 2018 to derive insights into customer behavior, order trends, payment patterns, freight performance, and overall operational efficiency.

Dataset

The dataset consists of eight CSV files:

customers.csv – Customer information

sellers.csv – Seller details

order_items.csv – Details of purchased items

geolocation.csv – Geographic data of customers

payments.csv – Payment transaction details

reviews.csv – Customer reviews and ratings

orders.csv – Order-related data

products.csv – Product attributes

Objectives

As a data analyst at Target, the goal is to analyze the dataset and provide actionable recommendations to improve business operations.

Key Analyses

1. Exploratory Data Analysis (EDA)

Examined data types, missing values, and general dataset structure.

Identified customer distribution across states and cities.

Determined the time range of orders in the dataset.

2. Order & Sales Trends

Analyzed year-over-year growth in order volume.

Identified seasonal trends in monthly orders.

Determined peak hours for customer orders (Dawn, Morning, Afternoon, Night).

3. Regional E-commerce Insights

Mapped monthly order distribution across states.

Examined customer distribution across different regions.

4. Economic Impact Analysis

Measured the percentage increase in order costs between 2017 and 2018.

Computed total and average order price per state.

Assessed freight costs per state to identify cost-effective logistics strategies.

5. Logistics & Delivery Performance

Calculated average delivery time and deviation from estimated delivery dates.

Identified states with the highest and lowest average delivery times.

Ranked states based on the accuracy of estimated vs. actual delivery times.

6. Payment Insights

Analyzed payment type distribution across different months.

Evaluated installment-based payment trends.

Key Findings

99441 unique customer records across 27 states and 4415 cities.

Data inconsistencies: ~625 records with missing order status.

High order cancellations: 609 orders were canceled, leaving 96476 successful deliveries.

Recommendations

Improve Delivery Network: The average delivery time is 12 days, which may negatively impact customer satisfaction. Target should optimize its logistics to reduce delays.

Data Structure Optimization: The order_items table stores multiple items per order with unique IDs, which could be better represented by their respective product IDs for clarity.

Address Missing Data Issues: The presence of incomplete records, such as missing order statuses, suggests data management improvements are necessary.

Tech Stack

SQL (MySQL)

Python (Pandas for data preprocessing)

Excel (for additional data validation)
