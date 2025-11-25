# TASK08-
Task 8: House Price Prediction using Feature Engineering

Loaded the dataset (boston.csv) in Google Colab.

Checked missing values using df.isnull().sum().

Filled missing values:

Numeric → median

Categorical → “Missing”

Encoded categorical columns:

Small categories → Label Encoding

Others → One-Hot Encoding (pd.get_dummies())

Applied np.log1p() to fix skewed numeric columns.

Split data into train and test sets.

Trained a RandomForestRegressor model.

Calculated RMSE for model accuracy.

Printed feature importances using .feature_importances_.
