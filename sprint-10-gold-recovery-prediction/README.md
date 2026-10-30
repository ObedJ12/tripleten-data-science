# Sprint 10: Gold recovery prediction

## Summary
Predicts rougher and final gold recovery in an ore purification process; validates the recovery formula and uses a weighted sMAPE.

## Tools
pandas, NumPy, scikit-learn, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `gold_recovery_train.csv`
- `gold_recovery_test.csv`
- `gold_recovery_full.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Random Forest was best in cross-validation (final sMAPE 6.20 vs 7.31–8.36 for others); final sMAPE on the test set: 10.91.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
