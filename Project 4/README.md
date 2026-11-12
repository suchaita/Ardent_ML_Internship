# Machine Learning Project: Breast Cancer Classification using Random Forest

## 📌 Overview
This project focuses on **classification using the Random Forest algorithm** on the **Breast Cancer dataset**.  
The goal is to predict whether a tumor is **malignant** or **benign** based on various medical features.

The project is implemented using **Python** in a **Jupyter Notebook** and follows a standard **Machine Learning workflow**, making it suitable for **students and academic evaluation**, while maintaining a **professional structure**.

---

## 🧠 Concepts Covered
- Supervised Learning
- Classification
- Random Forest Algorithm
- Decision Trees (ensemble concept)
- Train–Test Split
- Model Evaluation using Accuracy Score
- Working with real-world medical datasets

---

## 🛠 Tech Stack
- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-learn

---

---

## 📊 Dataset Description
The project uses the **Breast Cancer dataset** available in `scikit-learn`.

### Target Classes:
- **Malignant**
- **Benign**

### Features:
The dataset consists of multiple numerical features computed from digitized images of breast mass, such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness  
(and others)

---

## 🌲 Random Forest Classification
### Description
Random Forest is an **ensemble learning method** that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.

### Why Random Forest?
- Handles complex datasets well
- Reduces overfitting compared to single decision trees
- Works efficiently with high-dimensional data

---

## ⚙️ Workflow
1. Load the Breast Cancer dataset
2. Convert data into features and target labels
3. Split the dataset into training and testing sets
4. Train the Random Forest classifier
5. Predict outcomes on test data
6. Evaluate model performance using accuracy

```python
accuracy = model.score(X_test, y_test)
---

