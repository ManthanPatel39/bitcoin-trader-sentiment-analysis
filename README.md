# bitcoin-trader-sentiment-analysis
## Project Overview
Analyzed trader performance and behavior patterns using Bitcoin market sentiment (Fear &amp; Greed Index) with Python, Pandas, and data visualization.
The goal is to understand whether market sentiment has any visible relationship with trader profitability, win rate, and trading behavior.

## Objective
- Merge trader-level historical trading data with daily market sentiment data
- Create account-level daily features
- Segment traders based on behavior patterns
- Compare performance across different sentiment conditions

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Used
- Historical trader data
- Bitcoin Fear & Greed Index data

## Key Analysis Performed
- Data cleaning and preprocessing
- Date alignment between both datasets
- Feature engineering at account-day level
- Trader segmentation based on:
  - Trade size
  - Trading frequency
  - Consistency of profitable days
- Performance comparison across sentiment groups
- Visualization of PnL and win-rate trends

## Key Insight
The analysis suggests that market sentiment can act as a useful contextual signal when evaluating trader behavior and profitability. Different trader segments showed different performance patterns under varying sentiment conditions.

## Files in this Repository
- `bitcoin_trader_sentiment_analysis.ipynb` → Main notebook
- `historical_data.csv` → Historical trader data
- `fear_greed_index.csv` → Fear & Greed Index data
- `final_trader_daily_features.csv` → Engineered account-day dataset
- `segment_comparison_summary.csv` → Final segment comparison output

## AUTHOR
**MANTHAN PATEL**
