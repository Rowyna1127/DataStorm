# 🧠 Apoptotic Prediction using Machine Learning

This project uses biological experiment data to predict and classify apoptotic behavior of cells using machine learning techniques.

## 📦 Project Structure

* `machine.ipynb`: The main Jupyter notebook containing the code for:

  * Data loading from SQL Server
  * Preprocessing (factorization, scaling)
  * Regression & Classification
  * Visual evaluation (scatter plot, confusion matrix)

## 🔍 Objectives

* Predict `% Apoptotic` using regression models.
* Classify samples into high or low apoptotic using classification models.
* Analyze feature importance.
* Visualize model performance.

## 🧰 Tools & Libraries

* Python (Jupyter Notebook)
* pandas, numpy, seaborn, matplotlib
* scikit-learn (RandomForest, evaluation metrics)
* SQLAlchemy (for SQL Server access)

## 📊 Models Used

* **RandomForestRegressor**: for predicting continuous `% Apoptotic` values.
* **RandomForestClassifier**: for classifying samples into High or Low apoptosis.

## 📈 Results Summary

* **Regression**: Achieved reasonable prediction performance based on R² and MSE.
* **Classification**: Evaluated using accuracy, classification report, and confusion matrix.
* **Feature Importance**: Visualized to highlight key predictive features.

## 📌 Notes

* Data was retrieved directly from SQL Server using a secure connection.
* Features were factorized and standardized before training.
* Visualizations provide clarity on model behavior and outputs.

## 🚀 How to Run

1. Clone this repository.
2. Open `machine.ipynb` in Jupyter Notebook.
3. Ensure SQL Server is accessible.
4. Run cells in order.


