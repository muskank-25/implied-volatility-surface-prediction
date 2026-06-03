# Implied Volatility Surface Prediction
Finance Club, IIT Roorkee — Open Projects 2026

## Approach
PCHIP time-series interpolation blended with cross-sectional 
smile interpolation on log-moneyness basis. Blend weight tuned 
on 10% hold-out of observed values.

## Files
- `nifty.ipynb` — main notebook, run top to bottom
- `dataset.csv` — original dataset
- `filled_dataset.csv` — dataset with all missing values filled
- `submission.csv` — final Kaggle submission
- `submission-converter.ipynb` — converts filled dataset to submission format

## How to Run
1. Place `dataset.csv` in the same directory as `nifty.ipynb`
2. Run all cells top to bottom
3. `submission.csv` and `filled_dataset.csv` will be generated automatically
