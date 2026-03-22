# Google Data Analytics Capstone Case Study

   This presentation is a project for my Google Data Analytics capstone case study. I am using a synthetic dataset generated with ChatGPT that has 2 tables. I have given this fictitious small outdoor camping retail business the name of "Outdoor Palooza". Items such as trail running shoes, hiking socks, backpacks, lanterns, and foldable chairs are some of the items offered for sale. This synthetic dataset provides a safe, realistic environment for exploring sales trends, customer behavior, inventory count as well as practicing exploratory data analysis.

Tables included are orders_table and products_table.

orders_table columns include:                  
   - order_id                                     
   - product_id                                   
   - customer_id                                  
   - price                                       
   - quantity                                     
   - discount                                     
   - order_date                                   
   - shipping_date                                
   - shipping_method                              
   - order_status

products_table columns include:
   - product_id
   - product_name
   - product_category
   - manufacturing_city
   - size
   - color
   - SKU
   - unit_cost
   - release_year

I will begin my analysis by importing both tables into Excel and merging the two .csv files into one .xlsx file having two sheets to work with. I will check for duplicate rows. I will remove extra spaces. I will convert text dates to integer dates. I will filter columns to check for blanks and decide to replace with "Unknown", "NA", or just leave blank.
I will now convert my .xlsx file into a .csv file so that I can import it into Bigquery so that I can run some SQL commands since Bigquery does not accept .xlsx files.

SQL commands used for data analysis:

To find 'Total Revenue':
SELECT SUM(price * quantity) AS total_revenue
FROM orders;

To find 'Orders by shipping method':
SELECT shipping_method, COUNT(*) AS total_orders
FROM orders
GROUP BY shipping_method;

To find 'Revenue by product':
SELECT
   p.product_name,
   SUM(o.price * o.quantity) AS revenue
FROM orders o
JOIN product p



- Questions to Explore:

How does customer age and gender influence their purchasing behavior?
Are there discernible patterns in sales across different time periods?
Which product categories hold the highest appeal among customers?
What are the relationships between age, spending, and product preferences?
How do customers adapt their shopping habits during seasonal trends?
Are there distinct purchasing behaviors based on the number of items bought per transaction?
What insights can be gleaned from the distribution of product prices within each category?

Columns description:

Transaction ID: A unique identifier for each transaction, allowing tracking and reference.
Date: The date when the transaction occurred, providing insights into sales trends over time.
Customer ID: A unique identifier for each customer, enabling customer-centric analysis.
Gender: The gender of the customer (Male/Female), offering insights into gender-based purchasing patterns.
Age: The age of the customer, facilitating segmentation and exploration of age-related influences.
Product Category: The category of the purchased product (e.g., Electronics, Clothing, Beauty), helping understand product preferences.
Quantity: The number of units of the product purchased, contributing to insights on purchase volumes.
Price per Unit: The price of one unit of the product, aiding in calculations related to total spending.
Total Amount: The total monetary value of the transaction, showcasing the financial impact of each purchase.

Suggested Explorations:

Analyze spending patterns by gender or age group.
Track most popular product categories over time.
Predict total amount spent based on customer features.
Identify seasonal or monthly spikes in certain categories.

* I will show how I cleaned the datasets in Excel here.

Data Cleaning & Preprocessing
✅ Handle missing values (Jarak_Kirim_KM, Rating_Pelanggan)
✅ Detect & treat outliers (Harga_Pesanan)
✅ Standardize datetime formats
✅ Text preprocessing for reviews

* I will show how I used Bigquery for my SQL requests here.

* I will show my visualizations here.

* List insights here. 

* I will address the stakeholders here.
