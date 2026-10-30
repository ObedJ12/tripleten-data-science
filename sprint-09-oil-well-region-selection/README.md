# Sprint 9: OilyGiant oil well region selection

## Summary
Linear regression per region plus 1,000-iteration bootstrap of profit/risk to choose where to drill.

## Tools
pandas, NumPy, SciPy, scikit-learn, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Only Region B kept risk of loss below 2.5%, so it is the recommended region.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
