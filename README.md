# Time-series-Dockship-Learn-ML-2021-Grand-Challenge-Stock
NOTE : 1. First attempt at Time series, so there could be some mistakes with the codes or concepts (please refer to other sources as well before using this as a refrence)
2. The RSME value for the submission made using this code was very high and better values were achieved using regression so this is just for refrence (for a time series based project)
3. Refer to playlist for time series : https://www.youtube.com/playlist?list=PLqYFiz7NM_SMC4ZgXplbreXlRY4Jf4zBP
4. After differencing using cumsum() fn on predicted values (Not in videos)
5. For differencing use .diff() and dropna() after that since one value will become NaN (not in video) - Use differencing for converting from stationary to non stationary

Competition problem statement :

The aim of this task is to predict the stock market prices for 5 stocks.

The year 2020 has been an outlier year for finance analysts. Most of the past models have failed to give out great results on the 2020 financial data creating a need for more robust models to handle such outliers. Hence with this challenge, we wish to test your analytical modelling skills not for 1 stock but 5 to see if you have what it takes to create a model that can give predictions for the outlier 2020 year. All the best for the challenge!

The aim of this challenge is to predict the closing prices of 5 stocks using the given data.

The dataset consists of 3 files:

new_train.csv (for training)
new_test.csv (for test)
new_sample_submission.csv (for sample submission format)
This data should be used to train the model, no additional data is allowed to be used for the training process.
