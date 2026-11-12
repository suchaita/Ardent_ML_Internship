# Breast Cancer Classification using Logistic Regression

## 📌 Project Overview
This project demonstrates a **binary classification** problem using **Logistic Regression** to predict whether a breast tumor is **malignant** or **benign** based on medical features.

The project uses the **Breast Cancer Wisconsin Dataset** available in `scikit-learn` and includes:
- Data loading
- Feature scaling
- Model training
- Prediction
- Model evaluation
- Confusion matrix visualization

This project is suitable for **beginners in Machine Learning** who have basic knowledge of **NumPy and Matplotlib**.

---

## 📊 Dataset Information
- Source: `sklearn.datasets.load_breast_cancer`
- Number of samples: 569
- Number of features: 30
- Target classes:
  - `0` → Malignant
  - `1` → Benign

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🧠 Machine Learning Concepts Used
- Binary Classification
- Logistic Regression
- Train-Test Split
- Feature Scaling (StandardScaler)
- Model Evaluation
- Confusion Matrix

---


---

## ⚙️ Implementation Steps

### 1️⃣ Import Libraries
Essential libraries for numerical computation, visualization, and machine learning are imported.

### 2️⃣ Load Dataset
The Breast Cancer dataset is loaded directly from `scikit-learn`.

### 3️⃣ Split Data
The dataset is split into training and testing sets to evaluate model performance fairly.

### 4️⃣ Feature Scaling
`StandardScaler` is used to normalize features so that all values are on the same scale.

### 5️⃣ Model Training
A **Logistic Regression** model is trained using the scaled training data.

### 6️⃣ Prediction
The trained model predicts the class labels for the test dataset.

### 7️⃣ Model Evaluation
Model performance is evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

### 8️⃣ Confusion Matrix Visualization
The confusion matrix is visualized using `matplotlib` to clearly understand correct and incorrect predictions.

---

## 📈 Confusion Matrix Explanation
- **Rows** represent actual labels
- **Columns** represent predicted labels
- Diagonal values indicate correct predictions
- Off-diagonal values indicate misclassifications

---

## ✅ Results
The Logistic Regression model achieves **high accuracy**, showing that it is effective for this binary classification task.

---

## 🚀 How to Run the Project
1. Clone the repository
2. Open the notebook `Project_2.ipynb`
3. Run all cells sequentially

---

## 📌 Learning Outcome
By completing this project, you will understand:
- How classification problems work
- Why feature scaling is important
- How Logistic Regression makes predictions
- How to evaluate a machine learning model
- How to visualize results effectively

---

## 👤 Author
**Your Name Here**

---

## 📜 License
This project is for educational purposes.
--- 