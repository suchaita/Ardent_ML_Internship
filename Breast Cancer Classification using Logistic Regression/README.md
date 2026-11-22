# Breast Cancer Classification using Logistic Regression

## Project Overview
This project uses **Logistic Regression**, a supervised machine learning algorithm, to classify observations in the Breast Cancer Wisconsin dataset as **malignant** or **benign**.

It demonstrates a basic classification workflow, including data loading, train-test splitting, feature scaling, model training, prediction, and evaluation.

## Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Samples: 569
- Features: 30 numerical features
- Classes: malignant and benign

## Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Concepts
- Binary classification
- Logistic Regression
- Train-test split with stratification
- Feature scaling using `StandardScaler`
- Accuracy, classification report, and confusion matrix

## Workflow
1. Load the Breast Cancer Wisconsin dataset from Scikit-learn.
2. Explore the dataset and feature columns.
3. Split the data into training and test sets (80:20), using stratification.
4. Fit `StandardScaler` on the training data and transform both training and test data.
5. Train a Logistic Regression model.
6. Generate predictions for the test set.
7. Evaluate the model using accuracy, a classification report, and a confusion matrix.

## Results
- **Test accuracy: 98.25%**
- **Test samples: 114**
- **Confusion matrix:**
  ```text
  [[41  1]
   [ 1 71]]
  ```

The matrix uses the class order malignant, benign. The model correctly classified 41 malignant and 71 benign samples in this test split, with one misclassification in each class.

## Run the Notebook
1. Clone this repository.
2. Install the required packages: `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.
3. Open `Project_2.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the cells in order.

## Learning Outcomes
- Understanding binary classification
- Applying feature scaling without fitting on test data
- Training a Logistic Regression model
- Evaluating classification performance

## Author
**Suchaita Halder**

> **Disclaimer:** This is an educational machine learning project using a public dataset. It is not a medical device and must not be used for diagnosis or treatment decisions.
