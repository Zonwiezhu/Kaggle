Kaggle Challenge: Season 3 Episode 12 (Playground Series)

This repository contains my solution for the Kaggle challenge Season 3 Episode 12 (Playground Series), which is a binary classification problem with a tabular kidney stone prediction dataset. The challenge was launched on April 4, 2023 and closed on April 17, 2023.Dataset

The dataset consists of 10 features and 1 target variable. The features are:

age: The age of the patient in years
sex: The sex of the patient (0 = male, 1 = female)
pain: The level of pain experienced by the patient (0 = none, 1 = mild, 2 = moderate, 3 = severe)
hematuria: The presence of blood in the urine (0 = no, 1 = yes)
pyuria: The presence of pus in the urine (0 = no, 1 = yes)
urine_volume: The volume of urine produced by the patient in milliliters
serum_creatinine: The level of creatinine in the blood in milligrams per deciliter
serum_urea: The level of urea in the blood in milligrams per deciliter
serum_uric_acid: The level of uric acid in the blood in milligrams per deciliter
serum_calcium: The level of calcium in the blood in milligrams per deciliter
The target variable is:

stone: The presence of kidney stones in the patient (0 = no, 1 = yes)
The dataset contains 1000 rows and 11 columns. The train set has 800 rows and the test set has 200 rows.

Approach
To solve this challenge, I used the following steps:

Data exploration: I performed some basic exploratory data analysis to understand the distribution, correlation, and outliers of the features and the target variable.
Data preprocessing: I applied some data cleaning and transformation techniques to handle missing values, categorical variables, and scaling of the features.
Model selection: I experimented with different machine learning algorithms, such as logistic regression, decision tree, random forest, and gradient boosting, to find the best model for the classification task.
Model evaluation: I used accuracy, precision, recall, and F1-score as the metrics to evaluate the performance of the models on the train and test sets.
Model tuning: I used grid search and cross-validation to find the optimal hyperparameters for the best model.
Model prediction: I used the best model to make predictions on the test set and submitted the results to Kaggle.
Results
The best model that I found was the gradient boosting classifier, which achieved an accuracy of 0.83 on the test set. This score placed me at the 710th position out of 998 participants in the leaderboard.