Smart Price Analyzer & Predictor

This project is a Streamlit web application designed to analyze the e-commerce sales data from data.csv. It provides a user-friendly interface to explore sales trends, visualize key metrics, and predict the unit price of items using a machine learning model.

Features

The application is split into two main sections:

1. Price Prediction

Predictive Model: Uses a trained Random Forest Regressor to predict the UnitPrice of an item.

User Inputs: Allows you to select features to get a live price prediction:

StockCode

Country

Quantity

Month

Day of Week

2. Data Analysis Dashboard

Key Metrics: Displays high-level KPIs:

Total Revenue

Total Items Sold

Average Unit Price

Visualizations: Includes a comprehensive set of charts to understand the data:

Monthly Sales Revenue: A line chart showing sales trends over time.

Top 10 Countries by Revenue: Bar chart of the highest-performing countries.

Top 10 Products by Revenue: Bar chart of the best-selling products.

Top 10 Customers by Revenue: Bar chart of the most valuable customers.

Unit Price Distribution: A histogram showing the frequency of different price points.

Quantity vs. Unit Price: A scatter plot to identify relationships between order quantity and price.
