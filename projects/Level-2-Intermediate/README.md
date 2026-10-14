# Level 2 (Intermediate) — Sentiment Analysis of X (Twitter) Data

## Objective
Perform sentiment analysis on X (Twitter) data using VADER to categorize tweets as positive, negative, or neutral, and evaluate VADER's accuracy.

## Dataset
- **Source:** NLTK Twitter Sample (10,000 tweets)
- **Labels:** 5,000 positive + 5,000 negative
- **Note:** The original ShadowFox dataset link was unavailable; NLTK sample used as an alternative.

## Tools Used
- **NLTK** — VADER Sentiment Analyzer, Twitter sample dataset
- **Pandas** — Data manipulation
- **Matplotlib + Seaborn** — Static visualizations
- **Plotly** — Interactive visualizations
- **WordCloud** — Text visualization

## Key Results
- **VADER Accuracy:** 87.19% (on non-neutral tweets)
- **Sentiment Distribution:**
  - Positive: 5,536 (55.4%)
  - Negative: 3,673 (36.7%)
  - Neutral: 791 (7.9%)
- **Classification Performance:**
  - Positive F1-score: 0.88
  - Negative F1-score: 0.86

## Files
- `sentiment_analysis.ipynb` — Main analysis notebook
- `data/` — (Empty; NLTK data is loaded programmatically)

## Conclusions
VADER performs strongly on Twitter data (~87% accuracy) without requiring model training. It handles informal language, emojis, and slang effectively. Combining VADER with machine learning models could improve accuracy further.

## References
- NLTK VADER: https://github.com/cjhutto/vaderSentiment
- NLTK Twitter Sample: https://www.nltk.org/howto/twitter.html

### Note on Dataset
The dataset link provided in the task PDF was unavailable (returned "file does not exist"). 
The ShadowFox team was contacted via email (g2doubts@shadowfox.in) for an updated link.
While awaiting response, NLTK's public Twitter sample dataset was used as a fully 
compliant alternative for VADER sentiment analysis.