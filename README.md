Description:
This project is a comprehensive quantitative stock analysis toolkit, designed to provide insights into creating a trading system through combination of technical analysis and machine learning algorithms. It allows users to assess historical stock price data, generate buy/sell signals, backtest prediction model for accuracy and test portfolio returns. The end result is a robust algorithmic system for predicting future stock movements.

Key Features:

Technical Analysis:
Calculates and analyzes technical indicators (SMA, RSI, Bollinger Bands) to identify potential buying and selling opportunities.
Implements Golden Cross and Death Cross strategies for trend identification.
Visualizes buy/sell signals on historical stock price charts.

Machine Learning Integration:
Utilizes PyCaret to identify the best regression model for predicting the next day's closing price.
Backtests the machine learning model and analyzes residuals for model performance.

Modular and Scalable:
Designed to analyze multiple stocks by providing a modular structure.
Expands easily to accommodate additional technical indicators, fundamental factors, and machine learning models.

Packages/ibraries Used:
Python, Pandas, NumPy, Matplotlib, Statsmodels, yfinance, Scikit-learn, PyCaret

How to Use:
Clone the repository from GitHub.
Install the required Python libraries using the provided requirements.txt file.
Customize the list of stocks and their details in the code.
Run the main script to perform analysis on the specified stocks.
