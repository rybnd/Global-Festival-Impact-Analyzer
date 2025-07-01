# Global Festival Impact Analyzer

Analyze the economic and social impact of major Indian festivals using financial news articles and public data.

## Project Overview
- **Goal:** Extract and visualize trends in spending, tourism, social sentiment, and business revenue around festivals like Diwali, Holi, etc.
- **Dataset:** [Indian Financial News Articles (2003–2020)](https://www.kaggle.com/datasets/hkapoor/indian-financial-news-articles-20032020?resource=download)
- **Tech Stack:** Python (Pandas, BeautifulSoup, Requests), Jupyter, Tableau/Power BI

## Features
- Scrape and collect supplementary data from tourism and business sources (if needed)
- Clean and preprocess news articles
- Extract festival-related mentions and analyze their economic/social impact
- Perform sentiment analysis on festival-related coverage
- Visualize findings in Jupyter and export to Tableau/Power BI

## How to Run

1. Clone this repo and download the Kaggle dataset into `data/`.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Explore and run notebooks in sequence under `/notebooks/`.
4. Export analysis and visualizations for dashboards.

## File Structure

- `data/` – Contains raw and processed data.
- `src/` – Python scripts for data processing and analysis.
- `notebooks/` – Jupyter notebooks for each project phase.
- `reports/` – Dashboards and report images.

## Credits
- Indian Financial News dataset from Kaggle, by hkapoor.
