# House-price-prediction
Beginner machine learning project submitted to the Kaggle House Prices competition.

## Aim
Predict residential property sale prices using a range of numerical and categorical property features.

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
