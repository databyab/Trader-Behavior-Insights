# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid.

---

## Methodology

1. Cleaned and aligned trader data with daily sentiment data.
2. Created key metrics:
   - Daily PnL per trader
   - Win rate
   - PnL volatility (risk proxy)
   - PnL per trade (efficiency)
   - Aggression score (capital exposure proxy)
3. Compared performance across sentiment regimes.
4. Segmented traders into:
   - High vs Low Frequency
   - High vs Low Aggression
   - Consistent vs Inconsistent

---

## Key Insights

1. Fear regimes produce ~2× higher profitability but with significantly higher volatility.
2. High-frequency and high-aggression traders generate higher returns but experience amplified risk.
3. Extreme Greed regimes show declining trade efficiency and increased long bias.

---

## Strategy Recommendations

**1. Volatility-Based Scaling During Fear**
Increase participation during Fear regimes while applying tighter risk controls due to elevated volatility.

**2. Reduce Directional Aggression During Extreme Greed**
Limit long exposure and avoid excessive trading during Extreme Greed to prevent inefficiency.

---

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
