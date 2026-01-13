# Trader-Performance-Analysis-Under-Market-Sentiment-Regimes
This project analyzes the relationship between market sentiment (Fear &amp; Greed Index) and trader performance using historical crypto trading data.The analysis combines sentiment data with trade-level execution data, performs statistical aggregation, and visualizes key insights.

Overview
This project analyzes how crypto traders perform under different market sentiment regimes (Fear, Greed, Extreme conditions) using historical trade data and the Fear & Greed Index.

Data
Historical Trader Data: Trade executions, size, PnL, fees, accounts
Fear & Greed Index: Daily market sentiment classification

Approach
Convert and align timestamps
Merge sentiment with trades using last-known sentiment
Analyze PnL, win rate, ROI, risk metrics
Identify consistent traders across regimes
Visualize results using bar charts, heatmaps, and boxplots

Key Insights
Extreme Greed shows better risk-adjusted performance
Fear and Greed generate higher total PnL due to higher activity
Only a few traders remain consistent across sentiment regimes

Sentiment has weak direct correlation with individual trade outcomes

Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
