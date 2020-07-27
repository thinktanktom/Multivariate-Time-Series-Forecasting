# MultiVariate Time Series Forecasting

This repository showcases two different approaches to time series forecasting. The second method involving a lot more fine-tuning and calculation.

# Problem 

The csv data and word problem can be found in the data directory.

# Working

The following steps were taken to create the model:

- created a DataFrame and deleted unwanted columns.
- Utilised granger causality tests to check relationships between different variables.
- split data into training and test set.
- Utilised Augmented Dickey-Fuller Test to check if data is stationary.
- Fitted a VAR(Vector AutoRegression) Model with the training data.
- Used the model to forecast test set.