# Sprint 14: IMDB movie review sentiment classification

## Summary
Classifies reviews as positive/negative (target F1 ≥ 0.85) with NLTK/spaCy preprocessing, TF-IDF, linear models, LightGBM and BERT embeddings.

## Tools
pandas, NumPy, NLTK, spaCy, scikit-learn, LightGBM, Transformers

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `imdb_reviews.tsv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
TF-IDF + Logistic Regression is best: test F1 ≈ 0.88, ROC AUC 0.95.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
