# Data Cleaning and Analysis

This repository contains a Jupyter notebook with code for analyzing sales data. The data consists of four CSV files: products_cl.csv, orders_cl.csv, orderlines_cl.csv, and brands_cl.csv.

The notebook starts by loading the data into Pandas DataFrames. It then merges the orderlines_cl and products_cl DataFrames to create a new DataFrame called ol_p_cl, which contains information about each order line and its associated product. 

It calculates the discount and discount percentage for each order line and adds those columns to the DataFrame. It also converts the date column to a datetime format and creates a new column for revenue.

The notebook then proceeds to perform various analyses on the data, including:

- A scatter plot of SKU vs. discount percentage
- A time series plot of discount totals by year and month
- A horizontal bar chart of discounts by month
- A bar chart of the top 10 most discounted brands
- A bar chart of the top 10 most ordered products
- A time series plot of discounts between November and December 2017
- A bar chart of average discounts by brand for November and December 2017
- A time series plot of discounts between June and July 2017
- A function for categorizing products based on their name and description
- A horizontal bar chart of the top 10 most discounted product categories
- A horizontal bar chart of the top 10 most expensive product categories
- A horizontal bar chart of the top 10 product categories by revenue


This code should be helpful for anyone who wants to analyze sales data and understand trends in customer behavior.
