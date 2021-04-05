# Tensorflow LSTM-practice

Tensorflow LSTM practice

This practice uses the LSTM method to predict a stock price. 
Use past 30 days price for reference and predict the following day price.

there are maltplot and tensorboard  visualising the result and value.

change stock by upload another csv file in your google drive

Change interval as you like.
For example, you want predication the next price based on past 30 day then set 30.

the model add tensorflow tuner that it will try to find the best variable.

Model example:

stock:tsla
day interval:60

result:

![image](https://github.com/benbenfai/LSTM-stock-price-prediction/blob/main/unknown.png)

Predict result in range around 2% to 5% error

It is not enough to get an accurate result, yet may show an upward and downward trend.

There is a example result below.

![image](https://github.com/benbenfai/LSTM-practice/blob/main/result.png)
