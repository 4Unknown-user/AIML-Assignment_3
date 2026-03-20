# AIML-Assignment_3

This repository contains the code and outputs for my Artificial Intelligence and Machine Learning (AIML) assignment. The assignment is divided into two distinct tasks focusing on unsupervised and supervised machine learning techniques.

## 📂 Repository Contents

This repository includes two separate Jupyter Notebooks containing the code, evaluation metrics, and visual outputs:

### 1. Customer Segmentation Using K-Means Clustering
* **File:** `CustomerSegmentation.ipynb`
* **Description:** This notebook demonstrates unsupervised learning by applying the K-Means clustering algorithm to segment customers based on synthetic data (e.g., Annual Income vs. Spending Score). 
* **Evaluation Metrics Used:**
    * **Silhouette Score:** Measures how similar an object is to its own cluster compared to other clusters.
    * **Davies-Bouldin Index:** Evaluates the average 'similarity' ratio of each cluster with its most similar cluster (lower is better).

### 2. Student Performance Prediction
* **File:** `Student_Performance_Prediction.ipynb`
* **Description:** This notebook demonstrates supervised learning by utilizing a Simple Linear Regression model to predict a student's exam score based on the number of hours they studied.
* **Evaluation Metrics Used:**
    * **Mean Squared Error (MSE) & Root Mean Squared Error (RMSE):** Measures the average squared difference between the estimated values and the actual value.
    * **Mean Absolute Error (MAE):** Measures the average magnitude of the errors in a set of predictions.
    * **R-squared ($R^2$) Score:** Represents the proportion of the variance for a dependent variable that's explained by an independent variable.

## 🛠️ Technologies & Libraries Used
* Python 3.x
* pandas (Data manipulation)
* NumPy (Numerical computations)
* Matplotlib (Data visualization)
* scikit-learn (Machine learning models and evaluation metrics)

## 🚀 How to View and Run
1. Click on either `CustomerSegmentation.ipynb` or `Student_Performance_Prediction.ipynb` above to view the code and visual outputs (scatter plots and regression lines) directly here on GitHub.
2. To run or interact with the code yourself, click the **"Open in Colab"** button located at the top of the notebook file when viewing it, or download the files and run them in your local Jupyter environment.
