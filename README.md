# Bitcoin Fear & Greed Index Trading Strategy

## 📌 Project Overview
This project analyzes the correlation between **Market Sentiment (Fear & Greed Index)** and **Trader Profitability**. The goal was to identify the best market conditions for trading Bitcoin.

## 🛠️ Tech Stack
- **Python** (Pandas, Matplotlib, Seaborn)
- **Data Analysis:** Data cleaning, Merging datasets, Groupby aggregation.
- **Visualization:** Bar charts to visualize profitability.

## 📊 Key Insights
Based on the analysis of historical data:
1.  **Best Time to Trade:** Traders have the highest Win Rate and Maximum Profit during **"Extreme Greed"**.
2.  **Worst Time to Trade:** Profitability drops significantly during **"Extreme Fear"**.
3.  **Risk:** During Fear, trade volume is high but the success rate is lower.

## 💡 Proposed Strategy
- **Aggressive Approach:** Increase position size when the index shows **"Extreme Greed"** (High Probability of Winning).
- **Defensive Approach:** Reduce leverage and tighten stop-loss during **"Extreme Fear"**.
