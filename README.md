Retail Demand Forecasting and Inventory Optimization Using Machine Learning


This project is based on the UCI Online Retail dataset, which contains over a year of sales transactions from a UK-based online retailer.

What happened in this project:

I used machine learning to predict daily sales for a popular product.

I cleaned the data by removing returns, non-UK sales, and missing values.

I created new features, like previous day’s sales and weekly averages, to better capture sales patterns.

I explored the data with plots and found clear seasonality and trends.

I trained and compared four models: Random Forest, Decision Tree, SGD Regression, and Logistic Regression.

Random Forest Regression gave the most accurate sales forecasts.

Logistic Regression was used to predict days with a high risk of running out of stock and was very accurate.

Using these predictions, I calculated when to reorder stock (reorder point: 1,291 units) and how much extra to keep as safety stock (454 units) for a 95% service level and 7-day lead time.

In summary:
This project shows that machine learning can help retailers better predict demand, avoid stockouts, and reduce extra inventory. The approach can be expanded to more products and real-time dashboards in the future.
