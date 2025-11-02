# Portfolio Risk Analysis using Value at Risk (VaR)

This project analyzes and estimates the financial risk of a diversified stock portfolio using **Value at Risk (VaR)** models in Python.

## 📊 Overview
The notebook demonstrates how to calculate and compare different risk measures using real stock data from **Yahoo Finance**. It follows a step-by-step approach to compute:
- **Daily Log Returns**
- **Parametric VaR (Normal & Student’s t)**
- **Historical VaR**
- **Expected Shortfall (ES)**
- **VaR Backtesting**
- **Rolling 60-Day VaR Visualization**
- **Jarque–Bera Normality Test**

## 🧠 Key Concepts
- **VaR (Value at Risk):** Maximum expected loss over a given time period at a specific confidence level.  
- **Expected Shortfall:** Average loss on the worst 5% of days.  
- **Backtesting:** Validating how often losses exceed the VaR estimate.  

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `yfinance`

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Portfolio-Risk-Analysis-VaR.git

   Open the Jupyter Notebook:

jupyter notebook Anand_Kumar_Yadav_var.ipynb


Run all cells sequentially to reproduce results.

📈 Results

Compares Normal, t-distribution, and Historical VaR.

Estimates Expected Shortfall (ES) and performs VaR backtesting.

Visualizes portfolio risk trends over time.

👨‍💻 Author

Anand Kumar Yadav
Portfolio Risk Analysis | Python | Financial Modelling

📅 Developed as part of a financial risk analysis project using Python.
