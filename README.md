# Store-Sales-Time-Series-Forecasting---ML-Regression-Project.
This project focuses on time series forecasting to predict store sales for Corporation Favorita, a large Ecuadorian-based grocery retailer. The goal is to build a model that accurately predicts the unit sales for thousands of items sold at different Favorita stores.

# Business Understanding
## Introduction
This project focuses on time series forecasting to predict store sales for Corporation Favorita, a large Ecuadorian-based grocery retailer. The objective is to build a model that accurately predicts the unit sales for thousands of items sold at different Favorita stores.

## Objectives
**Understand the data:** Gain insights into the store sales data, including store-specific information, product families, promotions, and sales numbers. This understanding will enable the company to make informed business decisions.

**Predict store sales:** Develop a reliable time series forecasting model that accurately predicts the unit sales for different product families at various Favorita stores. This will help the company optimize inventory management, plan promotions, and improve overall sales performance.

## Methodology
To achieve the objectives, we will follow a structured approach:

**Data Exploration:** Thoroughly explore the provided datasets to understand the available features, their distributions, and relationships. This step will provide initial insights into the store sales data and help identify any data quality issues.

**Data Preparation:** Handle missing values, perform feature engineering, and encode categorical variables as necessary. This step may involve techniques like imputation, scaling, and one-hot encoding.

**Time Series Analysis:** Analyze the temporal aspects of the data, including trends, seasonality, and potential outliers. This analysis will provide a deeper understanding of the underlying patterns in-store sales over time.

**Model Selection and Training:** Select appropriate time series forecasting models and train them using the prepared data. Consider incorporating external factors like promotions, holidays, and oil prices, if available, to enhance forecasting accuracy.

**Model Evaluation:** Evaluate the trained models using appropriate metrics, such as mean absolute error (MAE), root mean squared error (RMSE), or mean absolute percentage error (MAPE). Assess the models' performance and identify the most accurate and reliable forecasting model.

**Model Deployment and Forecasting:** Deploy the chosen model to predict store sales for future time periods, leveraging the provided test dataset. Generate forecasts for the target period and assess the model's ability to capture the sales patterns accurately.

## File Descriptions and Data Field Information
**train.csv**: The training data contains time series information, including store_nbr, family, onpromotion, and the target variable sales. It provides insights into the store, product, promotion, and sales data.

**test.csv**: The test data has the same features as the training data. The task is to predict the target sales for the dates in this file. The dates in the test data are for the 15 days following the last date in the training data.

**transaction.csv**: This file includes the date, store_nbr, and the number of transactions made on each specific date.

**stores.csv**: This file contains store metadata, including city, state, type, and cluster. The cluster column represents the grouping of similar stores.

**oil.csv**: Daily oil prices, which include values during both the train and test data timeframes. Oil prices are significant because Ecuador is an oil-dependent country, and its economy is vulnerable to shocks in oil prices.

**holidays_events.csv**: This file provides information about holidays and events, including metadata. The "transferred" column indicates if a holiday was officially transferred to another date by the government. Additional details about different holiday types are also provided.

## Additional Notes
Wages in the public sector are paid every two weeks on the 15th and the last day of the month. This information could affect supermarket sales.

An earthquake with a magnitude of 7.8 struck Ecuador on April 16, 2016. The earthquake led to relief efforts and donations, which significantly impacted supermarket sales for several weeks afterwards.

## Data Preparation
**Handling missing values:** Identify missing values in the datasets and decide on an appropriate strategy for handling them. This may involve imputing missing values or removing data points with missing values.

**Performing feature engineering:** Transform and create new variables that can potentially improve the predictive power of the models. This step may include encoding categorical variables, scaling numerical variables, or creating interaction terms.

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

## Model Development
I will select appropriate time series forecasting models.
Train the models using the prepared data and incorporate external factors if available.
Optimize the models by tuning hyperparameters and selecting the best-performing model.

## Model Evaluation
I will evaluate the trained models using appropriate metrics such as MAE, RMSE, MSE, or MAPE.
Interpret the models to understand the factors driving store sales and their relative importance.

## Project Deliverables
Exploratory Data Analysis (EDA) report.
Data preprocessing and feature engineering documentation.
Trained time series forecasting models.
Model evaluation and performance analysis.
Final project report summarizing the findings, insights, and recommendations.

## Conclusion
The Regression Project (Store Sales - Time Series Forecasting) aims to predict store sales accurately using time series forecasting techniques. By leveraging the provided datasets and following the outlined methodology, I aim to provide valuable insights to Corporation Favorita and develop a reliable forecasting model for store sales. The project will enable informed decision-making, optimize inventory management, and improve overall sales performance for the company.

The ultimate objective is to build a model that accurately predicts the unit sales for thousands of items.
