# Predict-Stock-Price
We make an LSTM to capture the downward and upward trend of the Google stock price.
We implement a a stacked LSTM which will be super robust with high-dimensionality and several layers. We add some dropout 
regularization to avoid overfilling and use the most powerful optimizer that we have in the Keras Library. We train our LSTM model on five years of the Google stock price (2012 to 2016) and based on this training, we predict the upward or downward trend of the Google stock price on the first month of 2017.
![alt Predict Google Stock Price](https://github.com/z1shahraki/Predict-Stock-Price/blob/master/RNN_LSTM_StockPrice.png)
