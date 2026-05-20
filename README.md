# 🌸 Iris Species Classification using K-Nearest Neighbors (KNN)

A clean, production-ready implementation of the K-Nearest Neighbors (KNN) algorithm on the classic Iris dataset. This project demonstrates an end-to-end machine learning pipeline, including feature scaling, hyperparameter tuning, model evaluation, and error-rate visualization.


## 🚀 Key Features

* **Data Preprocessing & Scaling:** Implements standard normal feature scaling via `StandardScaler` to ensure uniform distance weighting during neighbor calculation.
* **Hyperparameter Optimization:** Includes a custom diagnostic loop computing dynamic cross-validation error rates across a range of $1 \le K \le 20$.
* **Robust Evaluation Metrics:** Evaluates final testing splits utilizing complete confusion matrices and detailed classification reports (Precision, Recall, F1-Score).
* **Matplotlib Error Curve Rendering:** Features inline graphical generation plotting the operational error rates to select the absolute mathematically optimal value for $K$.

## 🛠️ Tech Stack & Dependencies

* **Python 3.x**
* **Scikit-Learn** (Dataset acquisition, preprocessing, modeling, and evaluation)
* **Pandas** (Data manipulation and exploratory frame inspection)
* **Matplotlib** (Data visualization and optimization curves)

