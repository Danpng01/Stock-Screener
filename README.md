# Stock Analysis and Visualization

## Overview
To enhance my fundamental analysis of company business reports, I recognized the limitations of manually processing vast amounts of data and performing complex calculations. In response, I developed this Python notebook to streamline and expedite the analysis and comparison of stocks.

The code within the notebook conducts an in-depth examination of a specified list of stocks, encompassing intrinsic value calculations, the presentation of crucial financial ratios, and the visualization of stock prices, Net Income, Revenue, and Free Cash Flow over time. Leveraging financial data obtained from Yahoo Finance, the script employs the mplfinance and seaborn libraries to generate insightful graphs.

Through this automated approach, I aim to leverage the capabilities of data analysis in Python to gain deeper insights into the financial health and performance of the selected stocks. This not only saves time but also allows for more efficient decision-making in my investment strategy.

## Requirements
Make sure to install the required libraries before running the script:

```python
pip install yfinance
pip install mplfinance
```
## Key Components

### Initialization
The script initializes by importing necessary libraries, setting up the list of stocks, and creating Ticker objects for each stock using the yfinance library.

### Stock Price Visualization
The script generates candlestick charts for each stock, displaying the stock price history with 50 and 200 Simple Moving Averages (SMA) plotted on them.

### Financial Ratios
The script calculates and presents key financial ratios for each stock. The metrics include Market Cap, Debt to Equity ratio, Quick Ratio, Return on Assets, Return on Equity, Gross Margins, Operating Margins, Profit Margins, Dividend Yield, and Beta.

### Comparison Charts
The script creates comparison charts for Net Income, Total Revenue, and Free Cash Flow over time for the selected stocks.

### Correlation Matrix
The script generates a correlation matrix for the closing prices of the stocks, providing insights into the correlation between their price movements.

## Usage
Make sure to have Python and Jupyterlab installed on your system.
Install the required libraries using the provided pip install commands.
Copy the script into your Python environment.
Adjust the stock_list variable to include the desired stock symbols.
Run the script.
