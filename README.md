# Heavy-Equipment-Price-Prediction
"I built a machine learning model that predicts the selling price of heavy equipment (like bulldozers, excavators) using past sales data — things like the machine's age, how many hours it has been used, and its technical specifications."

# The Big Picture — Workflow
Load the data (train.csv, test.csv)
EDA (Exploratory Data Analysis) — look at the data, find patterns and problems
Preprocessing — clean the data (missing values, wrong values)
Feature Engineering — create new, more useful columns from existing ones
Encoding — convert text columns into numbers (models only understand numbers)
Model Training — train 3 different models (LightGBM, CatBoost, XGBoost)
Cross-Validation — test the model fairly, 5 times, on different data splits
Ensembling / Stacking — combine all 3 models into one final, stronger model
Submission — save final predictions to a CSV file

