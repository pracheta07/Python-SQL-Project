# Project Title
E-Commerce Data Analysis with Python and MySQL
# Brief Summary
Transform raw e-commerce CSV data into a MySQL database and extract actionable business insights using Python.
# Overview
This project imports multiple CSV files related to an e-commerce business into MySQL, cleans and structures the data using Python, and performs analysis to understand sales trends, customer distribution, and revenue contribution by product category. Visualizations are generated to provide clear insights.
# Problem Statement
E-commerce businesses generate large amounts of raw data. Extracting meaningful insights from this data manually is time-consuming and error-prone. This project automates data cleaning, storage, and analysis to enable faster, accurate business decision-making.
# Dataset
Customers – customer_id, name, city, state, etc.
Orders – order_id, customer_id, purchase_timestamp, etc.
Products – product_id, category, price, etc.
Payments – payment_id, order_id, payment_value, payment_installments, etc.
Sellers – seller_id, name, location, etc.
Geolocation – seller_zip_code, city, state, etc.
Order Items – order_item_id, order_id, product_id, etc.
All data is stored in CSV format in the E-Commerce folder.
# Tools & Technologies
Python – Data cleaning and automation
Pandas – CSV handling and data manipulation
MySQL – Relational database for structured storage
Matplotlib & Seaborn – Data visualization
OS Library – File path management
# Methods

Data Import & Cleaning : Read CSV files using pandas.
                        : Clean column names to remove spaces, hyphens, or dots.
                        : Replace missing values (NaN) with None for SQL compatibility.

Database Creation: Create MySQL tables with appropriate data types.
                  : Insert cleaned data into respective tables.

Data Analysis & Visualization: Write SQL queries in Python to extract business insights.
                              : Generate bar charts and statistical plots to visualize trends.
# Key Insights

Total sales per product category and their percentage contribution.
Orders trends per month and year.
Customer distribution across cities and states.
Percentage of orders paid in installments.
Average number of products per order per city.   

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


