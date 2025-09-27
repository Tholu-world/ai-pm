
# AI-Powered Portfolio Manager 

This project is a mini **AI-powered portfolio management app** built in Python.  
It combines **finance** and **machine learning** to help track stock investments, calculate portfolio performance, and predict short-term market trends.  

---

## ✨ Features
- 📈 **Live Stock Prices** → fetched using Yahoo Finance (`yfinance`)  
- 💰 **Profit/Loss Calculator** → computes gain or loss on each stock  
- 🤖 **AI Prediction** → uses Logistic Regression to estimate probability of next-day stock price increase  
- 📊 **Dashboard Visualization** → portfolio allocation (pie chart) & profit/loss (bar chart)  
- 📂 **Exportable Results** → saves summary into `CSV` for record-keeping  

---

##Tech Stack
- **Python**  
- `yfinance` (live stock data)  
- `pandas`, `numpy` (data handling)  
- `scikit-learn` (machine learning)  
- `matplotlib` (visualizations)  

---

## 📂 Project Files
- `week4_ai_portfolio_app.py` → main Python script  
- `week4_portfolio_summary.csv` → auto-generated portfolio summary  
- `week4_dashboard.png` → dashboard chart of allocation & P/L  

---

## 🚀 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/YOUR-USERNAME/ai-portfolio-manager.git
   cd ai-portfolio-manager

2. install dependencies:
    ```bash
   pip install yfinance pandas numpy matplotlib scikit-learn

3. Run the app:
   ```bash
   python week4_ai_portfolio_app.py
   
4. Enter ticker symbols(e.g, AAPL,TSLA,AMZN), number of shares and your buy price

5. The program will:
  - Fetch live stock prices
  - Calculate profit/loss
  - Predict probability of next-day price increase
  - Save results to CSV
  - Generate portfolio dashboard as a PNG

   
