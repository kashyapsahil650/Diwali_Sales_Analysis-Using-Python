# Diwali_Sales_Analysis-Using-Python
# Diwali Sales Analysis: Exploratory Data Analysis using Python
# Description
This project focuses on analyzing Diwali sales data to gain insights and perform exploratory data analysis (EDA) using Python. The analysis aims to understand sales patterns, trends, and correlations in the dataset.

# Table of Contents
Importing Dependencies
Data Description
Data Cleaning
EDA Steps
Conclusion
# Importing Dependencies
we have imported following python Libraries Numpy, Pandas, Matplotlib, Seaborn

# Data Description
The dataset used for this analysis contains Diwali sales data for a specific period. The data is provided in CSV format and includes the following columns:

User_ID : The Id of person

Cust_name : Customer Name

Product_ID : Id of each product

Gender : Gender of each person
Age Group : Age range for person
Age : age of each person
Marital_Status : Married person was represented by 1 and unmarried by 0
State : State from which person belongs
Zone : In which zone person belongs
Occupation : Occupation of each person
Product_Category : different category of products
Orders : Number of orders
Amount : Amount spend by customer
Status : Blank column
unnamed1 : Blank column
In the dataset there are 11251 rows and 15 columns.

# Data Cleaning
In our Dataset there are 2 columns which are blank columns named 'Status' and 'unnamed1', so firstly we remove both the columns. Now we check for null values in dataset and remove these null values.

# EDA Steps
1.We create Bar chart with the help of seaborn library between Gender and count and another one between Gender and Amount We can see that most of the buyers are females and even the purchasing power of men are lesser than female

2.Now we create barplot between Age group and count and another between Total Amount and age group. From these graphs we can see that most of the buyers are of age group between 26-35 yrs female

3.Now we create Barplot between State and orders and another barplot between state and total amount. From these graphs we can see that most of the orders & total sales/amount are from Uttar Pradesh, Maharashtra and Karnataka respectively

4.Now we create Barplot between Marital_Status and count and another barplot between Marital_Status and Amount. From these graphs we can see that most of the buyers are married (women) and they have high purchasing power.

5.Now we create Barplot between Occupation and count and another barplot between Occupation and amount. From these graphs we can see that most of the buyers are working in IT, Healthcare and Aviation sector

6.Now we create Barplot between Product_Category and count and another barplot between Product_category and amount From above graphs we can see that most of the sold products are from Food, Clothing and Electronics category

At end we find Top 10 most sold products.

# Conclusion
Married women in the 26-35 age range from the states of Uttar Pradesh, Maharashtra, and Karnataka who work in the IT, healthcare, and aviation industries are more likely to purchase items from the food, clothing, and electronics categories.
