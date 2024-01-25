# machine_learning_project-supervised-learning

## Problem Statement

The purpose of this project to assess data provided by the National Institute of Diabetes and Digestive and Kidney diseases to understand which features are best in predicting whether a patient is at risk of diabetes. 

## Approach

The project approach focuses on four (4) key steps:

1. Exploratory Data Analysis - in this step the aim is to explore and understand what variables are available for their analysis and whether the data requires and cleaning or modification
2. Clean & Prepare Data - in this step data is cleaned to remove any outliers based on the EDA process and then standardized and balanced accordingly to ensure results are consistent and reliable
3. Execute Supervised Learning Models - goal is to conduct both a Logistic Regression and Random Forest classification for the model to assess which model is best based on a train/test split building and testing approach
4. Hyperparameter Tuning - Tune and optimize the hyperparameters for the Random Forest model to create final output

## Results

The result of this exercise was the creation of two models with the following accuracies:

Logistic Regression Accuracy: 0.8181

Random Forest Classification: 0.8585

The hyperparameters were tuned using a grid search function which resulted in the following hyperparameters and accuracy:

Max Depth: 20
Min Sample Leafs: 1
Min Sample Split: 2
N Estimators: 100

Refined Accuracy: 0.8787

## Conclusion

Based on the Supervised Learning project, here are the four (4) key takeaways I learned:

1. It is important to conduct good data cleaning and preparation. Overall, I made some limiting assumptions in the interest of time such as removing outliers, however, if more time was given I would explored replacing with mean, median, etc. to see how this affects the model
2. Order matters when scaling, balancing, and splitting data. At first I split the data into train/test sets and then applied scaling and balancing via oversampling which resulted in poor results. Scaling and oversampling the data and then splitting the model into train/test yielded more favourable results
3. Handling imbalanced data is important. Given more time I would have tested other approaches such as undersampling, SMOTE, etc.
4. Hyperparameter tuning is important but largely felt like a black box. It's unclear the trade-off between the base model and going to a max depth of 20 and whether this would result in overfitting. As mentioned, given more time I would have loved to pursue other models.
