# Stock Trend Analyzer

A simple Python program to analyze stock price trends using historical data fetched from Yahoo Finance.  
It plots the last 30 days of closing prices along with 5-day and 10-day Simple Moving Averages (SMA).

---

## Features

- Fetches last 30 days stock price data using `yfinance`  
- Calculates 5-day and 10-day SMAs  
- Plots closing price and moving averages using `matplotlib`  
- Interactive: lets user input any valid stock ticker symbol  
- Handles invalid ticker input with error messages

---

## Requirements

- Python 3.x  
- yfinance  
- matplotlib  
- pandas

---

## Installation

Use pip to install the required packages:

```bash
pip install yfinance matplotlib pandas
