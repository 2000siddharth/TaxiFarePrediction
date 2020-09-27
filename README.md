# TaxiFarePrediction
Prediction fares for taxi rides in NYC. The dataset can be found at [Kaggle](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data)

The dataset was originally made to be run on cloud platforms, thus the data is huge, but I have only used a subset of the entire data for my predictions (1,000,000 rows)
I have used two approaches till now for making the predictions:
1. Linear Regression
2. Random Forests

There are 3 files in the repo:
1. EDA
2. LinearReg
3. RandForests

Features provided in the original dataset:
| Feature | Description |
| ----------- | ----------- |
| Timestamp | Records the date and time of the ride |
| fare_amount | The fare for the given ride |
| pickupLatitude | The pickup latitude coordinate |
| pickupLongitude | The pickup longitude coordinate |
| dropoffLatitude | The dropoff latitude coordinate |
| dropoffLongitude | The dropoff longitude coordinate |

The results for the above two models are:
| Algorithm | RMSE | MAE | R2 Score |
| ----------- | ----------- | -------- | ----- |
| Linear Regression | 5.63 | 2.66 | 65.87 |
| Random Forests | 4.22 | 2.08 | 82.60 |
