# Store-Sales-Time-Series-Forecasting---ML-Regression-Project
This project focuses on time series forecasting to predict store sales for Corporation Favorita, a large Ecuadorian-based grocery retailer. The goal is to build a model that accurately predicts the unit sales for thousands of items sold at different Favorita stores.

## Project Description
The project involves analyzing the training data, which includes dates, store information, product details, promotion status, and sales numbers. The objective is to build a model that can accurately forecast the sales for the test data, which consists of the same features as the training data.

## File Descriptions and Data Field Information
**train.csv**: The training data contains time series information, including store_nbr, family, onpromotion, and the target variable sales. It provides insights into the store, product, promotion, and sales data.

**test.csv**: The test data has the same features as the training data. The task is to predict the target sales for the dates in this file. The dates in the test data are for the 15 days following the last date in the training data.

**transaction.csv**: This file includes the date, store_nbr, and the number of transactions made on each specific date.

**stores.csv**: This file contains store metadata, including city, state, type, and cluster. The cluster column represents the grouping of similar stores.

**oil.csv**: Daily oil prices, which include values during both the train and test data timeframes. Oil prices are significant because Ecuador is an oil-dependent country, and its economy is vulnerable to shocks in oil prices.

**holidays_events.csv**: This file provides information about holidays and events, including metadata. The "transferred" column indicates if a holiday was officially transferred to another date by the government. Additional details about different holiday types are also provided.

## Additional Notes
Wages in the public sector are paid every two weeks on the 15th and the last day of the month. This information could affect supermarket sales.

An earthquake with a magnitude of 7.8 struck Ecuador on April 16, 2016. The earthquake led to relief efforts and donations, which significantly impacted supermarket sales for several weeks afterward.

## Data Preparation
Before building the model, data preparation steps will be performed to ensure the data is ready for analysis and modeling.

## Hypothesis & Questions
To guide the analysis and explore the data, the following questions will be answered:

### Questions
1. Is the train dataset complete, including all the required dates?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake have an impact on sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices, and holidays?
6. What analysis can be derived from the date and its extractable features?
7. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
   
The task is to build a model that can accurately predict the unit sales for thousands of items based on the provided data.
