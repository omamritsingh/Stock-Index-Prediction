# Stock-Index-Prediction

## Data
Minutely scraped S&P 500 data from the Google Finance API. The data consisted of index as well as stock prices of the S&P’s 500 constituents.



## ANN in Tensorflow
Implemented an  Artificial  Neural Network approach in Tensorflow to predict stock market prices. Artificial  Neural  networks are very effectively implemented  in forecasting stock prices, returns,and stock  modelling, and the most frequent methodology is the Back propagation algorithm. 

## Results
The final test MSE equals 0.00078 (it is very low, because the target is scaled). The mean absolute percentage error of the forecast on the test set is equal to 5.31%. the Adam learning scheme that lowers the learning rate during model training in order not to overshoot the optimization minimum. After 10 epochs,  a pretty close fit to the test data! 