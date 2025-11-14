# Financial News Sentiment Project

This folder contains a ready-to-run **Jupyter notebook** and scaffolding for an end-to-end financial sentiment classification assignment.

## Files
- `financial_sentiment_project.ipynb` — main notebook (data, EDA, modeling, evaluation, application).
- `requirements.txt` — suggested Python packages.
- `data/` — put your datasets here (e.g., `financial_phrasebank.csv` with columns `text,label`). 
- `outputs/` — artifacts (splits, models, scraped headlines).

## Quick Start
1. Create/activate a Python 3.10+ environment.
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter lab  # or jupyter notebook
   ```
4. If you have no internet/GPU, skip transformer/BiLSTM sections and run NB+TF-IDF baseline.

## Scraping
The notebook includes a Google News RSS–based scraper for ticker news. This may break if providers change; if it fails, save headlines to CSV and proceed.

## Notes
- Your grade emphasizes **data prep, EDA, and rationale** over raw accuracy. Write thoughtful comments in the indicated sections.
- Try **time-based splits** and domain-specific models (**FinBERT**) for extra credit.
