# Market Basket Analysis with BigQuery

# Overview
This project involves conducting a market basket analysis using data obtained from a BigQuery dataset. The data is dynamic and may vary from the source over time.

# Objective
The goal is to uncover associations and patterns between different products purchased together, helping businesses understand customer buying behavior.

# Data Source
The dataset for this analysis was acquired from a BigQuery source. Please note that the data is subject to change and may not be identical upon return visits to the source.

# Methodology
Data Querying with SQL:
SQL queries were used to extract relevant data from BigQuery. The data includes transactional information such as order IDs, product IDs, quantities, and timestamps.
# Data Preprocessing:
Cleaning and preparing the data for analysis.
Combining relevant columns (e.g., product ID and name) to create unique identifiers.
# Market Basket Analysis:
Applying the Apriori algorithm to discover frequent itemsets (combinations of products frequently purchased together).
Calculating association rules (if product A is purchased, what other products are likely to be purchased).
Insights and Recommendations:
Interpreting the discovered rules to gain insights into customer behavior.
Recommending strategies for cross-selling, inventory management, and promotions.
Usage
# SQL Queries:
Use SQL queries to extract relevant data from BigQuery.
Explore different dimensions ( time, location, product categories) to refine your analysis.
# Apriori Algorithm:
Run the Apriori algorithm on the preprocessed data.
Adjust support and confidence thresholds to discover meaningful patterns.
