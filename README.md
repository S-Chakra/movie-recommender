# Movie Recommender System

A hybrid recommender that predicts how users will rate movies.

## What it does
- Loads 641,699 ratings and maps 2,113 users and 10,001 movies to indices
- Builds sparse (SciPy CSR) and dense rating matrices
- Baseline bias model: validation RMSE 0.8235
- NMF matrix factorization (35 factors)
- Hybrid blend of the two (alpha tuned to 0.25): validation RMSE 0.809
- Retrained on the full set and predicted 71,299 test pairs

## Tech
Python, Pandas, NumPy, SciPy, scikit-learn, Jupyter

## Data
The ratings data was provided by the course and isn't included in this repo.
