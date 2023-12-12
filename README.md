# Retail Sales Statistics Exploration

Analyzing product sales data to uncover trends and insights for a retail store.

**Overview**
This project performs statistical analysis on a sample dataset of retail sales transactions over the past year. The goal is to analyze key metrics related to sales, revenue, staffing, and other attributes to uncover trends, correlations, and make predictions to support critical business decisions.

The analysis is implemented in SQL and visualized in a Jupyter notebook.

**Contents**
The repository contains the following files:

* analysis.ipynb: Jupyter notebook with SQL querying the database and visualizing results
* sales.sql: SQL script to create the sales database table and populate sample rows of data

**Notebooks**
The Jupyter notebooks provide the analysis:

**Sales Statistics**
* Descriptive stats like total transactions, average sales
* Trends over month, year
* Correlations between product sales and revenue, staffing
* Predictive analysis like required staff levels

**Database**
The sales.sql script creates the table to hold the raw transaction data.

**Store Sales**
* Date, month, year of sale
* Number of employees working
* Sale quantities
* Revenue generated
  
**To run this analysis:**
* Create the store_sales table in a database by running sales.sql
* Load sample data into the table, or use your own store's sale data
* Open analysis.ipynb, connect to the database, and run each cell to generate insights!

**There are many additional types of analysis that could provide further insights:**
* Statistical analysis by product type, brand, size etc
* Grouping by store location/region
* Incorporating operational costs, profits etc
* Drill-downs on key drivers behind trends

Thanks for viewing the project :)

