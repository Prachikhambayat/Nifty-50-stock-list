# Nifty-50-stock-list

This project analyzes intraday stock data for NIFTY50 companies to calculate **sector momentum** and **stock volatility**. The analysis is implemented in Python using `yfinance`, `pandas`, `matplotlib`, and `seaborn`.

---

## Files

- `Nifty50_Analysis.ipynb` – Jupyter Notebook containing all data fetching, analysis, and visualizations.
- `nifty-50-stock-list.csv` – List of NIFTY50 companies with stock symbols and sectors.

---

## Features

- Fetches **1-minute intraday data** for all NIFTY50 stocks.
- Cleans and processes stock data.
- Calculates:
  - Intraday range (`High - Low`)
  - Percentage change in close prices
  - Stock volatility (standard deviation of % change)
  - Average sector momentum (% change)
- Generates visualizations:
  - Top 10 most volatile stocks
  - Sector-wise momentum comparison

---

## Installation

1. Clone the repository:
 
```bash
git clone https://github.com/Prachikhambayat/Nifty-50-stock-list.git
cd  Nifty-50-stock-list     (Folder_Name)


