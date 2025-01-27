**eCommerce Data Science Assignment**
This repository contains the solution for the eCommerce Transactions Dataset assignment. The task involves performing exploratory data analysis (EDA), building predictive models, and deriving actionable business insights. The dataset consists of three files: Customers.csv, Products.csv, and Transactions.csv. The goal is to apply various data science techniques to derive meaningful insights and predictions from the dataset.

Dataset Overview
You are provided with three CSV files:

Customers.csv
Products.csv
Transactions.csv

Files Description:
Customers.csv:
CustomerID: Unique identifier for each customer.
CustomerName: Name of the customer.
Region: Continent where the customer resides.
SignupDate: Date when the customer signed up.

Products.csv:
ProductID: Unique identifier for each product.
ProductName: Name of the product.
Category: Product category.
Price: Product price in USD.

Transactions.csv:
TransactionID: Unique identifier for each transaction.
CustomerID: ID of the customer who made the transaction.
ProductID: ID of the product sold.
TransactionDate: Date of the transaction.
Quantity: Quantity of the product purchased.
TotalValue: Total value of the transaction.
Price: Price of the product sold.


Assignment Tasks
Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform EDA on the provided dataset.
Derive at least 5 business insights from the EDA:
Insights should be concise (maximum 100 words per insight).
Present the findings in a PDF report (maximum 500 words).
Deliverables:
Jupyter Notebook/Python script containing the EDA code.
PDF report with business insights.


Task 2: Lookalike Model
Build a Lookalike Model that takes a user's information as input and recommends 3 similar customers based on their profile and transaction history. The model should:
Use both customer and product information.
Assign a similarity score to each recommended customer.
Deliverables:
A CSV file named Lookalike.csv containing the map Map<cust_id, List<cust_id, score>> for the first 20 customers (CustomerID: C0001 - C0020).
Jupyter Notebook/Python script explaining the model development.
Evaluation Criteria:
Model accuracy and logic.
Quality of recommendations and similarity scores.


Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques.
Use both customer profile information (from Customers.csv) and transaction information (from Transactions.csv).
Choose any clustering algorithm and any number of clusters between 2 and 10.
Calculate clustering metrics, including the DB Index.
Visualize the clusters using relevant plots.
Deliverables:
Report on clustering results:
Number of clusters formed.
DB Index value.
Other relevant clustering metrics.
Jupyter Notebook/Python script containing the clustering code.
Evaluation Criteria:
Clustering logic and metrics.
Visual representation of clusters.
