# MITSUI-CO-Commodity-Predictor.py
Python pipeline for MITSUI@CO commodity price predictor challenge on Kaggle

# Project Overview

This projects tackles the challenge of accurate and long-term commodity price prediction using a combination of statistical, ML, and deep learning models. The pipeline combines: 
  * __ARIMA__ (statistical baseline)
  * __XGBoost__ (ML baseline)
  * __LSTM__ (deep learning)

This project also includes technical signal engineering -- such as trend, reversal, and breakout indicators.

# **Key Features**

* Data Prepocessing
* Feature engineereing (lag features, rolling stats, temporal features)
* Technical Indicators (trend signals, reversal signals, breakout signals)
* Time series cross-validation appraoch
* Multiple layers
* Multiple model evaluation metrics
* Comprehensive visualisation of predictions

# **Dataset**

This project uses data from the MITSUI&Co Commodity Prediction Challenge available on Kaggle, to train and to test the model.

├── train.csv           # Historical commodity data
├── train_labels.csv    # Target values for training
├── target_pairs.csv    # Commodity pair information
└── test.csv           # Test data for predictions
