# CreditCard_Usage_Analysis
A data visualization project using Power BI, Excel &amp; SQL to analyze customer spending patterns and credit card usage trends.

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Data Processing](#data-processing)
   1. [SQL Method](#sql-method)
   2. [Direct Import in Power BI](#direct-import-in-power-bi)
4. [Insights from the Dashboard](#insights-from-the-dashboard)
   1. [Customer Insights Report](#customer-insights-report)
   2. [Credit Card Transaction Report](#credit-card-transaction-report)
5. [Project Structure](#project-structure)
6. [Acknowledgement](#acknowledgement)
7. [Technologies Used](#technologies-used)
8. [How to Use This Project](#how-to-use-this-project)

---

# Credit Card Analysis & Customer Insights - Power BI Dashboard  

## 📌 Project Overview  
This project analyzes **credit card usage patterns** and **customer demographics** using SQL and Power BI.  
The goal is to uncover trends in spending, customer behavior, and financial insights to assist in data-driven decision-making.  

## 📊 Dataset Description  
The project uses two datasets:  

1. **Credit Card Transactions**  
   - Includes details like card category, annual fees, transaction amounts, credit limits, and utilization ratios.  
2. **Customer Demographics**  
   - Contains age, gender, marital status, job type, income, and satisfaction scores.  

## 🛠️ Data Processing  
The data was prepared in two ways:  
1. **SQL Method**  
   - A SQL script was used to create tables (`cc_detail` and `cust_detail`) and import data from CSV files.  
   - The SQL query structures and loads the data efficiently.  

2. **Direct Import in Power BI**  
   - The Excel files were loaded as text into Power BI.  
   - Data transformations were performed using Power Query.   

## 🔍 Insights from the Dashboard

### 1️⃣ Customer Insights Report
- Total Revenue: $55.3M
- Total Customer Income: $576M
- Total Interest Earned: $8M
- Avg. Customer Satisfaction Score: 3.19
- Top Revenue Generating States: TX, NY, CA, FL, NJ
- Major Revenue Contributors: Business owners, white-collar professionals, and self-employed individuals
- Highest Spending Age Group: 30-40 years

### 2️⃣ Credit Card Transaction Report
- Total Transactions: 656K
- Total Amount Spent: $45M
- Most Used Card Type: Blue
- Top Expenditure Categories: Bills, entertainment, fuel, grocery
- Preferred Payment Method: Swipe (Highest), Chip, Online (Lowest)
- Male customers are contributing more in revenue 30M, female 25M
- Overall Activation rate is 57.5%
- Overall Delinquent rate is 6.06%

## 📁 Project Structure 

* The project structure is as follows:
  
- **sql_queries/load_data.sql**: Contains SQL queries that load data from CSV files into the database.
- **data/credit_card.csv**: A CSV file containing the credit card data.
- **data/customer.csv**: A CSV file containing the customer data.

 



## 🤝 Acknowledgement 
* This project was inspired by similar Data Anaylysis case study, Thanks to the open-source community for resources and guidance. 

## 🛠️ Technologies Used  
* **SQL** **(Postgresql)** – Database creation, data import, and transformations  
* **Power BI** – Data visualization and dashboard creation  
* **Excel** – Initial data structuring and transformation  


## 🚀 How to Use This Project  
1. Clone this repository:  
   ```sh
   https://github.com/Atharv521/CreditCard_Usage_Analysis.git
