# loan-prediction

Predicting bank loan approval from applicant data — a full exploratory and modelling pass
in one notebook.

## What the notebook covers

`loan_proj1.ipynb`, 63 cells, worked through in order:

1. **The problem** — what is being predicted and why it matters
2. **Loading** the CSV and a first look at the raw data
3. **Missing values** — where the NaNs are, what they mean, and how each column is filled
4. **Encoding** — categorical columns converted to numeric
5. **Univariate analysis** — distribution shape per feature, and outliers in the numeric columns
6. **Bivariate analysis** — how each feature relates to approval
7. **Feature selection**
8. **Models** — LinearRegression, RandomForestRegressor and ExtraTreesClassifier, with
   resampling to correct the class imbalance
9. **Results** — what worked, what didn't, and why

## Stack

pandas · numpy · scikit-learn · matplotlib · seaborn · mlxtend

## Running it

The dataset CSV is not committed. Point the read cell in section 2.1 at your own copy of a
loan-approval dataset with the same columns, then run the notebook top to bottom.
