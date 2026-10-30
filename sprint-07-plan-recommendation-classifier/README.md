# Sprint 7: Megaline plan recommendation classifier

## Summary
Classifies which plan (Smart/Ultra) to recommend from user behavior.

## Tools
pandas, scikit-learn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `users_behavior.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Random Forest (max_depth=10, n_estimators=10): validation accuracy ~0.79, test accuracy ~0.81 (threshold 0.75; dummy ~0.5).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
