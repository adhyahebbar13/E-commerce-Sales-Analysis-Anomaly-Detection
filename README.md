# E-commerce-Sales-Analysis-Anomaly-Detection
This project analyzes the Olist E-commerce dataset to extract insights on sales trends, customer behavior, product performance, and delivery patterns. Additionally, it identifies unusual or anomalous transactions using machine learning techniques.
The analysis leverages Pandas, Seaborn, Matplotlib, and Scikit-learn for data cleaning, exploration, visualization, and anomaly detection.

Dataset
Source: Olist E-commerce Dataset on Kaggle

Contents: Orders, order items, customers, products, sellers, and payments.

Size: 100,000+ orders with multiple related tables.


Objectives
Explore sales trends by day, month, and product category.

Identify top customers, best-selling products, and regional revenue differences.

Detect anomalous transactions (e.g., extremely high prices, long delivery times) using Isolation Forest.

Perform Market Basket Analysis to find products frequently bought together.

Visualize key findings in a portfolio-ready manner.


Methods & Tools

Data Cleaning: Handling missing values, stripping column names, type conversions, datetime parsing.

Exploratory Data Analysis (EDA): GroupBy, pivot tables, aggregations, sales trend plots.

Visualization: Line plots, bar charts, heatmaps, scatter plots using Matplotlib and Seaborn.

Anomaly Detection: Isolation Forest on price, freight_value, and delivery_time.

Market Basket Analysis: Apriori algorithm to identify frequent product combinations and association rules.


Key Insights
Top product categories and best-selling products identified.

Peak sales months and regional revenue patterns visualized.

Anomalous orders flagged for unusually high prices, weights, or delivery times (~2% of total orders).

Market Basket Analysis revealed co-purchased product categories, highlighting cross-selling opportunities.


Files

ecommerce_analysis.ipynb — Jupyter Notebook with full analysis, visualizations, and anomaly detection.

README.md — Project description and instructions.

