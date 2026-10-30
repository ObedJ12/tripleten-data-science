# Sprint 13: Sweet Lift taxi demand forecasting

## Summary
Hourly airport taxi order forecasting with lag/rolling/calendar features; target RMSE ≤ 48.

## Tools
pandas, NumPy, scikit-learn, Matplotlib

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `taxi.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Best tuned model, retrained on train+validation: test RMSE 26.61 (target ≤ 48).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
