# Trader Performance vs Market Sentiment

## 📌 Project Overview
This project analyzes how **market sentiment (Fear vs Greed)** impacts trader performance and behavior.  
The analysis focuses on **PnL, win rate, drawdown risk**, and **behavioral changes** such as trade frequency, position sizing, and long/short bias.

---

## 📊 Key Questions Answered
- Does trader performance differ between **Fear** and **Greed** days?
- Do traders change behavior based on market sentiment?
- How do different trader segments perform under varying sentiment?

---

## 📂 Dataset & Features
Key features used in the analysis:
- `daily_pnl`
- `win_rate`
- `drawdown_proxy`
- `trade_frequency`
- `position_size_usd`
- `long_ratio`
- Market sentiment classification (`Fear`, `Greed`, `Neutral`)

---

## 🔍 Methodology
1. Aggregated daily trader metrics by market sentiment
2. Compared performance metrics using tables and charts
3. Segmented traders into:
   - Frequent vs Infrequent traders
   - Consistent vs Inconsistent traders
4. Visualized insights using bar plots and box plots

---

## 📈 Key Insights
- **Fear days** show more stable PnL and smaller drawdowns.
- **Greed days** exhibit higher trading activity and larger downside risk.
- Frequent traders trade more aggressively during Greed periods.
- Consistent traders achieve better risk-adjusted performance than inconsistent traders.

---

## 🧠 Actionable Takeaways
- Reduce leverage during **Greed** periods to control drawdown risk.
- Increase trade frequency selectively during **Fear** periods for consistent traders.
- Apply stricter risk controls for inconsistent traders.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📎 Files
- `Trader_Performance_vs_Market_Sentiment.ipynb` — Full analysis and visualizations

---

## 👤 Author
Gauri  
