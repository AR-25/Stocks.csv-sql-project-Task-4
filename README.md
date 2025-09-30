# Stocks.csv-sql-project-Task-4

# Task 5: Time Series Analysis of Stock Data - Summary of Insights

This analysis explored the historical closing prices of the AAPL stock to identify underlying trends and patterns.

* **Overall Trend**: The decomposition analysis clearly shows a strong, long-term upward trend in the stock price over the observed period.
* **Seasonality**: A distinct yearly seasonal pattern was identified. The stock price typically shows strength in the later months of the year and experiences a dip in the mid-year months.
* **Stationarity**: An Augmented Dickey-Fuller (ADF) test was performed on the daily closing prices. The resulting p-value was significantly greater than 0.05, which leads us to conclude that the time series is non-stationary, as is common with financial data that exhibits a clear trend.
