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

# Extraction
I utilized Google Cloud Console to perform the analysis by creating the dataset and table, and subsequently loading the data into the table

![Screenshot 2024-07-19 at 10 04 33 PM](https://github.com/user-attachments/assets/b9165646-8c5e-4d23-8ef2-b6ce49489e68)

![Screenshot 2024-07-19 at 10 05 21 PM (2)](https://github.com/user-attachments/assets/50ca0b8e-c4b9-49c3-b779-01e5a60fafd2)

Google Cloud offers two options for creating a table. The first option  is to use the Auto Detect feature, which automatically infers the table schema from the CSV file, making it a quick and convenient method for straightforward datasets. The second option invloves manually defining the table schema, which provides more control and precision. This method requires specifying each field's name, data type, and mode (e.g., NULLABLE, REQUIRED, REPEATED).

For this project, I opted to manually enter the schema to ensure accuracy and alignment with the analysis requirements. O began by giving the table a descriptive name and defining each column's propoerties. For instance, I specified `order_id` as an INTEGER, `product` as a STRING, `quantity_ordered` as an INTEGER and so on. This manual approach allowed me to tailor the table structure precisely to the dataset's needs and ensure that all data types were correctly assigned, facilitating accurate analysis and query performance. By carefully setting up the table schema, I laid a solid foundation for the subsequent data analysis using queries in Google Console.

![Screenshot 2024-07-19 at 10 08 31 PM](https://github.com/user-attachments/assets/acb24cd4-ad8d-4572-abd6-79e352776934)

# Analysis Queries
# Query 1: Total Sales
To determine the overall sales performance:

![Screenshot 2024-08-07 at 12 39 29 PM](https://github.com/user-attachments/assets/308d1473-a87b-4dd0-8a2e-5adf20ee538c)

Result: The total sales of this dataset are $34 Million.

# Query 2: Total Sales by City
To identify the top-performing cities:

![Screenshot 2024-07-20 at 1 18 00 AM](https://github.com/user-attachments/assets/9899637a-05fb-4ac0-80d4-0da2339e09a4)

Result: The top 3 performing cities are San Francisco, Los Angeles, and New York City, indicating higher purchasing power and frequent purchases in these urban areas.

# Query 3: Total Sales by Product
To understand which products are the most popular:

![Screenshot 2024-08-07 at 12 47 37 PM](https://github.com/user-attachments/assets/f21ae5c7-cf70-448c-b105-182ddeec2bb0)

Result: Apple products such as Macbook Pro and iPhone are paritcularly popular.

# Query 4: Customer with Most Purchases and Sales Amount
To identify the most frequent buyers:

![Screenshot 2024-08-07 at 12 37 30 PM](https://github.com/user-attachments/assets/91c5079f-dfdc-4227-92f6-646e29e4df03)

Result: The address 193 Forest St made the most purchases during the reporting period, indicating a highly responsive customer to deals and promotions.

# Query 5: Least Interactive Customers
To find customers with minimal interaction:

![Screenshot 2024-08-07 at 12 38 28 PM](https://github.com/user-attachments/assets/db434031-ec64-4a03-b508-d21998601fc2)

Result: Identified customers who interacted the least with the platform, providing opportunities to re-engage them through targeted marketing efforts.

# Insights
* Sales Concentration: Major sales are concentrated in a few key cities such as San Francisco, Los Angeles, and New York City, highlighting areas with higher purchasing power and frequent transactions.
* Product Popularity: Apple products are among the top-selling products, indicating their popularity and demand among consumers.
* Customer Behavior: Certain customers, like the one at 193 Forest St, show a high responsiveness to promotions and deals, making them ideal targets for future marketing campaigns.
* Engagement Opportunities: Identifying least interactive customers provides a basis for targeted re-engagement strategies to boost their participation and increase overall sales.
* Trend Analysis: Understanding product trends and shelf life helps in optimizing inventory management and ensuring the availability of popular items.
  
# Conclusion
This marks the end of my analysis. This project showcases the effective use of SQL for performing a comprehensive sale analysis. The insights derived from the dataset can aid in strategizing sales promotions, understanding market trends, and improving customer engagement. SQL proves to be a powerful tool for data analysis, enabling businesses to make informed decision based on accurate data insights.
