
# Stock Price Analysis Dashboard

This project is an interactive web application for analyzing stock data, built with Python using the Dash framework. The app combines machine learning, data preprocessing, and data visualization to provide insights into stock prices and market trends.

## Environment Variables

To run the app locally, ensure you have the following installed:

Python 3.7+

Required Python libraries:

Dash

Pandas

Plotly

Numpy

Scikit-learn

TensorFlow

Stock data CSV files (e.g., NSE-Tata-Global-Beverages-Limited.csv, stock_data.csv).

Pre-trained LSTM model (saved_lstm_model.h5).

## Features

LSTM-Based Stock Price Prediction:

Predicts stock closing prices using an LSTM (Long Short-Term Memory) model.

Visualizes actual vs. predicted closing prices for NSE-TATAGLOBAL.

Interactive Stock Data Analysis:

Visualizes high/low prices and transaction volumes for stocks like Tesla, Apple, Facebook, and Microsoft.

Allows users to select multiple stocks for customized analysis.

Dynamic Visualizations:

Scatter plots for actual and predicted stock prices.

Line graphs for high/low prices and market volume.

Interactive date range selectors and sliders for detailed exploration.

User-Friendly Dashboard:

Intuitive tabs and dropdowns for seamless navigation.

Mobile-friendly design and easy-to-use interface.

## Installation

Clone the repository.

Install the required libraries using pip:

bash
pip install dash pandas plotly numpy scikit-learn tensorflow

Place the CSV files and 
the saved LSTM model file in the appropriate directories.
    
## Run Locally

Clone the project

Navigate to the project directory.

Run the app using the following command:

bash
python app.py
Open a web browser and visit http://127.0.0.1:8050 to access the dashboard.


## Notes

Notes
Ensure that the file paths for the CSV files and LSTM model are correctly specified in the script.

The app is configured for debugging mode (debug=True).