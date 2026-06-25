# Exploring Reviewing Culture in Letterboxd's Top 250 Film Community

## Overview

This project explores linguistic patterns, sentiment expression, and reviewing 
culture in Letterboxd's Top 250 film community. Using a corpus of 67,574 reviews 
across 195 films, it applies computational text analysis methods including word 
frequency analysis, sentiment scoring, and topic modeling.

This project was completed as the Individual Coding Project for DIGHUM 101 UC Berkeley Summer 2026.

## Research Questions

1. What linguistic features characterize reviews in Letterboxd's Top 250 film community?
2. What themes and topics appear most frequently in these reviews?
3. How do users express sentiment and emotional engagement toward highly regarded films?
4. What do these patterns suggest about the reviewing culture reflected in this corpus?

## Data Sources

- [Letterboxd Movie Reviews Dataset（90016 Reviews)] — 90,016 reviews  
https://www.kaggle.com/datasets/riyosha/letterboxd-movie-reviews-90000 
- [Letterboxd Movie Metadata Dataset] — film genres and spoken languages  
https://www.kaggle.com/datasets/ky1338/10000-movies-letterboxd-data 
- [IMDb Movie Reviews Dataset] — used in early exploratory phase only  
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews 


## Methods

- Review length analysis (by film, genre, rating, spoken language)
- Word frequency analysis with custom stopword filtering
- Sentiment analysis using VADER
- Topic modeling using Latent Dirichlet Allocation (LDA)

## Repository Structure

```
letterboxd-top250-reviewing-culture/
├── notebooks/
│   └── analysis.ipynb
├── README.md
└── .gitignore
```

> Data files are not included due to file size. All datasets are publicly available on Kaggle (see Data Sources above).

## Requirements

This project uses the course environment `dighum101`. Two additional packages need to be installed:

```bash
pip install vaderSentiment pyLDAvis
```

Full dependency list:
- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `scikit-learn`
- `vaderSentiment`
- `pyLDAvis`