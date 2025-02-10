# StockPredictor

## Overview
StockPredictor is a **machine learning-based stock market forecasting tool** that predicts stock prices using historical data. It utilizes **time-series analysis** and **deep learning models** to provide real-time insights through an interactive **Streamlit** dashboard.

## Features
- **Stock Price Prediction**: Implements **LSTM-based deep learning models** to forecast future stock prices.
- **Live Data Fetching**: Uses **Yahoo Finance (yfinance)** API for real-time stock market data.
- **Interactive Dashboard**: Built with **Streamlit** for visualization and user interaction.
- **High Accuracy**: Achieves reliable performance through **feature engineering**, **data preprocessing**, and **hyperparameter tuning**.
- **Comprehensive Data Visualization**: Displays stock trends with **matplotlib** and **seaborn**.

## Tech Stack
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Deep Learning** (TensorFlow/Keras, LSTMs)
- **Streamlit** (interactive web interface)
- **Yahoo Finance API** (real-time stock data retrieval)

## Installation
```bash
# Clone the repository
git clone https://github.com/luvdtu/Stock-Market-Predictor.git
cd StockPredictor

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app3.py
```

## Usage
1. Enter the stock ticker symbol (e.g., `AAPL`, `GOOGL`).
2. Select the prediction timeframe.
3. View the **forecasted stock price**, trend analysis, and historical data visualization.

## Model Accuracy
The trained model was evaluated using key performance metrics:

- **Mean Squared Error (MSE):** 0.0562
- **Root Mean Squared Error (RMSE):** 0.2371
- **Mean Absolute Error (MAE):** 0.2008

These metrics indicate a relatively good prediction performance for stock price forecasting.

## Future Enhancements
- Implement **GRUs** for further accuracy improvements.
- Add **sentiment analysis** from financial news for better predictions.
- Enhance **UI/UX** with advanced charting libraries.

## License
This project is licensed under the MIT License.

