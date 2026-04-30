
🚀 Machine Learning-based momentum trading strategy that predicts weekly stock returns and constructs a portfolio with risk-adjusted performance.

# Momentum Trading Strategy using Machine Learning

## Project Files

Notebook: [Open Jupyter Notebook](ParasSurve_QuantQuest_ESummit26.ipynb.ipynb.txt)

Report: [View Project Report](paras_surve_Momentum-Trading-Strategy-using-Machine-Learning.pdf_20260315_201249_0000.pdf)

Predictions CSV: [Download Weekly Predictions](paras_surve_weekly_predictions%20(8).csv)

This project implements a machine learning based momentum trading strategy developed for the QuantQuest Hackathon (E-Summit IIT Mandi).

## Objective
Predict whether a stock will generate positive returns over the next week and construct a weekly rebalanced portfolio.

## Dataset
Daily OHLCV stock data from Yahoo Finance (2017–2025).

Stocks used:
AAPL, MSFT, GOOGL, AMZN, META, TSLA, JPM, V, JNJ, BRK.B

## Features
- 5-day momentum
- 10-day momentum
- 20-day momentum
- rolling volatility

## Model
Random Forest Classifier

## Portfolio Construction
- Rank stocks by predicted probability
- Select top 2 stocks weekly
- Equal weight portfolio
- Weekly rebalancing

## Transaction Cost
0.1% entry + 0.1% exit

## Performance (After Transaction Cost)

Cumulative Return: 4.19x  
Annual Return: 20.87%  
Annual Volatility: 23.42%  
Sharpe Ratio: 0.89  
Max Drawdown: -31.96%

## Tools Used
Python  
Pandas  
Scikit-Learn  
Matplotlib  
Yahoo Finance API

## How to Run

1. Clone the repository
git clone https://github.com/surveparas484-art/momentum-trading-ml

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
Open ParasSurve_QuantQuest_ESummit26.ipynb in Jupyter Notebook
