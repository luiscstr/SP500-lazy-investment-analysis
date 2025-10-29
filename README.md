# SP500 investment lazy optimization analysis- Historical S&P 500 Performance & Seasonal Strategy Analysis
Note: THis notebook contains several interactive plotly charts. To visualize them use nbviewer

# Objective:
Analyze S&P 500 historical performance (1950–2025) to evaluate long-term growth trends, seasonal patterns (e.g., “Sell in May”), and contribution timing strategies — comparing Dollar-Cost Averaging (DCA) vs. Lump-Sum Investing to determine the optimal long-term approach.

# Data Overview
- Source: Yahoo Finance via pandas_datareader + manual CSV merge (1950–1970 data to bypass Windows epoch limit).
- Data Span: 1950–2025 daily S&P 500 values.

 # Tools & Libraries
- Data & Math: pandas, numpy, pandas_datareader, datetime, numba
- Visualization: matplotlib, seaborn, plotly
- Statistics: statsmodel

 # Key Insights
  - Long-term investing consistently outperforms seasonal timing strategies.
  - “Sell in May” and other anomalies exist but lack sustained statistical advantage.
  - Lump-sum investing consistently outperformed all DCA variants in total return due to earlier market exposure.
  - DCA reduced short-term volatility and drawdowns but sacrificed long-term growth.
  - Contribution timing influences volatility more than total return — time in the market beats timing the market.
  - Best strategy: Invest lump sums immediately and stay invested for the long run.
