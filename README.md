# Store Revenue Analysis 
This repository contains Python code that analyzes store revenue data using pandas DataFrame operations.

###  Code Overview
The main file, store_revenue_analysis.py, performs the following tasks:

#### 1. Data Setup
Creates a list of dictionaries representing product data.
Converts the list to a pandas DataFrame and sets column headers.
#### 2. Categorization of Products
Defines a function categorise_products to categorize products into 'computers', 'food', or 'books' based on their names.
Applies this function to the DataFrame's 'name' column and saves the result in a new 'category' column.
#### 3. Revenue Analysis
Calculates net revenue per product using groupby and sum operations based on product categories ('computers', 'food', 'books').
Calculates new net revenue after applying a 30% discount on the wholesale price.
#### 4. Revenue with Sales Tax
Creates new columns in the DataFrame for revenue with different sales tax rates (15%, 20%, 25%).


### Note
Ensure that you have pandas library installed (pip install pandas) to run the code successfully.
Input data can be modified by updating the list of dictionaries in the code.
Adjustments to categorization logic or revenue calculations can be made by modifying respective functions.


