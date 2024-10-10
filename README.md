# Quant-Analysis-MF
Quantitative Analysis in the stock market is a financial methodology that utilizes mathematical and statistical techniques to analyze stocks (AAPL, GOOG, MSFT, NFLX) and financial markets

# Explanation of Dataset
The Dataset stocks.csv is uploaded in the repository
The dataset contains the following columns for stock market data:

* Ticker: The stock ticker symbol.
* Date: The trading date.
* Open: The opening price of the stock for the day.
* High: The highest price of the stock during the day.
* Low: The lowest price of the stock during the day.
* Close: The closing price of the stock for the day.
* Adj Close: The adjusted closing price, which accounts for all corporate actions such as dividends, stock splits, etc.
* Volume: The number of shares traded during the day.

# Descriptive Statistics
Descriptive Statistics will provide summary statistics for each stock in the dataset. We’ll look at measures such as mean, median, standard deviation, and more for the Close prices

https://github.com/user-attachments/assets/3f31c1a6-7944-4885-8ade-f2abbed454b7

# Time Series Analysis
Trends and patterns over time, especially for closing prices.

https://github.com/user-attachments/assets/2af69165-0040-4e51-b408-9a49259b3e3d

* Trend: Each stock shows its unique trend over time. For instance, AAPL and MSFT exhibit a general upward trend in this period.
* Volatility: There is noticeable volatility in the stock prices. For example, NFLX shows more pronounced fluctuations compared to others.
* Comparative Performance: When comparing the stocks, MSFT and NFLX generally trade at higher price levels than AAPL and GOOG in this dataset

# Volatility Analysis
Calculate and compare the volatility (standard deviation) of the closing prices for each stock. It will give us an insight into how much the stock prices fluctuated over the period:

https://github.com/user-attachments/assets/be31a0fd-0236-464b-a2cb-a3accd4e77bd

* NFLX: Highest volatility with a standard deviation of approximately 18.55.
* MSFT: Next highest, with a standard deviation of around 17.68.
* AAPL: Lower volatility compared to NFLX and MSFT, with a standard deviation of about 7.36.
* GOOG: The least volatile in this set, with a standard deviation of approximately 6.28.
It indicates that NFLX and MSFT stocks were more prone to price fluctuations during this period compared to AAPL and GOOG.

# Correlation Analysis
Understand how the stock prices of these companies are related to each other

https://github.com/user-attachments/assets/9d0a8c7c-5102-41e0-803b-fcab3b1015e5

Here’s what the correlation coefficients suggest:

* Values close to +1 indicate a strong positive correlation, meaning that as one stock’s price increases, the other tends to increase as well.
* Values close to -1 indicate a strong negative correlation, where one stock’s price increase corresponds to a decrease in the other.
* Values around 0 indicate a lack of correlation.

From the heatmap, we can observe that there are varying degrees of positive correlations between the stock prices, with some pairs showing stronger correlations than others. For instance, AAPL and MSFT seem to have a relatively higher positive correlation.

# Comparative Analysis
We’ll compare the performance of different stocks based on their returns over the period. We’ll calculate the percentage change in closing prices from the start to the end of the period for each stock.

<img width="621" alt="Screenshot 2024-10-10 124134" src="https://github.com/user-attachments/assets/f772749f-bdb1-4407-bf89-97ee26c5ad8b">

The bar chart and the accompanying data show the percentage change in the closing prices of the stocks from the start to the end of the observed period:

* MSFT: The highest positive change of approximately 16.10%.
* AAPL: Exhibited a positive change of approximately 12.23%. It indicates a solid performance, though slightly lower than MSFT’s.
* GOOG: Showed a slight negative change of about -1.69%. It indicates a minor decline in its stock price over the observed period.
* NFLX: Experienced the most significant negative change, at approximately -11.07%. It suggests a notable decrease in its stock price during the period.

# Daily Risk Vs Return Analysis
To perform a Risk vs. Return Analysis, we will calculate the average daily return and the standard deviation of daily returns for each stock. The standard deviation will serve as a proxy for risk, while the average daily return represents the expected return.

We will then plot these values to visually assess the risk-return profile of each stock. Stocks with higher average returns and lower risk (standard deviation) are generally more desirable, but investment decisions often depend on the investor’s risk tolerance:


https://github.com/user-attachments/assets/58a1814c-00de-4682-bf1f-15d9fbe4f4f4

* AAPL shows the lowest risk combined with a positive average daily return, suggesting a more stable investment with consistent returns.
* GOOG has higher volatility than AAPL and, on average, a slightly negative daily return, indicating a riskier and less rewarding investment during this period.
* MSFT shows moderate risk with the highest average daily return, suggesting a potentially more rewarding investment, although with higher volatility compared to AAPL.
* NFLX exhibits the highest risk and a negative average daily return, indicating it was the most volatile and least rewarding investment among these stocks over the analyzed period.














