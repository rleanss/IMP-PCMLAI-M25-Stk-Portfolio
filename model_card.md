Model Card

Model Description

Input:

open: Opening price of a stock on a given day
high: Highest price reached by a stock on a given day
low: Lowest price reached by a stock on a given day
adjclose: Closing price of a stock after adjusting for actions such as dividends and stock splits, which can affect the price of a stock over time
Output:

close: Closing price of a stock on a given day
Model Architecture:

The model employs Linear Regression, a statistical method that estimates the relationship between the dependent variable (close) and independent variables (open, high, low, and adjclose). The model learns the coefficients of a linear equation that best fits the data.

Performance

The Coefficient of Determination (R²) evaluates the model's performance, measuring how well it fits the data (ranging from 0 to 1). With an R² value of 0.9462, the model exhibits a very strong fit to the data.

Limitations

This model lacks consideration for external factors impacting stock prices, such as news, economic events, or political developments. It assumes a linear relationship between input variables and the output variable (close). In reality, the relationship may not be perfectly linear, and other factors may influence stock prices.

Future Work

Future model iterations could enhance performance by incorporating additional features, such as:

News sentiment data
Economic indicators
Financial reports
Additionally, employing more advanced machine learning algorithms could capture complex relationships between input and output variables.

Conclusion

This model provides a simple and effective means to predict stock prices based on historical data. However, users should be mindful of its limitations and consider other factors that may impact stock prices.