# Support Vector Machine (SVM) – Social Network Ads

## Project Overview
This project implements Support Vector Machine (SVM) classification using the Social Network Ads dataset to predict whether a user will purchase a product based on their age and estimated salary.

## Objective
To understand and implement different types of SVM models for classification.

## Algorithm Used
Four SVM models are implemented:
- Polynomial SVM (Degree 2)
- Polynomial SVM (Degree 3)
- Linear SVM
- RBF SVM

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
**Social_Network_Ads.csv**

- Age
- Estimated Salary
- Purchased (Target Variable)

## Project Workflow
1. Import required libraries.
2. Load and explore the dataset.
3. Select input and target variables.
4. Split the dataset into training and testing sets.
5. Apply MinMaxScaler.
6. Train four SVM models.
7. Calculate model accuracy.
8. Visualize decision boundaries.

## Model Accuracy

| SVM Model | Accuracy |
|---|---:|
| Polynomial (Degree 2) | 89% |
| Polynomial (Degree 3) | 91% |
| Linear | 83% |
| RBF | 94% |

## Files Included
- `SVM_Social_Network.ipynb` – Jupyter Notebook containing the implementation.
- `Social_Network_Ads.csv` – Dataset used for training and testing.

## Project Type
College Practical / Machine Learning Classification Project
