## Explanation

This project focuses on developing a stock price prediction model for a specific set of stocks, aiming to construct portfolios or assess trading strategies across different sectors, such as big tech or finance companies. The initial model utilizes historical stock prices as the primary input variable, establishing a baseline performance for future iterations that incorporate additional data sources like news and financial reports.

**Data**

The dataset consists of historical stock price data for the companies that make up the selected sector, encompassing a period of time determined by the user's input. This data will be used to train and evaluate the stock price prediction model.

**Model**

The Linear Regression model is employed, seeking to establish a mathematical relationship between the independent variables (historical stock prices) and the dependent variable (future stock prices). This model is chosen for its interpretability and its ability to handle linear relationships between variables.

**Hyperparameter Optimization**

The Grid Search technique is utilized to select the optimum hyperparameters for the Linear Regression model. This technique efficiently explores the parameter space to identify the combination that yields the best model performance.

