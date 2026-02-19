# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes how market sentiment (Fear & Greed Index) affects trader performance.

The analysis evaluates:
- Daily Profit & Loss (PnL)
- Win Rate
- Trade Frequency
- Risk (Volatility)

The goal is to understand whether trader performance changes across different sentiment regimes.

---

## Setup Instructions

### 1. Clone the Repository

git clone https://github.com/Rahul107213/primetrade.ai.git
cd your-repository-name

---

### 2. Create Virtual Environment (Recommended)

python -m venv venv

Activate:

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

---

### 3. Install Dependencies

pip install pandas numpy matplotlib seaborn scipy jupyter

---

## How to Run

Run Jupyter Notebook:

jupyter notebook

Then open the notebook file (e.g., analysis.ipynb) and run all cells.

---

## Project Workflow

1. Data cleaning and timestamp correction  
2. Daily metric creation (PnL, Win Rate, Trade Count)  
3. Merge trader data with sentiment index  
4. Regime-based performance comparison  
5. Statistical testing (T-test)  
6. Visualization and final conclusions  

---

## Conclusion

The analysis shows that trader profitability varies across sentiment regimes, with Fear periods showing higher average returns but also higher volatility. The results suggest that incorporating market sentiment can improve understanding of trading performance.
