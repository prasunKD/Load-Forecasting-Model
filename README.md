# Load Forecasting Model

This repository contains a Python-based model for forecasting electricity load in different regions of India.

## Package Requirements

The following packages are required to run this code:

- pandas==1.5.3
- prophet==1.1.4
- seaborn==0.12.2
- matplotlib==3.7.1
- statsmodels==0.13.5
- xgboost==1.7.6
- keras==2.12.0
- scikit-learn==1.2.2
- tensorflow==2.12.0
- numpy==1.23.5

## Run Instructions

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt 
   ```
2. **Prepare data:**
   - Make sure you have the `Load Forecasting Data - 2017-22.csv` file in the same directory as the script.
3. **Execute the code:**
   - Run the Python script (e.g., using a Python interpreter or Jupyter Notebook).

## Code Description

The code implements several Machine Learning (ML) models and a Deep Learning (LSTM) model for time series forecasting. It processes the electricity load data, extracts features, and trains different models to predict future loads.


## Data
- The data source used in the model is `Load Forecasting Data - 2017-22.csv`. 
