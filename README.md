# Nova Financial Insights — FNSPID Sentiment Analysis

Analyzing correlations between financial news sentiment and stock price movements.

## Project Structure
- `data/` — raw and processed datasets
- `notebooks/` — EDA, sentiment, and correlation analysis
- `src/` — reusable Python modules
- `reports/` — figures and final report

## Setup
```cmd
conda env create -f environment.yml
conda activate nenv
python -m ipykernel install --user --name nenv --display-name "Python (nenv)"
```