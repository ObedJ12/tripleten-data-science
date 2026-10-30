# Sprint 6: Chicago taxi rides: SQL results EDA and weather hypothesis test

## Summary
Analyzes SQL-extracted Chicago taxi data (Nov 2017): top companies, top drop-off neighborhoods, and whether rain changes Loop→O'Hare Saturday ride durations.

## Tools
pandas, NumPy, SciPy, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `project_sql_result_01.csv`
- `project_sql_result_04.csv`
- `project_sql_result_07.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Flash Cab and Taxi Affiliation Services led trip volume; Loop, River North, and Streeterville led drop-offs. Rainy Saturday ride durations differ significantly (p < 0.05).

_TripleTen reviewer comments are kept in the notebook as part of the review history._
