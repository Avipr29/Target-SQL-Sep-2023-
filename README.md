# Target-SQL-Sep-2023-

# Target Brazil - SQL Case Study  

## 📌 Project Overview  
Target is a globally renowned retailer, and this business case focuses on its operations in Brazil. The dataset contains **100,000 orders** placed between **2016 and 2018**, covering various aspects such as order status, pricing, payment performance, customer demographics, product attributes, and reviews.  

As a **Data Analyst at Target**, the goal is to analyze the dataset, extract valuable insights, and provide **data-driven recommendations** for improving operations.  

## 📂 Dataset Information  
The data is spread across **8 CSV files**:  
- `customers.csv` - Customer details (location, unique IDs)  
- `sellers.csv` - Seller details  
- `order_items.csv` - Order details, pricing, freight, and seller ID  
- `geolocation.csv` - Customer location data  
- `payments.csv` - Payment type, installments, and values  
- `reviews.csv` - Customer reviews and ratings  
- `orders.csv` - Order timestamps and delivery estimates  
- `products.csv` - Product categories and descriptions  

## 🎯 Problem Statement  
The objective is to explore the dataset and answer key business questions:  
- **Customer & Order Analysis:**  
  - How many unique customers are there?  
  - What is the time range of orders?  
  - How are customers distributed across different states and cities?  
- **Sales & Seasonality Analysis:**  
  - Are the number of orders increasing over time?  
  - Is there a monthly/seasonal trend in order volume?  
  - At what time of the day do most customers place orders?  
- **Economic Impact & Revenue Trends:**  
  - How have order prices changed between 2017 and 2018?  
  - Which states contribute the most revenue?  
  - What is the impact of freight charges on overall costs?  
- **Logistics & Delivery Performance:**  
  - What is the average delivery time?  
  - How does actual delivery time compare with estimated delivery dates?  
  - Which states have the fastest/slowest delivery times?  
- **Payment Insights:**  
  - What are the most used payment methods?  
  - How many orders are placed with installment-based payments?  

## 🔍 Key Findings  
- **Customer Overview:**  
  - The dataset contains **99,441 customer records** from **27 states and 4,415 cities** in Brazil.  
  - Orders span a period of **25 months**.  
  - **625 records** have missing order statuses.  
  - **609 orders were canceled**, leaving **96,476 successfully delivered orders**.  

- **Delivery Performance:**  
  - The **average delivery time is 12 days**, which is a major inconvenience for consumers.  
  - There is a significant **gap between estimated and actual delivery times**, suggesting inefficiencies in the logistics network.  

- **Order & Revenue Trends:**  
  - Order volume showed **growth between 2017 and 2018**.  
  - Freight costs varied significantly across different states, affecting overall pricing.  

## ✅ Recommendations  
- **Improve Logistics & Delivery Efficiency:**  
  - The long delivery time (12 days on average) may be a major reason why Target struggled in Brazil.  
  - Optimizing the **delivery network** and working with more **efficient logistics partners** could improve customer satisfaction.  
- **Enhance Data Structuring:**  
  - The **order_items table** contains multiple items per order, but each has a separate ID.  
  - Assigning product IDs instead of order item IDs can make data tracking more efficient.  

---

## 🛠 Tech Stack  
- **SQL** - Data extraction & analysis  
- **MySQL** - Querying & data manipulation  
- **Excel** - Additional data validation & reporting  

## 📑 Files in This Repository  
- **`Target_Brazil_Analysis.ipynb`** - Jupyter Notebook with SQL queries and analysis  
- **`Target_Brazil_Report.pdf`** - Summary report with insights and visualizations  

---

### 🚀 Next Steps  
This project is part of my growing **Data Science & Machine Learning journey**. I will continue adding projects covering:  
- **Predictive Analytics** (Regression, Classification)  
- **Ensemble Methods & Feature Engineering**  
- **Unsupervised Learning & Clustering**  
- **Neural Networks & Deep Learning**  

Stay tuned for updates!  

