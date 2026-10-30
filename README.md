# TripleTen Data Science Projects

These are my sprint projects from the TripleTen Data Science bootcamp. They cover data wrangling, EDA, statistical testing, SQL, classical ML, time series, NLP, and computer vision. My capstone project (Interconnect churn prediction) lives in its own repo, `tripleten-capstone-interconnect-churn`.

## Tools
Python, pandas, NumPy, Matplotlib, seaborn, SciPy, scikit-learn, LightGBM, NLTK, spaCy, Hugging Face Transformers, TensorFlow/Keras, and Jupyter.

## Projects
| Sprint | Project | Result |
|---|---|---|
| 2 | [Instacart shopping patterns EDA](sprint-02-instacart-eda/) | Bananas and other staples (e.g. milk) top the most-popular and first-in-cart lists; a subset of customers reorders heavily, which supports loyalty and bundling strategies. |
| 3 | [Megaline prepaid plan revenue (statistical analysis)](sprint-03-megaline-plan-revenue/) | Welch's t-test (α = 0.05): the written conclusion reports a significant NY-NJ vs other-region difference (p = 0.0186; $57.19 vs $62.88 per month). |
| 5 | [Video game sales analysis (Integrated Project 1)](sprint-05-video-game-sales/) | Action, Sports, and Shooter lead sales. Xbox One vs PC user ratings differ significantly (p ≈ 9.5e-06); Action vs Sports ratings do not (p ≈ 0.28). |
| 6 | [Chicago taxi rides: SQL results EDA and weather hypothesis test](sprint-06-chicago-taxi-sql-analysis/) | Flash Cab and Taxi Affiliation Services led trip volume; Loop, River North, and Streeterville led drop-offs. Rainy Saturday ride durations differ significantly (p < 0.05). |
| 7 | [Megaline plan recommendation classifier](sprint-07-plan-recommendation-classifier/) | Random Forest (max_depth=10, n_estimators=10): validation accuracy ~0.79, test accuracy ~0.81 (threshold 0.75; dummy ~0.5). |
| 8 | [Beta Bank customer churn prediction](sprint-08-bank-customer-churn/) | Upsampled Random Forest: test F1 = 0.59 (meets threshold), AUC-ROC = 0.85. |
| 9 | [OilyGiant oil well region selection](sprint-09-oil-well-region-selection/) | Only Region B kept risk of loss below 2.5%, so it is the recommended region. |
| 10 | [Gold recovery prediction](sprint-10-gold-recovery-prediction/) | Random Forest was best in cross-validation (final sMAPE 6.20 vs 7.31–8.36 for others); final sMAPE on the test set: 10.91. |
| 11 | [Insurance: kNN, linear regression, and data obfuscation](sprint-11-insurance-linear-algebra/) | Scaling materially affects kNN (best F1 0.95 on scaled data, k = 1 per the write-up). Linear regression RMSE 0.3602 is identical on original and obfuscated data (outputs; the written text cites 0.34/0.66). |
| 12 | [Rusty Bargain used car price prediction](sprint-12-car-price-prediction/) | Random Forest best validation RMSE 1805.97 (vs Decision Tree 2083.22, Linear Regression 2880.73); test RMSE 1767.7. |
| 13 | [Sweet Lift taxi demand forecasting](sprint-13-taxi-demand-time-series/) | Best tuned model, retrained on train+validation: test RMSE 26.61 (target ≤ 48). |
| 14 | [IMDB movie review sentiment classification](sprint-14-imdb-sentiment-nlp/) | TF-IDF + Logistic Regression is best: test F1 ≈ 0.88, ROC AUC 0.95. |
| 15 | [Age estimation from face photos (computer vision)](sprint-15-age-prediction-cv/) | Best validation MAE 6.64 (epoch 17), meeting the ≤ 8 target; train MAE ~3.1 indicates moderate overfitting. |

## How to run
```bash
git clone https://github.com/ObedJ12/tripleten-data-science.git
cd tripleten-data-science
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```
The datasets aren't committed. Each sprint README lists the files that go in its `data/` folder.

Every notebook keeps its TripleTen reviewer feedback as part of the review history.
