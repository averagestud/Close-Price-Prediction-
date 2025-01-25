# Close-Price-Prediction-
<h3>Close Price Prediction using Convolutions and stacked LSTM</h3>
This project focuses on predicting the closing stock prices of six companies using a combination of convolutional layers and stacked Long Short-Term Memory (LSTM) networks. The dataset consists of non-stationary time-series data, and we first analyzed the trend, seasonality, and noise to identify key features. The data was split into training and testing sets, and we utilized TensorFlow to create batches with specific window sizes, ensuring the model understood the overall sentiment and dependencies of the dataset rather than memorizing the trends.

We compared the performance of stacked LSTM with the ARIMA model and found that the LSTM model outperformed ARIMA due to its ability to capture long-term dependencies in sequential data. The model architecture includes convolutional layers to filter out noise and extract key features, followed by stacked LSTM layers to capture temporal dependencies. The final dense layers summarize these dependencies, providing accurate closing price predictions.

The model was trained and evaluated on the closing prices of each company, with Company 4 being the most influential on error metrics. The complete model architecture, training procedures, and dataset preparation steps are provided in the repository.
