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
I will then convert my .xlsx file into a .csv file so that I can import it into Bigquery so that I can run some SQL commands since Bigquery does not accept .xlsx files.

---SQL queries used for data analysis---

# To find 'Total Revenue':
<img src="https://github.com/user-attachments/assets/1259388b-7134-4b27-b9f3-f7b4cb9b8d39" width="450">
<br>
<img src="https://github.com/user-attachments/assets/0b709784-8379-40b3-a0f6-559684db134f" width="450">

# To find 'Orders by shipping method':
<img src="https://github.com/user-attachments/assets/eba8fa48-7365-400d-a715-09f7bc112b86" width="450">
<br>
<img src="https://github.com/user-attachments/assets/2fb9f817-e214-43d5-a087-817c317bddcf" width="450">

# To find 'Total revenue by product':
<img src="https://github.com/user-attachments/assets/4f222f4c-2467-4119-bb17-8686d5fdbfd6" width="450">
<br>
<img src="https://github.com/user-attachments/assets/034ae9fb-2852-4520-979f-b247d2b59b51" width="450">

# To find 'Total revenue by category':
<img src="https://github.com/user-attachments/assets/a7f07fda-ab1b-4e17-a995-17223c2a0872" width="450">
<br>
<img src="https://github.com/user-attachments/assets/112f862c-052e-486a-b069-8dd7fcf40b32" width="450">
<br>
<img src="https://github.com/user-attachments/assets/296012fc-0065-4961-8e24-68c07701806a" width="450">

# To find 'Total profit by category':
<img src="https://github.com/user-attachments/assets/fd7e2f20-75f1-475a-9c6c-270fdf299056" width="450">
<br>
<img src="https://github.com/user-attachments/assets/b5851036-5020-4d07-a8ff-13880e491e5d" width="450">
<br>
<img src="https://github.com/user-attachments/assets/d824ea32-ddb9-48c6-9e08-1557a80b769c" width="450">

# To find 'Top 5 best selling products':
<img src="https://github.com/user-attachments/assets/50267dcb-747d-4f81-a80f-4ca1ec99c679" width="450">
<br>
<img src="https://github.com/user-attachments/assets/fde29aa5-a2e9-4335-8528-31b0660ed134" width="450">

# To find 'Top 10 customers by spending':
<img src="https://github.com/user-attachments/assets/b56bd4fa-c499-4a8b-9244-c46c4277c078" width="450">
<br>
<img src="https://github.com/user-attachments/assets/48a11d36-208b-42ca-9520-5439f8c103c5" width="450">

# To find 'Most profitable product color':
<img src="https://github.com/user-attachments/assets/064ab927-ced1-4fe4-a7fc-b24be7f038d2" width="450">
<br>
<img src="https://github.com/user-attachments/assets/a72371e3-90c8-4aac-8af9-5c71402df4a5" width="450">
<br>
<img src="https://github.com/user-attachments/assets/80436b79-919a-467c-a4d7-4548edfb5d7d" width="450">

# To find 'Products with declining monthly sales':
<img src="https://github.com/user-attachments/assets/6aeeb954-cca9-4fb6-9e43-860ab45aa013" width="450">
<br>
<img src="https://github.com/user-attachments/assets/f5fa63f1-c213-4f4c-8eae-6de7107298bb" width="450">
<br>
<br>



# Questions to Explore:

- How does inventory turnover vary across seasons or product types?
- Are there discernible patterns in sales across different time periods?
- Which product categories hold the highest appeal among customers?
- What is the customer purchase frequency by product category?
- Are there distinct purchasing behaviors based on the number of items bought per transaction?
- Where best to add additonal manufacturing?


* I will show my visualizations here.

* List insights here. 

* I will address the stakeholders here.
