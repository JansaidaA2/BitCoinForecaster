# BitCoinForecaster

# Bitcoin Price Prediction Project

## Overview

This project aims to predict Bitcoin prices using historical data and machine learning techniques. It leverages the yfinance library to gather cryptocurrency data for Bitcoin (BTC), Ethereum (ETH), Tether (USDT), and Binance Coin (BNB) over the past 5 years. The project performs exploratory data analysis (EDA) and applies a Random Forest Regressor model for price prediction.

## Features

*   *Data Collection:* Utilizes yfinance to fetch historical cryptocurrency data.
*   *Data Preprocessing:* Cleans and prepares the data for analysis, including handling missing values and feature engineering.
*   *Exploratory Data Analysis (EDA):*
    *   Visualizes closing prices and trading volumes.
    *   Performs correlation analysis to understand relationships between cryptocurrencies.
    *   Examines the distribution of closing prices.
*   *Machine Learning Model:*
    *   Employs a Random Forest Regressor to predict Bitcoin prices.
    *   Splits data into training and testing sets.
    *   Uses SelectKBest for feature selection.
*   *Libraries Used:*
    *   yfinance
    *   pandas
    *   numpy
    *   matplotlib
    *   seaborn
    *   scikit-learn
    

## Data

The project uses historical data for the following cryptocurrencies:

*   Bitcoin (BTC-USD)
*   Ethereum (ETH-USD)
*   Tether (USDT-USD)
*   Binance Coin (BNB-USD)

Data is sourced from Yahoo Finance using the yfinance library.

## Model

The project uses a Random Forest Regressor model from scikit-learn. Feature selection is performed using SelectKBest to identify the most relevant features for prediction.

## Results

The project provides insights into the factors influencing Bitcoin prices and demonstrates the application of machine learning for financial forecasting.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or suggest improvements.

