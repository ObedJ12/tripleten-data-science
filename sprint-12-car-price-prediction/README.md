# Sprint 12: Rusty Bargain used car price prediction

## Summary
Predicts used car market value, weighing RMSE vs training/prediction time.

## Tools
pandas, NumPy, scikit-learn, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `car_data.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Random Forest best validation RMSE 1805.97 (vs Decision Tree 2083.22, Linear Regression 2880.73); test RMSE 1767.7.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
