# Brazilian-E-commerce-dataset-by-Olist
This project analyzes the Brazilian E-Commerce Public Dataset provided by Olist. The dataset contains information on approximately 100,000 orders placed between 2016 and 2018 across multiple online marketplaces in Brazil. It includes customer information, product details, seller data, payment records, reviews, and delivery performance.

The goal of this project is to extract business insights, understand customer behavior, analyze sales performance, and identify factors affecting customer satisfaction.

Dataset Source:
[Olist Brazilian E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Main Tables
Customers Dataset
Orders Dataset
Order Items Dataset
Order Payments Dataset
Order Reviews Dataset
Products Dataset
Sellers Dataset
Geolocation Dataset

My analysis is purely based on only 3 datasets orders, order items and products.

Project Objectives
Analyze sales trends over time
Identify top-selling product categories
Study customer purchasing behavior
Measure delivery efficiency
Generate actionable business insights

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
SQL (optional)

Analysis Performed
Sales Analysis
Monthly revenue trends
Order volume growth
Seasonal purchasing patterns
Customer Analysis
Product Analysis
Best-selling categories
High-revenue products

Data Importing(pandas.read_csv() in Python, importing the CSV dataset)

Merged the order and items dataset with order_id and then merge with products dataset with product_id. Selected only the relevant columns required for the analysis and graph generation.Final dataset is checked with null values and replaced missing values in product_category_name with “unknown”. Removed rows where product_weight_g was missing.

Removing Duplicates(using df.drop_duplicates(),Purpose: Ensure no empty or incomplete data affects analysis)

Converted the order_purchase_timestamp into a datetime format.

Extracted year, month, month_name and day from the order_purchase_timestamp to support time-based analysis.

Verified the cleaned and transformed dataset before creating visualizations.



Delayed deliveries
Freight cost trends
Review Analysis
