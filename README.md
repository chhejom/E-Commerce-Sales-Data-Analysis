# E-Commerce-Sales-Data-Analysis
This project showcases my skills in SQL and Google Cloud Console through an in-depth analysis of e-commerce sales data sourced from Kaggle. The dataset covers a one-year period from January 1, 2019, to January 1, 2020. The analysis aims to uncover customer purchasing behaviors, identify top-performing products and regions, and evaluate the effectiveness of promotional strategies. This repository includes SQL scripts, the cleaned dataset, and a detailed report of the findings.

# Tools and Technologies
* Google Cloud Console: Used for dataset creation, table setup, and data loading.
* SQL: Employed for querying and data analysis, enabling the extraction of meaningful insights from the dataset.

# Dataset
The dataset used in this project includes the following columns:

* order_id (INTEGER): Unique identifier for each order.
* product (STRING): Name of the product sold.
* quantity_ordered (INTEGER): Quantity of the product ordered.
* price_each (FLOAT): Price of each unit of the product.
* order_date (TIMESTAMP): Date and time when the order was placed.
* purchase_address (STRING): Address where the order was delivered.
* month (INTEGER): Month of the order date.
* sales (FLOAT): Total sales amount for the order.
* city (STRING): City where the order was delivered.
* hour (STRING): Hour of the day when the order was placed.

# Analysis Queries
# Query 1: Total Sales
To determine the overall sales performance:

Result: The total sales of this dataset are $34 Million.

# Query 2: Total Sales by City
To identify the top-performing cities:

Result: The top 3 performing cities are San Francisco, Los Angeles, and New York City, indicating higher purchasing power and frequent purchases in these urban areas.

# Query 3: Total Sales by Product
To understand which products are the most popular:

Result: Monitors are the most popular product, followed by batteries, reflecting consumer preferences and product trends.

# Query 4: Customer with Most Purchases and Sales Amount
To identify the most frequent buyers:

Result: The address 193 Forest St made the most purchases during the reporting period, indicating a highly responsive customer to deals and promotions.

# Query 5: Least Interactive Customers
To find customers with minimal interaction:

Result: Identified customers who interacted the least with the platform, providing opportunities to re-engage them through targeted marketing efforts.

# Insights

Sales Concentration: Major sales are concentrated in a few key cities such as San Francisco, Los Angeles, and New York City, highlighting areas with higher purchasing power and frequent transactions.
Product Popularity: Monitors and batteries are among the top-selling products, indicating their popularity and demand among consumers.
Customer Behavior: Certain customers, like the one at 193 Forest St, show a high responsiveness to promotions and deals, making them ideal targets for future marketing campaigns.
Engagement Opportunities: Identifying least interactive customers provides a basis for targeted re-engagement strategies to boost their participation and increase overall sales.
Trend Analysis: Understanding product trends and shelf life helps in optimizing inventory management and ensuring the availability of popular items.
# Conclusion
This project showcases the effective use of SQL for performing a comprehensive sales analysis. The insights derived from the dataset can aid in strategizing sales promotions, understanding market trends, and improving customer engagement. SQL proves to be a powerful tool for data analysis, enabling businesses to make informed decisions based on accurate data insights.
