### Multi-Horizon Financial Forecasting with Ensemble and Meta-Learning Models

This project implements a multi-asset, multi-horizon forecasting framework for financial instruments including stocks, ETFs, and cryptocurrencies. Using historical price and volume data, it constructs a rich set of features — including returns, moving averages, volatility, momentum, and RSI-based indicators. These indicators are used to train multiple standalone models such as Ridge Regression, Random Forest, XGBoost, and Support Vector Regression.

Predictions obtained from standalone models are combined into meta-features and these newly created features are fed into meta-learning architechtures (Ridge, XGBoost, and LSTM) to improve forecasting performance. These architectures are further tested using walk-forward validation which allows for rigorous and realistic evaluation of predictions. To obtain this, we utilized different horizons (1, 5, 15, 30, and 50 days) and prepared visualizations. Comprehensive evaluation metrics and visualizations are utilized to compare standalone models and meta-learners, giving insight into both accuracy and different financial behaviors such as non-linear and temporal.

This repository serves as a template for building robust, ensemble-based, multi-horizon financial prediction systems with Python.
