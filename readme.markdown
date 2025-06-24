# Trader Behavior Insights Project

## Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed Index) and trader performance using historical trader data from Hyperliquid. The goal is to uncover patterns and deliver insights for smarter trading strategies in the Web3 space.

## Datasets
1. **Bitcoin Market Sentiment Dataset** (`fear_greed_index.csv`):
   - Columns: `Date`, `Classification` (Fear/Greed)
2. **Historical Trader Data** (`historical_data.csv`):
   - Columns: `Account`, `Symbol`, `Execution Price`, `Size`, `Side`, `Time`, `Start Position`, `Event`, `ClosedPnL`, `Leverage`, etc.

## Analysis
- **Preprocessing**: Cleaned and merged datasets, aggregating trader data to daily level.
- **Correlation Analysis**: Examined relationship between Closed PnL and Fear/Greed Index with lags (0-7 days).
- **Statistical Tests**: Conducted t-tests to compare BUY vs. SELL trades in Fear sentiment and PnL across Fear vs. Greed periods.
- **Trader & Coin Insights**: Identified top-performing traders and coins (@107, HYPE, SOL) with key metrics (PnL, trade count, size).
- **Strategy Recommendations**: Developed trading strategies based on sentiment, coin performance, and trade sizes.

## Key Findings
1. Weak correlation (-0.05 to -0.07) between Closed PnL and Fear/Greed Index.
2. Fear sentiment yields highest PnL ($3.36M), with BUY trades outperforming SELL ($1.94M vs. $1.42M).
3. Top coins: @107 ($2.78M PnL), HYPE ($1.95M), SOL ($1.64M).
4. Top traders: `0xb1231a4a2dd02f2276fa3c5e2a2f3436e6bfed23`, `0x083384f897ee0f19899168e3b1bec365f52a9012`, `0xbaaaf6571ab7d571043ff1e313a9609a10637864`.
5. Strategy: Prioritize BUY trades in Fear sentiment, trade @107/HYPE ($1,000–$5,000), SOL ($5,000–$12,000).

## Files
- `TradeAnalysis.ipynb`: Jupyter Notebook with full analysis code and outputs.
- `fear_greed_index.csv`: Bitcoin market sentiment data.
- `historical_data.csv`: Historical trader data from Hyperliquid.

## Dependencies
- Python 3.11
- Libraries: `pandas`, `matplotlib`, `seaborn`, `scipy`

## Usage
1. Clone the repository.
2. Install dependencies: `pip install pandas matplotlib seaborn scipy`
3. Run `TradeAnalysis.ipynb` in a Jupyter environment to explore the analysis.

## Ideal Candidate
- Subject: "Junior Data Scientist – Trader Behavior Insights"
- Email: hrishabkakoty21@gmail.com
- Degree: Btech CSE Graduate
