# Stock-price-prediction

# Stock Price Prediction using LSTM

This project demonstrates the use of a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data. 
The project fetches historical stock price data using the `yfinance` library, preprocesses the data, trains an LSTM model, and visualizes the results.

## Table of Contents
- [Introduction](#stock-price-prediction-using-lstm)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Project Structure](#project-structure)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/anukeerthi63803/Stock-price-prediction.git
   cd Stock-price-prediction
   
   Install the required dependencies using 'pip':
     pip install -r requirements.txt

## Usage

Replace 'AAPL' with the desired stock symbol in the 'stock_symbol' variable in 'stock_price_prediction.ipynb file'.
Set the appropriate 'start_date' and 'end_date' in the same file to fetch the desired historical data.
Run the Jupyter Notebook 'stock_price_prediction.ipynb' to execute the project.
The notebook will fetch historical stock price data using 'yfinance', preprocess the data, train an LSTM model, and visualize the results.

## Requirements
Python 3.x
Jupyter Notebook
yfinance library
numpy
pandas
matplotlib
scikit-learn
keras
Install the required dependencies using the provided 'requirements.txt' file:
  pip install -r requirements.txt


## Project Structure
The project contains the following files:

'stock_price_prediction.ipynb': Jupyter Notebook containing the code for data fetching, preprocessing, LSTM model creation, training, prediction, and visualization.
'requirements.txt': List of required Python packages for this project.
