# Retail_orders
It is divided into two a Jupyter Notebook that uses python and sql to analyze the dataset and a visualization table 
Overview
This Jupyter Notebook is designed to demonstrate how to use Python and SQL to analyze a retail dataset from Kaggle. It covers data loading, cleaning, transformation, and analysis to extract insights from the data.

## Table of Contents of the Jupyter Notebook
Installation, Data Loading, Data Exploration, Data Cleaning, Data Transformation, Analysis, Conclusion

## Data Loading
The notebook starts by importing necessary libraries and setting up the Kaggle API to download the retail orders dataset. It checks if the dataset is already available locally before downloading.

## Data Exploration
Once the data is loaded, exploratory data analysis (EDA) is performed, including:

Viewing the first few rows of the dataset.
Checking the shape and structure.
Identifying missing values.

## Data Cleaning
The data is cleaned by:

Replacing invalid entries in the 'Ship Mode' column.
Handling missing values effectively.

## Data Transformation
Key transformations include:

Renaming columns for better readability.
Creating new columns such as discount, selling_price, and profit.
Converting the order_date column to a datetime format.

## Analysis
The notebook conducts various analyses, including:

Total Revenue per Category: Calculates total revenue generated for each product category.
Top 3 Profitable Cities: Identifies cities with the highest total profit.
Profit Margin per Product: Analyzes profitability of different products.
Order Counts by Shipping Mode: Examines the frequency of different shipping methods.
Monthly Order Counts for 2023: Analyzes order trends on a month-by-month basis.
States with Lowest Sales: Identifies states with the lowest sales figures.
Top 5 Products by Revenue: Lists the highest-grossing products in terms of sales.

Conclusion
By executing the notebook, users can gain insights into sales performance, customer trends, and product profitability. This analysis can inform business decisions and strategies for improving sales.

# Visualization
# Data Visualization Project

## Overview

This project focuses on data visualization techniques using a dataset from Kaggle. The dataset consists of various orders that contain information such as order date, ship mode, segment, country, state, and sales metrics.

## Objectives

The main objectives of this project are:
- To load necessary libraries for data analysis and visualization.
- To load the dataset and explore its contents.
- To perform univariate, bivariate, and multivariate analyses using different visualization techniques.

## Key Sections

### 1. Loading Libraries
The project uses the following libraries:
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: A higher-level interface for drawing attractive statistical graphics.
- **Pandas**: For data manipulation and analysis.

### 2. Loading Data
The dataset is loaded into a pandas DataFrame, allowing for easy manipulation and analysis.

### 3. Univariate Analysis
- **Histogram**: Displays the distribution of discount percentages.
- **Box Plot**: Shows the spread and outliers for quantities sold.
- **Bar Plot**: Illustrates the frequency of different categories in the dataset.

### 4. Bivariate Analysis
- **Scatter Plot**: Examines the relationship between cost price and quantity sold.
- **Grouped Bar Plot**: Visualizes the count of segments by region.

### 5. Multivariate Analysis
Further visualizations, including pair plots and heatmaps, are generated to explore relationships among multiple variables.


