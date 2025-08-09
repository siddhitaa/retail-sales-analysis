# Retail Sales Analysis
## Project Overview
This project analyzes transactional data from an online retail store to uncover key insights into sales performance, customer behavior, and product trends. Using data cleaning, exploratory data analysis (EDA), and visualization techniques, the goal is to help the business make data-driven decisions to improve sales strategies, inventory management, and customer retention.

## Dataset
The dataset used is the Online Retail dataset from the UCI Machine Learning Repository, which contains all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail store. It includes:

Invoice number

Stock code and product description

Quantity purchased

Invoice date

Unit price

Customer ID

Country of the customer

## Analysis Steps
### Data Cleaning:

Removed transactions with missing Customer IDs

Filtered out negative quantities representing returns

Converted date columns to proper datetime format

Created a new column for total sales value (TotalPrice = Quantity × UnitPrice)

### Exploratory Data Analysis (EDA):

Identified top-selling products by revenue

Analyzed sales distribution by country

Examined monthly sales trends to identify seasonality and growth

Found top customers by total spending

### Visualization:

Bar charts for top products and countries by sales

Line chart showing monthly sales trend

Customer spending visualized to identify loyal customers

## Key Insights
A small number of products generate the majority of revenue.

Sales are concentrated in a few countries, suggesting market opportunities.

Monthly sales show seasonal patterns that can inform inventory planning.

Identifying top customers enables targeted marketing and loyalty programs.

## Tools & Libraries
Python (Pandas, Matplotlib, Seaborn)

Jupyter Notebook for interactive analysis

## How to Use This Repo
Download or clone the repository.

Ensure you have the required libraries installed (pandas, matplotlib, seaborn).

Open and run the Jupyter notebook retail_sales_analysis.ipynb to explore the data and analysis.

## Future Work
Implement customer segmentation using RFM analysis.

Build predictive models for sales forecasting.

Create interactive dashboards with tools like Tableau or Power BI.

### Feel free to reach out for any questions or collaboration opportunities!
