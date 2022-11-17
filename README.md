# Stock-Market-Prediction
Stock Market Prediction using Textual and Numerical Analysis. <br>
Youtube Link: https://youtu.be/-h-pqSgSREU

## Features
* Created a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines.
* We are using S&P BSE SENSEX as the stock to analyze and predict.
* Historical stock prices are gathered from https://finance.yahoo.com/
* Headlines and news (Textual) data is obtained from https://bit.ly/36fFPI6

## Preview
1. Closing Price of S&P BSE SENSEX.

![1](https://user-images.githubusercontent.com/96954007/201759193-50c332d7-2715-437d-a647-d627e67cc435.JPG)


2. Result of Dickey Fuller test of stationarity.

![2](https://user-images.githubusercontent.com/96954007/201759355-24d1a7c7-ea83-4e47-8610-2a7b152bcf2c.JPG)

3. Visualization of the prediction model for S&P BSE SENSEX, depicted in lime green line and yellow represents the actual stock price in that given period of time.

![3](https://user-images.githubusercontent.com/96954007/201759590-a1d1171d-2ac1-4a2c-af2f-55b7355fab5e.JPG)

4. Performance comparison of different regressor models.

![4](https://user-images.githubusercontent.com/96954007/201759943-4f6ed6c2-8006-44cc-a14c-fbfa05387803.JPG)


## Implementation 
* Python in Jupyter Notebook.
* Different regressor models like Random Forests, Decision Tree, AdaBoost, LGBM, and XGBoost regressor models to determine the best performing model using root mean squared error as the testing parameter.
* Data Analysis and Visualization using  Pandas, Numpy, Matplotlib & Seaborn.
