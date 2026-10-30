# Sprint 3: Megaline prepaid plan revenue (statistical analysis)

## Summary
Compares revenue from Megaline's Surf vs Ultimate plans and tests regional revenue differences using monthly per-user usage and overage charges.

## Tools
pandas, NumPy, SciPy, Matplotlib

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `megaline_calls.csv`
- `megaline_internet.csv`
- `megaline_messages.csv`
- `megaline_plans.csv`
- `megaline_users.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Welch's t-test (α = 0.05): the written conclusion reports a significant NY-NJ vs other-region difference (p = 0.0186; $57.19 vs $62.88 per month).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
