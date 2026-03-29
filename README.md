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

---SQL commands used for data analysis---

# To find 'Total Revenue':
<img src="https://github.com/user-attachments/assets/1259388b-7134-4b27-b9f3-f7b4cb9b8d39" width="450">
<br>
<img src="https://github.com/user-attachments/assets/0b709784-8379-40b3-a0f6-559684db134f" width="450">

# To find 'Orders by shipping method':
<img src="https://github.com/user-attachments/assets/eba8fa48-7365-400d-a715-09f7bc112b86" width="450">
<br>
<img src="https://github.com/user-attachments/assets/2fb9f817-e214-43d5-a087-817c317bddcf" width="450">

# To find 'Revenue by product':
<img src="https://github.com/user-attachments/assets/140f97d6-0d1b-4eee-af4b-9a4b067c6b04" width="450">
<br>
<img src="https://github.com/user-attachments/assets/5945ba8f-349b-4a07-9a7a-fe01b3457c7b" width="450">

# To find 'Revenue by category':
<img src="https://github.com/user-attachments/assets/e1b483f6-1542-4183-ae88-b8de968baa2b" width="450">
<br>
<img src="https://github.com/user-attachments/assets/e2e4f252-0660-4939-add0-b42456b267d0" width="450">
<br>
<img src="https://github.com/user-attachments/assets/5cfb40a0-62ea-42c1-ae05-b096ecabfaaa" width="450">

# To find 'Top 5 best selling products':
<img src="https://github.com/user-attachments/assets/50267dcb-747d-4f81-a80f-4ca1ec99c679" width="450">
<br>
<img src="https://github.com/user-attachments/assets/fde29aa5-a2e9-4335-8528-31b0660ed134" width="450">

# To find 'Top 10 customers by spending':
<img src="https://github.com/user-attachments/assets/b56bd4fa-c499-4a8b-9244-c46c4277c078" width="450">
<br>
<img src="https://github.com/user-attachments/assets/48a11d36-208b-42ca-9520-5439f8c103c5" width="450">

# To find 'Most profitable product color':
<img src="https://github.com/user-attachments/assets/9721589b-b6fa-4693-87d9-3543d9ff642b" width="450">
<br>
<img src="https://github.com/user-attachments/assets/3753dede-4097-419b-80e0-8a6b6abe3828" width="450">

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
