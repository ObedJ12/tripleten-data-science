# Sprint 2: Instacart shopping patterns EDA

## Summary
Exploratory analysis of Instacart orders: when people shop, order sizes, reorder behavior, and top products.

## Tools
pandas, NumPy, Matplotlib

## Data
The data files aren't included in this repo. Put these files in this folder's `data/` directory (the notebook originally read them from TripleTen's `/datasets/` path):
- `aisles.csv`
- `departments.csv`
- `instacart_orders.csv`
- `order_products.csv`
- `products.csv`

## How to run
```bash
pip install -r ../requirements.txt
jupyter notebook notebook.ipynb
```
Before you run it, change the `/datasets/...` paths in the notebook to `data/...`.

## Results
Bananas and other staples (e.g. milk) top the most-popular and first-in-cart lists; a subset of customers reorders heavily, which supports loyalty and bundling strategies.

_TripleTen reviewer comments are kept in the notebook as part of the review history._
