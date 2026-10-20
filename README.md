# Trader Sentiment Analysis

Problem Statement: In cryptocurrency markets, market sentiment—often quantified by the Bitcoin Fear & Greed Index—drives behavioral shifts among traders. Extreme market conditions frequently lead to emotional decision-making, such as overtrading during fear or overleveraging during greed.

Trading platforms and retail traders lack structured, data-driven insights on:
- How overall market sentiment impacts individual trading performance (PnL) and win rates.
- Which trader archetypes (e.g., high-risk, frequent traders) suffer the largest drawdowns during adverse market states.
- How to quantitatively predict daily profitability and build adaptive risk-management rules to protect capital.

Solution: This project analyzes the relationship between Bitcoin market sentiment and trader behavior/performance using historical trading data from Hyperliquid combined with the Bitcoin Fear & Greed Index.

Key aspects of the analysis and predictive modeling include:
- Behavioral & Performance Analysis: Evaluates daily PnL, trading frequency, trade sizes, and directional bias (Long vs. Short ratio) across different sentiment regimes (Extreme Fear, Fear, Neutral, Greed, Extreme Greed).

- Trader Archetype Segmentation: Applies K-Means Clustering to segment traders into distinct archetypes (Conservative Traders, Aggressive Traders, and Over-Traders) based on activity level, trade size, win rate, and directional bias.

- Predictive Modeling: Builds a Random Forest Classifier to forecast next-day profitability using trade metrics and market sentiment features.

- Actionable Risk Strategies: Derives concrete, data-backed strategy rules, such as capping position sizes and setting trade-frequency limits during Fear periods, to mitigate emotional overtrading and excessive drawdowns.

# Tech Stack
- Data Science: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn
- Machine Learning: RandomForestClassifier, KMeans Clustering.

# Setup Installation
```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
git clone https://github.com/ujjwalkumar14b/Data_Science_Project.git
cd Data_Science_Project
```

## Author
Ujjwal Kumar
GitHub: [https://github.com/ujjwalkumar14b](https://github.com/ujjwalkumar14b)
