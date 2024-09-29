### mushroom_classification

Predicting if the mushroom is edible or poisonous using machine learning(binary classification).<br />
In the data mostly there are categorical columns and only few numerical columns.<br />
Data Cleaning:<br />
- Some columns have lot of missing values, so filled those missing values with 'Unknown', instead of dropping them
- Transformed the columns by keeping only the valid values and replacing remaining values with 'Unknown'
Feature Engineering:<br />
- Used Label Encoding for converting categorical features into numerical features.
Models used:<br />
- Decision tree, random forest, XGBoost, LightGBM, CatBoost. Out of all these random forest performed better.
