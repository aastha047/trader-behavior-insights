# Trader Performance & Bitcoin Market Sentiment Analysis

Overview

This project explores the relationship between trader performance and Bitcoin market sentiment using two datasets:
1. Historical data
2. Fear and greed

The objective is to analyze how sentiment impacts trading behavior and profitability, uncover hidden patterns, and deliver insights that can guide smarter trading strategies.

Datasets:

Historical Data:
Columns: Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp IST, Start Position, Direction, Closed PnL, Transaction Hash, etc.

Link: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Fear and Greed Index: 
Columns: Timestamp, Value, Classification, Date

Link: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Steps Performed:

1. Data Cleaning and Preparation
2. Feature Engineering
3. EDA(Exploratory Data Analysis) and Visualization

How to run

1. Install required Python packages.
2. Download the datasets.
3. Open and run the jupyter notebook.

Insights:

1. PnL tends to be higher during "Greed" periods, suggesting traders capture more upside moves and actively exploit momentum.
2. The number of trades and position sizes are also higher during "Greed", reflecting greater risk appetite and confidence.
3. Top traders show a strong positive PnL during "Greed", indicating they are skilled at riding bullish momentum and scaling positions effectively.
4. During "Fear", more conservative behavior is observed (fewer trades and smaller positions). However, some traders still achieve positive PnL, highlighting opportunities for selective or contrarian strategies even in bearish sentiment.

Recommendations:

1. Align trading aggressiveness with market sentiment, which increase position sizes and trade frequency during "Greed", but maintain strict risk and stop-loss controls.
2. During "Fear", focus on selective, high-conviction trades or mean-reversion approaches rather than aggressive momentum chasing.
3. Integrate real-time sentiment monitoring into daily trading decisions to dynamically adapt strategies and improve risk-adjusted returns.
