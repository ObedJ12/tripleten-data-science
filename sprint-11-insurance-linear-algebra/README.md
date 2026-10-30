# Sprint 11: Insurance: kNN, linear regression, and data obfuscation

## Summary
Similar-customer search with kNN, benefit classification, linear regression implemented with matrix ops, and invertible-matrix data masking.

## Tools
pandas, NumPy, scikit-learn, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `insurance_us.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Scaling materially affects kNN (best F1 0.95 on scaled data, k = 1 per the write-up). Linear regression RMSE 0.3602 is identical on original and obfuscated data (outputs; the written text cites 0.34/0.66).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
