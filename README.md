# Forecasting Financial Markets: Predictive Modeling Using S&P 500 Data  
The Erdős Institute Data Science Bootcamp Fall 2023  
By Guess-timate Gang
  (Hitesh Gakhar, Michail Paparizos, Kriti Sehgal, Limin Wang)  
Group Mentor: Soheyl Anbouhi

## Project Description
This project aims to provide accurate and reliable predictions of S&P 500 index prices, aiding investors, financial analysts, and policymakers in making informed decisions. 

## Data Collection
The dataset we consider is the S&P index closing prices over the last 10 years.  
 https://www.nasdaq.com/market-activity/index/spx/historical?page=254&rows_per_page=10&timeline=y10

## Model Selection
ARIMA, double exponential smoothing, decision trees, k-nearest neighbors, support vector machines, and random forests. 

## Evaluation Metrics
Regression Tasks:Root Mean Square Error (RMSE), Max Absolute Error Percentage (Max AEP), and Mean Absolute Error Percentage (Mean AEP), 
Classification Tasks: Precision, Recall, Accuracy, F1 score

## Model Evaluation
The best-performing model was Gradient Boost. For optimal parameters, the RMSE of the forecast and the test data is 31.34 (scale ~4400) and the MAEP is ~2.02%.

## Future Work
We could take, like further exploration of ensemble methods, perhaps by borrowing tools from applied topology or network science, and the development of a pipeline that executes a large variety of methods to pick the best strategy for any given financial time series.
