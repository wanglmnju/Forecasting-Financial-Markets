# Forecasting Financial Markets: Predictive Modeling Using S&P 500 Data  
The Erdős Institute Data Science Bootcamp Fall 2023  
By Guess-timate Gang
  (Limin Wang, Hitesh Gakhar, Michail Paparizos, Kriti Sehgal)  
Group Mentor: Soheyl Anbouhi

## Project Description
This project aims to provide accurate and reliable predictions of S&P 500 index prices, aiding investors, financial analysts, and policymakers in making informed decisions. 

## Data Collection
The dataset we consider is the S&P index closing prices over the last 10 years.  
 https://www.nasdaq.com/market-activity/index/spx/historical?page=254&rows_per_page=10&timeline=y10

## Model Selection
A large number of models were tried, including ARIMA, double exponential smoothing, decision trees, Gradient Boosting, k-nearest neighbors, support vector machines, and random forests. 

## Evaluation Metrics
Regression Tasks:Root Mean Square Error (RMSE), Max Absolute Error Percentage (Max AEP), and Mean Absolute Error Percentage (Mean AEP), 
Classification Tasks: Precision, Recall, Accuracy, F1 score

## Model Evaluation
The best-performing model was Gradient Boosting Regressor. For optimal parameters, the RMSE of the forecast and the test data is 31.34 (scale ~4400) and the MAEP is ~2.02%. The latter means for these "optimal parameters", the percentage error was never more than 2.02%. By optimizing for MAEP, we could get it down to 1.67%, however at a loss of optimality in RMSE (which went up to ~33.5).
