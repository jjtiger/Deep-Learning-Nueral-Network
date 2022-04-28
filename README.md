![](bestdeeplearning.jpg)

# Deep-Learning-Nueral-Network

![](deeplearningml.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. 

This project uses deep learning models applying both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this project, I will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

Prepared the data for training and testing
Built and train custom LSTM RNNs
Evaluated the performance of each model

Files
Closing Prices Starter Notebook
FNG Starter Notebook

Prepared the data for training and testing
Used the starter code as a guide to create a Jupyter Notebook for each RNN. 

For the Fear and Greed model, I applied the FNG values to try and predict the closing price.

For the closing price model, I applied previous closing prices to try and predict the next closing price.

Each model used 70% of the data for training and 30% of the data for testing.
Applied a MinMaxScaler to the X and y values to scale the data for the model.
Finally, reshaped the X_train and X_test values to fit the model's requirement of samples, time steps, and features. (example: X_train = X_train.reshape((X_train.shape[0], X_train.shape[1], 1)))

Built and trained custom LSTM RNNs
In each Jupyter Notebook, created the same custom LSTM RNN architecture. In one notebook,  the data is fit using the FNG values. In the second notebook,  the data is fit using only closing prices.

Used the same parameters and training steps for each model. This was necessary to compare each model accurately.

Evaluated the performance of each model
Finally, used the testing data to evaluate each model and compared the performance.



Resources
Keras Sequential Model Guide
Illustrated Guide to LSTMs
Stanford's RNN Cheatsheet



