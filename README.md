
# Customer Shopping Behaviour Analysis

## Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI. It includes data loading, exploratory data analysis, data cleaning, business queries, and an interactive dashboard.

## Dataset

The project uses a customer shopping dataset with 3,900 records. It includes customer demographics, product categories, purchase amounts, reviews, subscriptions, discounts, shipping types, and purchase frequency.

- **Dataset source:** [Customer Shopping Behavior dataset](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI)
- **Local file:** `Customer_Shopping_Behaviour.csv`

## Tools

- **Python and pandas** for loading, cleaning, and exploring the data
- **Google Colab** for running the Python notebook
- **MySQL** for querying the prepared data
- **Power BI** for building the interactive dashboard

## Project Steps

1. Loaded the dataset into Google Colab using pandas.
2. Reviewed the data structure, summary statistics, missing values, and duplicate records.
3. Cleaned column names and removed unnecessary or duplicate columns.
4. Created age groups and converted purchase frequency values into days.
5. Used SQL queries to explore revenue, discounts, product ratings, shipping, subscriptions, and customer segments.
6. Built a Power BI dashboard to present key metrics and shopping patterns.

## Dashboard

The Power BI dashboard includes:

- Customer count, average purchase amount, and average review rating
- Revenue and sales by product category
- Revenue and sales by age group
- Customer subscription status
- Revenue by season
- Filters for subscription status, gender, category, and shipping type

## Analysis

The SQL analysis explores questions such as:

- How does revenue compare by gender?
- Which discounted purchases are above the average purchase amount?
- Which products have the highest average review ratings?
- How do average purchase amounts compare by shipping type?
- How do subscriber and non-subscriber spending compare?
- Which products have the highest discount rates?
- How are customers segmented by previous purchases?
- What are the top purchased products in each category?
- How do repeat purchases relate to subscription status?
- How does revenue vary across age groups?

## How to Run

1. Download or clone this repository.
2. Open `Customer_Shopping_Behaviour_Analysis.ipynb` in Google Colab.
3. Upload `Customer_Shopping_Behaviour.csv` to Colab or Google Drive.
4. Update the dataset path in the notebook to match where you uploaded the CSV.
5. Run the notebook cells to load, clean, and explore the data.
6. Load the prepared data into MySQL and run `Customer_Shopping_Behaviour_sql_queries.sql`.
7. Open `Customer_Shopping_Behaviour_Dashboard.pbix` in Power BI Desktop to explore the dashboard.

## Project Files

- `Customer_Shopping_Behaviour.csv` — customer shopping dataset
- `Customer_Shopping_Behaviour_Analysis.ipynb` — Python data cleaning and exploratory analysis notebook
- `Customer_Shopping_Behaviour_sql_queries.sql` — SQL analysis queries
- `Customer_Shopping_Behaviour_Dashboard.pbix` — Power BI dashboard
