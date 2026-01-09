# Short-Term Stock Price Prediction

## Task Objective
Predict the next day’s closing price of a stock using historical Open, High, Low, and Volume data.

## Dataset Used
- Historical stock data from Yahoo Finance (using yfinance)
- Example stock: Apple (AAPL)
- Features: Open, High, Low, Volume
- Target: Next day’s Close price

## Models Applied
- **Linear Regression**
- **Random Forest Regressor**

## Key Results and Findings
- Linear Regression achieved MSE ≈ 6.89 and R² ≈ 0.98, indicating strong linear correlation between features and next-day close price.
- Random Forest had higher MSE ≈ 72.18 and R² ≈ 0.81, performing worse due to noisy short-term stock data.
- Simpler linear models can outperform complex ones in short-term stock prediction with strongly correlated features.
