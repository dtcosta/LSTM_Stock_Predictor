# LSTM Stock Predictor using Deep Learning 

![deepearn.jpg](deaplearn.jpg)
* https://unsplash.com/photos/Wpnoqo2plFA?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink *

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

Use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

## Steps Taken:

1. [Prepare the data for training and testing](#prepare-the-data-for-training-and-testing)
2. [Build and train custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
3. [Evaluate the performance of each model](#evaluate-the-performance-of-each-model)


## Conclusion:

> What were the results?
|Window Size|FNG Loss|Closing Loss|
|-----------|--------|------------|
|1          |0.1117  |0.0335      |
|5          |0.1211  |0.069       |
|7          |0.123   |0.0805      |
|10         |0.1219  |0.0885      |


> Which model has a lower loss?
LSTM Stock Predictor Using Closing Prices

> Which model tracks the actual values better over time?
LSTM Stock Predictor Using Closing Prices

> Which window size works best for the model?
LSTM Stock Predictor Using Closing Prices with Window Size 1 