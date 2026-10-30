# Sprint 8: Beta Bank customer churn prediction

## Summary
Predicts which customers will leave Beta Bank, handling class imbalance; target metric F1.

## Tools
pandas, NumPy, scikit-learn, Matplotlib

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `Churn.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Upsampled Random Forest: test F1 = 0.59 (meets threshold), AUC-ROC = 0.85.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
