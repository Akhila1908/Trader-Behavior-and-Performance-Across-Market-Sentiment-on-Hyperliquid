# Trader-Behavior-and-Performance-Across-Market-Sentiment-on-Hyperliquid

This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform using Bitcoin market sentiment data.

## Dataset Sources
- Bitcoin Fear & Greed Index (Daily)
- Hyperliquid Historical Trader Data (Trade-level)

## Setup Instructions
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Methodology
Trade-level data from Hyperliquid was aligned with daily Bitcoin market sentiment (Fear/Greed). Trades were aggregated at a daily trader level, and key metrics such as PnL, win rate, leverage proxy, trade frequency, and positioning bias were analyzed across sentiment regimes.

## Key Insights
1. Trader performance varies significantly by sentiment regime, with higher returns and higher risk observed during Greed days.
2. Traders increase leverage, trade frequency, and long bias during Greed periods, while adopting conservative behavior during Fear regimes.
3. High-leverage and frequent traders outperform in Greed markets but experience larger drawdowns during Fear regimes, whereas consistent traders remain resilient across both regimes.

## Strategy Recommendations
- During Fear regimes, reduce leverage and trade frequency, especially for high-risk trader segments.
- During Greed regimes, selectively increase activity for frequent traders while capping leverage to manage downside risk.

These findings highlight the importance of sentiment-aware risk management in crypto trading.
