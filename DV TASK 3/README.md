# Shopify Stock Data Understanding, Cleaning & Exploratory Analysis

## Project Overview

This project focuses on understanding, cleaning, and analyzing **Shopify stock market data**.

The analysis uses price and trading volume information to study daily stock movements, returns, trading activity, and unusual trading days.

## Objectives

* Load and clean stock price data.
* Analyze Open, High, Low, Close, and Volume values.
* Calculate daily price changes.
* Calculate daily percentage returns.
* Study trading volume trends.
* Identify unusual trading days.
* Analyze the distribution of stock returns.

## Data Cleaning

The following price attributes are checked and cleaned:

* **Open** – Opening price of the stock.
* **High** – Highest price during the trading day.
* **Low** – Lowest price during the trading day.
* **Close** – Closing price of the stock.
* **Volume** – Number of shares traded.

Missing or invalid values are handled before performing the analysis.

## Daily Price Delta

The daily price change is calculated using:

**Price Delta = Close − Open**

A positive value means the closing price was higher than the opening price.

A negative value means the closing price was lower than the opening price.

## Daily Percentage Return

Daily percentage return is calculated to understand the percentage change in the stock price from one trading day to the next.

Returns help measure the daily performance of the stock.

## Trading Volume Analysis

Trading volume is analyzed over time to understand how actively the stock was traded.

Unusually high or low trading volume days are identified as **anomalous trading days**.

These days may show unusual market activity and can be studied further.

## Return Distribution

The distribution of daily returns is summarized using:

* **Mean** – Average daily return.
* **Variance** – Measures how much the returns vary from the mean.
* **Standard deviation** – Measures the spread or volatility of returns.

A higher standard deviation generally indicates greater variation in daily returns.

## Key Insights

This analysis helps understand:

* Daily Shopify stock price movements.
* Average stock returns.
* The spread and volatility of returns.
* Trading volume patterns.
* Unusual trading activity.
* Overall behavior of the stock during the analyzed period.

## Conclusion

This project provides a basic **exploratory analysis of Shopify stock data**.

By cleaning the data and analyzing price changes, returns, trading volume, and return statistics, we can better understand the historical behavior and volatility of the stock.
