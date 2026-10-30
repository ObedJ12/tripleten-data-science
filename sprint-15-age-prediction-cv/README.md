# Sprint 15: Age estimation from face photos (computer vision)

## Summary
Regresses a person's age from photos with a TensorFlow/Keras CNN; target MAE ≤ 8.

## Tools
TensorFlow/Keras, pandas, NumPy, Matplotlib, seaborn

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `labels.csv`
- `faces/ (image folder)`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Best validation MAE 6.64 (epoch 17), meeting the ≤ 8 target; train MAE ~3.1 indicates moderate overfitting.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
