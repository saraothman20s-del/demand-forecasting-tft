# Demand Forecasting using Temporal Fusion Transformer (TFT)

## Project Overview

This project focuses on predicting future product demand using the Temporal Fusion Transformer (TFT), a deep learning model designed for multi-horizon time-series forecasting.

The goal is to predict future demand from historical sales data and relevant time-based and business features to support better inventory planning.

## Objectives

* Analyze historical sales data
* Perform Exploratory Data Analysis (EDA)
* Engineer meaningful time-series features
* Prepare the data for time-series forecasting
* Train a Temporal Fusion Transformer (TFT) model
* Generate future demand forecasts
* Evaluate model performance

## Exploratory Data Analysis

The analysis focuses on understanding:

* Overall sales trends
* Monthly sales patterns
* Sales distribution
* Differences between products and stores
* Outliers and unusual sales behavior

## Feature Engineering

The following features were created to help the model learn temporal patterns:

* Day of week
* Month
* Year
* Weekend indicator
* Holiday indicator
* Time index
* Selling price
* Event-related features

## Model

The project uses the **Temporal Fusion Transformer (TFT)** for multi-horizon time-series forecasting.

TFT combines temporal sequence processing, attention mechanisms, and variable selection to learn patterns from historical and known future information.

## Evaluation

The model was evaluated using:

* MAE — Mean Absolute Error
* RMSE — Root Mean Squared Error
* SMAPE — Symmetric Mean Absolute Percentage Error

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* PyTorch
* PyTorch Forecasting
* Lightning
* Matplotlib

## Project Structure

```text
demand-forecasting-tft/
│
├── Demand_Forecasting_TFT.ipynb
├── README.md
└── requirements.txt
```

## Future Improvements

* Hyperparameter tuning
* Comparison with other forecasting models
* Adding more business-related features
* Improving long-horizon forecasting
* Deploying the model as an API or dashboard

## Author

**Sara Othman**

Information Systems Student
Al Shorouk Academy
