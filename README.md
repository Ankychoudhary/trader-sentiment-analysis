# 📊 Trader Performance vs Market Sentiment Analysis

### Data Science Intern Assignment – Primetrade.ai

---

## 📌 Objective

The goal of this project is to analyze how market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.

We aim to uncover patterns that can inform smarter trading strategies.

---

## 📂 Datasets Used

1. **Bitcoin Market Sentiment Dataset**
   - Columns: Date, Classification (Fear/Greed)

2. **Historical Trader Data (Hyperliquid)**
   - Includes: account, price, size, side, timestamp, PnL, etc.

---

## ⚙️ Methodology

1. **Data Cleaning**
   - Handled missing values
   - Standardized column names
   - Converted timestamps to datetime format

2. **Data Merging**
   - Aligned both datasets at daily level using date

3. **Feature Engineering**
   - Win rate calculation
   - Daily PnL per trader
   - Trade frequency
   - Trade size as proxy for risk

4. **Analysis**
   - Compared performance across sentiment regimes
   - Analyzed trading behavior (long/short, size)
   - Segmented traders (frequent vs infrequent)

---

## 📊 Key Insights

- Extreme Greed shows the highest profitability and win rate.
- Fear periods are more stable but less profitable.
- Trade sizes increase during Greed, indicating higher risk appetite.
- Traders prefer long positions during bullish sentiment.
- Frequent traders may underperform due to overtrading.

---

## 💡 Strategy Recommendations

- Increase exposure during strong bullish (Greed) conditions.
- Reduce position sizes during Fear to manage risk.
- Avoid excessive trading during moderate Greed phases.
- Focus on high-quality trades over high-frequency trading.

---

## 🧠 Conclusion

Market sentiment significantly influences trader behavior and performance.  
Understanding these patterns helps design more disciplined and adaptive trading strategies.

---

## 🛠️ Tech Stack

- Python
- Pandas
- Matplotlib

---

## ▶️ How to Run

1. Clone the repository
2. Open the notebook in Google Colab / Jupyter
3. Run all cells sequentially

---

## 📎 Author

Angkita Chowdhury
