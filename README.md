# Ds_Aaron
#  Trader Behavior vs. Market Sentiment Analysis

This project analyzes how trading behavior (profitability, risk, volume, and leverage) aligns or diverges from the Bitcoin market sentiment (Fear vs. Greed). Using real trader data from Hyperliquid and the Fear & Greed Index, we explore patterns that could influence smarter trading strategies.

---

# Project Structure
ds_Aaron/
├── notebook_1.ipynb # Main analysis notebook (Google Colab)
├── csv_files/ # Contains raw & processed CSV files
│ ├── fear_greed_index.csv
│ ├── sentiment_summary.csv
│ └── merged_data.csv
├── outputs/ # Visualizations and charts
│ ├── pnl_by_sentiment.png
│ └── avg_leverage_chart.png
├── ds_report.pdf # Final report summarizing insights
└── README.md # This file



# Setup Instructions

# Requirements
- Python 3.7+
- Google Colab (preferred)
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`

# 1. Open Notebook
Launch `notebook_1.ipynb` using [Google Colab](https://colab.research.google.com). All processing and analysis are done there.

# 2. Mount Google Drive
Make sure both datasets (`historical_data.csv` and `fear_greed_index.csv`) are stored in your Google Drive. The notebook will guide you to mount the Drive.

# 3. Run All Cells
Execute each cell step-by-step:
- Load datasets
- Preprocess data
- Merge with sentiment index
- Analyze trading patterns
- Generate summary and charts



# Output

# Generated:
- A table showing key metrics grouped by market sentiment
- Charts:
  - Profitability vs. Sentiment
  - Average Leverage vs. Sentiment
- CSVs with summary stats and merged datasets



# Notes

- The `Crossed` field was used as a proxy for leverage. Replace with `leverage` column if available.
- All timestamps were normalized to `YYYY-MM-DD` for accurate merging.
- Only records with valid sentiment labels were used in the analysis.





