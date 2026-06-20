Stock Forecasting & Portfolio Management Using MLPs

Predicting stock trends and algorithmic capital allocation of a $1,000,000 portfolio using Multi-Layer Perceptrons (MLPs).
This project analyzes historical data of 5 major Wall Street equities, filters out market noise, and applies Machine Learning to predict future trends and make optimized investment decisions.

Features

Statistical Analysis & Data Engineering

Smoothing of daily price volatility using a 200-day Simple Moving Average (SMA).

Multicollinearity checking via Pearson Correlation Matrix to analyze unique input variables.

Data synchronization and alignment of 1,056 asynchronous trading days using Python & Pandas.

Scaling and Normalization

Min-Max Scaling (range 0 to 1) for neural network stability.

Chronological train-test split (80% Train, 20% Test) to prevent look-ahead bias.

Visualizations

Volatility vs. Smoothing line chart (Noise Reduction).

Heatmap of Pearson correlations between stocks, VIX, and S&P 500.

Bar chart of expected structural growth rates for the 10-day forecasting window.

True vs. Predicted line chart (Validation Performance).

Machine Learning

Regression: Predicting the structural trend of assets using an MLP Regressor.

Recursive Forecasting: Sequential 10-day-ahead out-of-sample prediction.

Evaluation Metrics: MAPE (error percentage) and $R^2$ Score (explanatory power).

Dataset

Data is sourced from Investing.com, covering 5 years (2021-2026).

5 equities: Apple (AAPL), Amazon (AMZN), Boeing (BA), Goldman Sachs (GS), Lockheed Martin (LMT)

2 market indicators: S&P 500 (US500) and VIX (Volatility Index)

Tools / Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

scikit-learn

How to Run

Open the notebook stock_forecasting_portfolio_mlp.ipynb in Google Colab or Jupyter.

Upload the CSV files to the same directory.

Run all cells in order to train the model, generate predictions, and export the charts.

Visualizations

Volatility vs. Smoothing (Amazon)

Pearson Correlation Matrix

Validation Performance (AAPL)

Expected Structural Growth Rate

Real-World Validation (Goldman Sachs)

Notes

This project is for portfolio purposes, showcasing practical ML applications in quantitative asset management.

The notebook is interactive when opened in Colab.
