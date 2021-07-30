# Flu-Shot-Learning-Predict-H1N1-and-Seasonal-Flu-Vaccines

This is a Machine Learning Competition held on DataDriven: https://www.drivendata.org/competitions/66/flu-shot-learning/
Competitors are required to predict whether a person has taken h1n1 vaccine or seasonal vaccine.

This repository documents all the steps taken to achieve a AUROC of 0.8618 which is ranked the top 5 percentile as of Aug 2021: https://github.com/chingfhen/Flu-Shot-Learning-Predict-H1N1-and-Seasonal-Flu-Vaccines/blob/main/RESULT.ipynb

In this project, many Machine Learning Models and Data Science Techniques were applied. Listing a few in chronological order: Data Exploration and preprocessing, random search hyperparameter tuning, Catboost, Advanced Categorical Encodings e.g WOEEncoders, Extreme Gradient Boosters, Stacking Generalization, Voting Classifier, Advanced NA imputation e.g 
IterativeImputer, Feature Engineering and Feature Selection, Lightgbm, Hyperparameter tuning with Optuna. 

Libraries used: sklearn, catboost, xgboost, lightgbm, category_encoders, seaborn, featuretools, Optuna. 

Each of notebooks have a summary and insights found, so they're easy to read and explore
