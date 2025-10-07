# Project Title
E-Commerce Data Analysis with Python and MySQL
# Brief Summary
Transform raw e-commerce CSV data into a MySQL database and extract actionable business insights using Python.
# Overview
This project imports multiple CSV files related to an e-commerce business into MySQL, cleans and structures the data using Python, and performs analysis to understand sales trends, customer distribution, and revenue contribution by product category. Visualizations are generated to provide clear insights.
# Problem Statement
E-commerce businesses generate large amounts of raw data. Extracting meaningful insights from this data manually is time-consuming and error-prone. This project automates data cleaning, storage, and analysis to enable faster, accurate business decision-making.
# Dataset
1. Customers – customer_id, name, city, state, etc.
2. Orders – order_id, customer_id, purchase_timestamp, etc.
3. Products – product_id, category, price, etc.
4. Payments – payment_id, order_id, payment_value, payment_installments, etc.
5. Sellers – seller_id, name, location, etc.
6. Geolocation – seller_zip_code, city, state, etc.
7. Order Items – order_item_id, order_id, product_id, etc.

All data is stored in CSV format in the E-Commerce folder.
# Tools & Technologies
1. Python – Data cleaning and automation
2. Pandas – CSV handling and data manipulation
3. MySQL – Relational database for structured storage
4. Matplotlib & Seaborn – Data visualization
5. OS Library – File path management
# Methods

1. Data Import & Cleaning : Read CSV files using pandas.
                        : Clean column names to remove spaces, hyphens, or dots.
                        : Replace missing values (NaN) with None for SQL compatibility.

2. Database Creation: Create MySQL tables with appropriate data types.
                  : Insert cleaned data into respective tables.

3. Data Analysis & Visualization: Write SQL queries in Python to extract business insights.
                              : Generate bar charts and statistical plots to visualize trends.
# Key Insights

1. List all unique cities where customers are located.
2. Count the number of orders placed in 2017.
3. Find the total sales per category.
4. Calculate the percentage of orders that were paid in installments.
5. Count the number of customers from each state. 
6. Calculate the number of orders per month in 2018.
7. Find the average number of products per order, grouped by customer city.
8. Calculate the percentage of total revenue contributed by each product category.
9. Identify the correlation between product price and the number of times a product has been purchased.  

# How to Run This Project

1. Clone this repository: git clone <(https://github.com/pracheta07/Python-SQL-Project)>
2. Install Python 3.x and required libraries:
       pip install pandas mysql-connector-python matplotlib seaborn
3. Create a MySQL database named ecommerce.
4.Update MySQL credentials in import_csv_to_mysql.py and data_analysis.py.
5. Run the data import script:
         python import_csv_to_mysql.py
6. Run the analysis and visualization script:
         python data_analysis.py
# Result & Conclusion
The project successfully transformed raw CSV data into a structured MySQL database and provided actionable business insights. The analysis revealed sales trends, customer distribution patterns, and revenue contribution by product category, enabling better decision-making for the e-commerce business. Visualizations made it easier to interpret and communicate the results.
# Author
Name: Pracheta Sharma
Linkedin Profile: https://www.linkedin.com/in/pracheta-sharma-a6933725b/

