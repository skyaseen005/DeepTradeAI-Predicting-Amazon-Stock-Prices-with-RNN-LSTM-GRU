**Stock Price Prediction using RNN, LSTM, and GRU**

This project demonstrates how to predict the next-day closing price of a stock (AMZN by default) using deep learning models — Simple RNN, LSTM, and GRU.
It downloads stock data via Yahoo Finance, trains three models, evaluates their performance, and compares them using error metrics (MSE, RMSE, MAE).

🚀 Features

Fetches real stock data using yfinance

Scales and sequences data for time series forecasting

Trains and evaluates three recurrent neural network models:

**SimpleRNN**

**LSTM**

**GRU**

Compares models using key metrics (MSE, RMSE, MAE)

Predicts next-day closing price

Visualizes model predictions vs actual prices

Identifies and prints the best performing model

Technologies Used

Python 3.10+

TensorFlow / Keras

Pandas, NumPy

Matplotlib

Scikit-learn

yfinance


Clone this repository

git clone https://github.com/skyaseen005/DeepTradeAI-Predicting-Amazon-Stock-Prices-with-RNN-LSTM-GRU.git
cd stockprice


Install dependencies

pip install -r requirements.txt
requirements.txt:

numpy
pandas
yfinance
matplotlib
scikit-learn
tensorflow


Run the project

python stock_prediction_rnn_lstm_gru.py

📊 Model Comparison Metrics
  Model        MSE      RMSE       MAE
0   RNN  30.174809  5.493160  4.179153
1  LSTM  24.118737  4.911083  3.979248
2   GRU  17.835310  4.223187  2.989397


Best Model Based on RMSE: GRU
Predicted Next Day Closing Price for AMZN using Best Model (GRU): $215.25

 Summary of All Model Predictions:
RNN: $218.28
LSTM: $214.55
GRU: $215.25

Insights

RNN: Fast but struggles with long-term dependencies.

LSTM: Best for handling sequential patterns in stock data.

GRU: Almost as good as LSTM, but lighter and faster.

Future Enhancements

Add multi-day forecasting

Integrate technical indicators (SMA, EMA, RSI)

Deploy using Streamlit or Flask

Implement hyperparameter tuning for optimal performance

👨‍💻 Author

Yaseen
📧 Feel free to contribute, fork, or open issues to improve this project.

🪪 License

This project is licensed under the MIT License – free to use, modify, and distribute.
