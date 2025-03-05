
# YES BANK STOCK CLOSING PRICE PREDICTION.
# Problem Statement
Stock price prediction is a complex and highly dynamic task due to various market factors. One such major factor is 2018 fraud case, which might have significantly fluctuated stock prices. The goal is to analyze historical stock price data and develop a model that can provide reliable future price estimates.




## Columns Info:
Date: Represents the trading date.

Open: The stock’s opening price for the given date,the price at which the first trade occurred.

High: The highest stock price reached during the trading session on that date.

Low: The lowest stock price recorded during the trading session.

Close: The last traded price of the stock for that day, the target feature for our models.

## Exploratory Data Analysis
1. Studied meta-data & found number of records, null values & data types.
2. Detected outliers and skewness within the data.

## Data Cleaning & Preprocessing
1. Handled skewness & the outliers.
2. Normalized the data with the help of StandardScaler
3. Separated Features(X) and Target(Y).
4. Splitted the dataset into train set and test set.

## Model Building
Built the following models and attained 90%+ accuracy in every model:

| Model  | Accuracy |
| ------------- | ------------- |
| Linear Regression  | 99.02%  |
| Decision Tree Regressor | 86.86%  |
| XGBoost Regressor  | 96.23%  |


## Further Developments
1. Application of Ensemble Learning techniques to stack models for more robust perfomance, with application of more models like K-Neighbors Regressor and Support Vector machines.
2. Deployment of the models on cloud and development of web-application.