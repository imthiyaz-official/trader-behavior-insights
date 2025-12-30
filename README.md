# Trader Behavior Insights under Fear & Greed Market Conditions

## Objective
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior, focusing on risk exposure, profitability, and trading outcomes.

## Datasets
- **Trader Transaction Data**: Historical trade-level data including execution price, position size, PnL, and timestamps.
- **Market Sentiment Data**: Bitcoin Fear & Greed Index used to classify market conditions into Fear and Greed.

Neutral sentiment data was excluded to clearly compare behavioral differences.

## Methodology
- Converted timestamps to datetime format
- Extracted date features for merging datasets
- Filtered sentiment to Fear and Greed
- Merged trader data with sentiment data on date
- Performed exploratory data analysis and visualization
- Generated a cleaned dataset (`processed_data.csv`) for analysis

## Key Insights
- Traders take larger position sizes during Fear periods, indicating higher risk exposure
- Greed periods show comparatively controlled risk-taking
- Higher risk does not always lead to higher profitability
- Market sentiment significantly impacts trading behavior and outcomes

## Outputs
- `processed_data.csv`: Cleaned and merged dataset used for analysis
- Visualizations:
  - Average PnL by Market Sentiment
  - Risk Exposure (Position Size) by Sentiment
  - Win Rate by Sentiment
  - PnL Distribution by Sentiment

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Google Colab

## Files Included
- `notebook_1.ipynb` – Analysis notebook
- `csv_files/processed_data.csv` – Processed dataset
- `outputs/` – Generated charts
- `ds_report.pdf` – Detailed analysis report

## Author
Syed Imthiyaz
