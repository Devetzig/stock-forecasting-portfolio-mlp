---

## Stock Forecasting & Portfolio Management Using MLPs

Predicting stock trends and algorithmic capital allocation of a $1,000,000 portfolio using Multi-Layer Perceptrons (MLPs).
This project analyzes historical data of 5 major Wall Street equities, filters out market noise, and applies Machine Learning to predict future trends and make optimized investment decisions.


## Features
1. **Statistical Analysis & Data Engineering**
   - Smoothing of daily price volatility using a 200-day Simple Moving Average (SMA).
   - Multicollinearity checking via Pearson Correlation Matrix to analyze unique input variables.
   - Data synchronization and alignment of 1,056 asynchronous trading days using Python & Pandas.

2. **Scaling and Normalization**
   - Min-Max Scaling (range 0 to 1) for neural network stability.
   - Chronological train-test split (80% Train, 20% Test) to prevent look-ahead bias.

3. **Visualizations**
   - Volatility vs. Smoothing line chart (Noise Reduction).
   - Heatmap of Pearson correlations between stocks, VIX, and S&P 500.
   - Bar chart of expected structural growth rates for the 10-day forecasting window.
   - True vs. Predicted line chart (Validation Performance).

4. **Machine Learning**
   - Regression: Predicting the structural trend of assets using an MLP Regressor.
   - Recursive Forecasting: Sequential 10-day-ahead out-of-sample prediction.
   - Evaluation Metrics: MAPE (error percentage) and $R^2$ Score (explanatory power).


## Dataset
  Data is sourced from Investing.com, covering 5 years (2021-2026).
   - 5 equities: Apple (AAPL), Amazon (AMZN), Boeing (BA), Goldman Sachs (GS), Lockheed Martin (LMT)
   - 2 market indicators: S&P 500 (US500) and VIX (Volatility Index)


## Tools / Libraries
   - Python
   - Pandas
   - NumPy
   - Matplotlib
   - Seaborn
   - scikit-learn


## How to Run
1. Open the notebook stock_forecasting_portfolio_mlp.ipynb in Google Colab or Jupyter.
2. Upload the CSV files to the same directory.
3. Run all cells in order to train the model, generate predictions, and export the charts.


## Visualizations
   - Volatility vs. Smoothing (Amazon)
   
   <img width="4200" height="1800" alt="volatility_vs_smoothing_amzn" src="https://github.com/user-attachments/assets/1b9a1f5b-41e9-4a0d-929f-b08f49125d05" />

   - Pearson Correlation Matrix

   <img width="3000" height="2400" alt="correlation_matrix" src="https://github.com/user-attachments/assets/3b17a4ee-2f6f-4680-be25-7215507f5009" />

   - Validation Performance (AAPL)

   <img width="3000" height="1500" alt="validation_performance" src="https://github.com/user-attachments/assets/bdfbfe55-ed10-4749-93ad-68d7bdf6a179" />
   
   - Expected Structural Growth Rate

   <img width="2700" height="1500" alt="expected_growth_rates" src="https://github.com/user-attachments/assets/42cd9ad9-2789-468b-9890-70fc42681204" />


---

**Notes**
This is for portfolio purposes, made with real data, during a Machine Learning course I took from the University of Crete.
This project is showcasing practical ML applications in quantitative asset management.
The notebook is interactive when opened in Colab.
