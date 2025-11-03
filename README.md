
#  SQL_Finance_360_Insights
----

In order to find insights like **total transactions, user activity, payment methods, and city-wise performance, this SQL case study** examines financial and **transactional data.**
It illustrates **sophisticated querying** strategies for practical **financial analytics, such as conditional aggregation, grouping, and joins.**

-----
# 🔑 Key Features

**⭐ Comprehensive Transaction Analysis :–** Evaluates total transactions, unique users, and transaction distribution across cities.<br>
**⭐ Credit & Debit Segmentation :–** Separately calculates total credited and debited amounts for each account type.<br>
**⭐ City & Category Insights :–** Identifies top-performing cities and categories with the highest average transaction amount.<br>
**⭐ Advanced SQL Querying :–** Demonstrates use of JOIN, GROUP BY, HAVING, and conditional aggregation for deep insights.<br>
**⭐ Data Integrity Handling :–** Detects missing or invalid transaction types using LEFT JOIN and ensures data consistency.<br>

-----
# 🛠 Setup 
---

### *Step 1: Prepare CSV Files*

* Make sure all your CSV files (orders, customers, restaurants, menu, reviews, etc.) are download
* Keep them all in a single folder for quick access



### *Step 2: Create a Database*

1. Open your SQL tool (e.g., *MySQL Workbench* or *SQL Server Management Studio*).
2. Create a new database:

sql
create database zomato;


---

### *Step 3: Import CSV into Tables*

1. Right-click on the *database* in the left panel.<br> <br><img width="1915" height="707" alt="image" src="https://github.com/user-attachments/assets/ada48464-b9ac-4dcb-8a42-e70f65064e39" />
2. Select *Table Data Import Wizard* (or similar option depending on your tool).<br><br> <img width="1918" height="730" alt="image" src="https://github.com/user-attachments/assets/ce50a37e-1a52-4ee3-ab06-67a6d8e9982f" />

3. Browse and select the CSV file you want to import.<br><br><img width="1918" height="901" alt="image" src="https://github.com/user-attachments/assets/7caf521f-8d1d-45bb-84de-2e9daaed6bfd" />

4. Follow the wizard to create the table and map columns correctly and all next next click and then click finish.<img width="1919" height="786" alt="image" src="https://github.com/user-attachments/assets/f62267cd-9e20-45bf-bf65-19fde27fa7ad" />


---

### *Step 4: Repeat for All CSVs*

* Repeat *Step 3* for each CSV file (customers, orders, menu, reviews, delivery partners, etc.) until all data is imported.

---

### ✅ *Step 5: Verify Data*

* Run a simple query to check the data is imported correctly:

sql
SELECT * FROM orders;
SELECT * FROM customers;

---
