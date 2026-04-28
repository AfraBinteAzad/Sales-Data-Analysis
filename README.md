This project focuses on analyzing a sales dataset to uncover business insights and build a machine learning model to predict revenue.

The goal is to transform raw transactional data into meaningful insights that can help businesses make data-driven decisions.

Dataset Description

The dataset contains 254 sales records with the following features:

Order ID – Unique identifier for each order
Date – Transaction date
Product – Item purchased
Price – Price per unit
Quantity – Number of units sold
Purchase Type – Online / In-store
Payment Method – Payment type used
Manager – Sales manager responsible
City – Location of sale

Data Preprocessing
Cleaned text fields (removed extra spaces)
Removed duplicate records
Created new feature:
Revenue = Price × Quantity
Extracted time-based features:
Year, Month, Day, Day of Week
Encoded categorical variables using One-Hot Encoding

Exploratory Data Analysis (EDA)

Key analysis performed:

Revenue distribution across products
Sales performance by city
Payment method trends
Monthly revenue trends

Key Insights
Burgers generated the highest revenue, making them the top-performing product.
Lisbon recorded the highest total sales, indicating a strong market.
Credit card payments contributed the most revenue, suggesting customer preference for digital payments.

Machine Learning Model
Model Used:
Linear Regression
Objective:

Predict Revenue based on sales features.

Model Performance
Mean Absolute Error (MAE): 148.92
R² Score: 0.994
Interpretation:
The model explains ~99.4% of the variance in revenue.
Very high accuracy, mainly because revenue is directly derived from price and quantity.

Future Improvements

To make this project more advanced:

Use Random Forest / XGBoost for better generalization
Build a Sales Forecasting Model (Time Series)
Develop a Recommendation System
Create a Dashboard (Power BI / Tableau)

Conclusion

This project demonstrates how raw sales data can be transformed into:

Actionable business insights
Predictive models for decision-making

It highlights the importance of data preprocessing, feature engineering, and proper model evaluation in real-world data science workflows.