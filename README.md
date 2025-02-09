# Stock-Prediction
This project uses machine learning models, including Decision Tree Regressor and Linear Regression, to predict Netflix's future stock prices based on historical data. The goal is to demonstrate how to preprocess stock data, train predictive models, and visualize the results to help forecast stock price trends.


**Overview**
The goal of this project is to predict the future closing price of Netflix stock using historical stock data. We use machine learning models, such as Decision Tree Regressor and Linear Regression, to predict the stock price for the next 25 days. This project demonstrates how to:
- Visualize stock price data
- Prepare data for machine learning
- Train models and make predictions
- Evaluate the models visually


**Prerequisites**
Ensure that you have the following Python libraries installed:
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`
- `google.colab` (if using Google Colab)

**Data**
Date: The date of the stock price data.
Open: Opening stock price of the day.
High: Highest stock price of the day.
Low: Lowest stock price of the day.
Close: Closing stock price of the day.
Volume: Number of stocks traded.

**Models**
This project uses two machine learning models to predict stock prices:

Decision Tree Regressor: A tree-based model that splits the data at different decision points to make predictions.
Linear Regression: A statistical model that predicts stock prices based on the relationship between the target and independent variables.

**Model Evaluation:**
The performance of the models is evaluated using visual comparison, where the predicted stock prices are plotted against the actual stock prices.

**Results**
The results of the predictions are visualized through a graph comparing the original stock prices with the predicted prices from both models. You will see two separate plots:
- One for the Decision Tree predictions
- One for the Linear Regression predictions
This allows us to compare how well each model predicts future stock prices.
