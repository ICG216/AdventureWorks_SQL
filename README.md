# Exploratory Data Analysis (EDA) on AdventureWorks Database

## Description
This project performs exploratory data analysis (EDA) on a fictional business database hosted in Azure SQL. The analysis aims to uncover key insights into customer purchasing behavior, product performance, and overall revenue trends. SQL queries are executed in a Python Jupyter Notebook environment to support strategic decision-making by analyzing sales and product data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [SQL Queries](#sql-queries)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/adventureworks-eda.git
   cd adventureworks-eda

## Set up the environment:

Install the required Python libraries:

   ```bash
pip install sqlalchemy pyodbc pandas jupyter
```
**Configure the database connection:**

Update the connection string in the notebook (replace with your Azure SQL database credentials):
   ```bash
connection_string = "mssql+pyodbc://<username>:<password>@<server>/<database>?driver=ODBC+Driver+17+for+SQL+Server"
 ```
## Usage
Launch the Jupyter Notebook:

jupyter notebook notebooks/eda_adventureworks.ipynb

**Run the notebook cells to execute the SQL queries and analyze the database. Key analyses include:**

Total revenue by product categories
Distribution of order quantities across product categories
Customer spending patterns
Product performance and popularity

## SQL Queries
Key SQL queries include:

- Revenue by Product Category: Analyze which product categories generate the most revenue.
- Order Quantity Distribution: Explore the most common order quantities in different product categories.
- Top Customers by Total Revenue: Identify the customers who have spent the most.