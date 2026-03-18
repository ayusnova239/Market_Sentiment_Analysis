**Project title:**
Trader Behavior vs Market Sentiment Analysis
**Dataset used:**
fear_greed_index.csv — Bitcoin market sentiment data
historical_data.csv — Hyperliquid historical trader data
**Setup:**
Python 3.13.3
Libraries: pandas, numpy, matplotlib
**How to run:**:
Clone the repo
Place both CSV files in the same folder as the notebook
Run all cells in order
**Methodology:**
Two datasets were merged on date — Bitcoin Fear/Greed sentiment data and Hyperliquid historical trader data. Key metrics were computed including daily PnL, win rate, average trade size, trades per day, and long/short ratio. Analysis was performed by grouping data on sentiment classification.

**Insights:**
1. Extreme Greed days yield the highest average PnL (67.89) and win rate (0.46), while Extreme Fear days show the lowest performance.
2. Traders place significantly larger positions on Fear days (avg $7816) despite lower returns, indicating panic-driven behavior.
3. Frequent traders execute 7x more trades than infrequent traders, but higher volume does not guarantee better win rates.

**Strategy Recommendations:**
1. During Fear sentiments, traders should reduce position size to minimize losses as on Fear days traders place larger positions but wins less.
2.Infrequent traders should increase activity during Extreme Fear days where PnL is highest. 
