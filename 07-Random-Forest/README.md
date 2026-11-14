# Random Forest Classification

## Project Overview
This project demonstrates Random Forest Classification using the Social Network Ads dataset.

## Objective
To predict whether a customer will purchase a product based on their age and estimated salary.

## Algorithm Used
- Random Forest Classifier
- GridSearchCV for hyperparameter tuning

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Dataset
**File:** `Social_Network_Ads.csv`

- Input Features: Age, Estimated Salary
- Target Variable: Purchased

## Steps Performed
1. Import required libraries.
2. Load and explore the dataset.
3. Select input and target variables.
4. Split the dataset into training and testing sets (75:25).
5. Train the Random Forest Classifier.
6. Check model scores.
7. Use GridSearchCV to find the best parameters.
8. Create and train the final model.
9. Predict purchase decisions for sample customer data.

## Best Parameters
- `max_depth = 3`
- `min_samples_leaf = 1`
- `n_estimators = 50`

## Files Included
- `Random_Forest_Social_Network.ipynb`
- `Social_Network_Ads.csv`

## Project Type
Machine Learning – Supervised Learning – Classification
