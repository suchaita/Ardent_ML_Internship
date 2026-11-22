# Breast Cancer Classification using Random Forest

## Overview
This project uses a **Random Forest Classifier** to predict whether a breast tumor is malignant or benign using the Breast Cancer Wisconsin dataset available in Scikit-learn.

The project demonstrates a supervised machine learning workflow, from preparing the dataset and training a classification model to evaluating its performance.

## Objectives
- Understand how Random Forest works for classification.
- Train a model using medical diagnostic features.
- Evaluate predictions using classification metrics.
- Explore hyperparameter tuning to improve model performance.

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
The project uses Scikit-learn's built-in Breast Cancer Wisconsin dataset.

- **Features:** 30 numerical diagnostic features.
- **Target classes:** Malignant and Benign.
- **Samples:** 569 observations.

## Workflow
1. Load the dataset.
2. Separate input features and target labels.
3. Split the data into training and testing sets.
4. Train a Random Forest Classifier.
5. Generate predictions on the test set.
6. Evaluate the model using accuracy, a confusion matrix and a classification report.
7. Apply GridSearchCV with cross-validation for hyperparameter tuning.

## Model
Random Forest is an ensemble learning algorithm that combines predictions from multiple decision trees to make a final classification.

## Results
The initial Random Forest model achieved a **test accuracy of 95.61%**.

The project also explores hyperparameter tuning using GridSearchCV and 5-fold cross-validation.

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```
3. Open the project notebook in Jupyter Notebook.
4. Run the cells sequentially.

## Key Learnings
- Supervised machine learning and classification.
- Random Forest and ensemble learning.
- Model evaluation using classification metrics.
- Hyperparameter tuning with GridSearchCV.

---

*This project was developed as part of my machine learning learning journey.*
