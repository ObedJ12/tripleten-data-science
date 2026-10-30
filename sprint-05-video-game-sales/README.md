# Sprint 5: Video game sales analysis (Integrated Project 1)

## Summary
Finds patterns that drive game success for the online store Ice: platforms, genres, regions, ESRB ratings, plus hypothesis tests.

## Tools
pandas, NumPy, SciPy, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `games.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Action, Sports, and Shooter lead sales. Xbox One vs PC user ratings differ significantly (p ≈ 9.5e-06); Action vs Sports ratings do not (p ≈ 0.28).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
