# Zomato_Data_Analysis
Zomato Restaurant Data Analysis
## Overview
This project presents an in-depth exploratory data analysis (EDA) of restaurant data sourced from Zomato. The goal is to derive actionable insights on restaurant trends, customer preferences, cost dynamics, and performance indicators based on ratings, online ordering, table booking, and restaurant types.

The dataset consists of 148 restaurants, with attributes like:

Restaurant Name
Online Ordering Availability
Table Booking Availability
Rating (out of 5)
Number of Votes
Approximate Cost for Two People
Type of Restaurant (e.g., Delivery, Dine-out, Cafes)

## Data Preprocessing
Cleaned and standardized the rate column by extracting numerical values.

Verified datatype consistency for key columns.

No missing values were present, ensuring a clean analytical base.

## Key Analyses & Visualizations
### 1. Distribution of Restaurant Types
The dataset includes a variety of listings such as Delivery, Dine-out, Cafes, and more.

Count plots and aggregation show "Delivery" restaurants dominate the dataset, followed by Dine-out options.

### 2. Votes by Restaurant Type
Restaurants listed as "Delivery" and "Dine-out" received the highest total votes.

This indicates that customers are most actively engaged in these two categories.

### 3. Rating Distribution
The majority of ratings fall between 3.5 and 4.5 stars.

Less than 10% of restaurants scored below 3.0, indicating generally high customer satisfaction.

### 4. Cost Analysis for Two People
The most common price point is around ₹300 to ₹500.

High-end restaurants (₹800+) make up <15% of listings.

### 5. Online Order vs Rating
Restaurants offering online orders have a slightly higher average rating (~4.0) than those that don’t.

Visualized using box plots to show rating variability and median values.

### 6. Heatmap: Restaurant Type vs Online Ordering
A heatmap of a pivot table showed that:

Delivery restaurants overwhelmingly support online orders.

Cafes and Desserts are less likely to provide online ordering options.

### 7. Correlation Analysis
Using a heatmap of numerical correlations:

Votes and ratings showed a strong positive correlation (~0.65).

Cost has a mild correlation with ratings and votes.

Online ordering and table booking were not strongly correlated with cost.

### 8. Top 10 Restaurants
Based on a combination of the highest ratings and maximum votes.

Barplots were used to visualize:

These restaurants consistently had ratings above 4.5.

They also received over 500 votes each, indicating both quality and popularity.

### 9. Table Booking vs Cost
Restaurants with table booking available had a higher median cost (₹600–₹1000).

Boxplots confirmed that booking availability often indicates premium pricing.

## Insights & Conclusions
Online Ordering contributes positively to customer satisfaction (reflected in ratings).

Table Booking is more common among higher-end restaurants.

The sweet spot for pricing is ₹300–₹500, with most customer engagement concentrated here.

Delivery-based services dominate both in quantity and customer interaction.

Ratings and vote count are reliable indicators of restaurant popularity.

## Project Structure
Zomato_Analysis.ipynb: Full Python notebook with visualizations and analysis.

Zomato data .csv: Cleaned dataset used for the analysis.

💡 Technologies Used
Python

Pandas & NumPy – Data manipulation and aggregation

Matplotlib & Seaborn – Visualizations

Jupyter Notebook – Interactive EDA


 ## Results Snapshot
Metric	Value / Insight
Most common cost range	₹300–₹500
Highest-rated restaurant	> 4.8 stars with > 500 votes
Online order vs rating	: +5–7% higher ratings on average
Table booking impact	Avg. cost ↑ ~35% when available
Rating distribution	70%+ of restaurants rated > 3.5

## Final Thoughts
This project provides a strategic overview of how different restaurant features impact customer engagement and satisfaction. The findings can aid restaurant owners, marketers, and food delivery platforms refine their service models for better customer alignment.


