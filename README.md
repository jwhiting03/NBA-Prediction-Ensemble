This is an ensemble machine learning method that predicts the outcome of NBA games based on player and team statistics
The models used are an Xgboost, Lasso Logistic Regression, and Ridge Logistic Regression.
Then it is a confidence based ensemble that uses Gaussian Mixture Model clustering

## Data Setup
Download the required datasets using the Kaggle CLI:

```bash
kaggle datasets download -d wyattowalsh/basketball --unzip -p data/
kaggle datasets download -d jacobwhiting03/2022-to-2026-nba-players --unzip -p data/
kaggle datasets download -d jacobwhiting03/nba-abbreviations --unzip -p data/
```
