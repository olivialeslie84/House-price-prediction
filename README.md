# House-price-prediction
Machine learning project using the Kaggle House Prices dataset to predict residential sale prices.

## Aim
Predict residential property sale prices using a range of numerical and categorical property features.

## Data
Data from the Kaggle House Prices - Advanced Regression Techniques competition: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

The dataset includes numerical and categorical property features used to predict 'SalePrice'.

## Approach
- Explored the data and investigated missing values
- Analysed the distribution of SalePrice
- Applied a log transformation to reduce skewness
- One-hot encoded categorical variables
- Compared Linear Regression and Random Forest models
- Evaluated models using RMSE on log-transformed sale prices

## Results
- Linear Regression validation RMSE: 0.1485
- Random Forest validation RMSE: 0.1478
- Kaggle score: 0.1493

Linear Regression was selected as the preferred model because the Random Forest improvement was marginal, while Linear Regression offered greater simplicity and interpretability.

## Tools
Python, pandas, NumPy, matplotlib, scikit-learn, VS Code.
