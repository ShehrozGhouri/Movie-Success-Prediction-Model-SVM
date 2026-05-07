# 🎬 Movie Success Prediction using SVM

This project implements a **Support Vector Machine (SVM)** classifier to predict whether a movie will be a "Success" or a "Failure" based on its budget, runtime, critic scores, and audience ratings.

## 🚀 Overview
Predicting movie success is a complex task. This project explores the use of the **Radial Basis Function (RBF)** kernel in SVMs to find non-linear decision boundaries between successful and unsuccessful films.

## 🛠️ Key Features & Learning Milestones
* **Data Preprocessing:** Handled raw movie data, including feature selection and splitting.
* **Feature Scaling:** Implemented `StandardScaler` to normalize data, which is critical for distance-based algorithms like SVM.
* **Hyperparameter Tuning:** Optimized the model using specific `C` (Regularization) and `Gamma` (Kernel Coefficient) values.
* **Performance Metrics:** Evaluated the model using Accuracy, Mean Squared Error (MSE), and R2 Score.
* **Visualization:** Generated a Confusion Matrix heatmap using `Seaborn` to visualize model hits and misses.

## 📊 Dataset
The model was trained on a movie dataset containing the following features:
* `Budget_M`: Production budget in millions.
* `Runtime_Min`: Total duration of the movie.
* `Critic_Score`: Professional review score (0-100).
* `Rating`: User/Audience rating (1-10).
* **Target:** `Success` (1 for Hit, 0 for Failure).

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
    * `Scikit-Learn` (Machine Learning & Scaling)
    * `Matplotlib` & `Seaborn` (Visualization)

## 📈 Results
The model achieves high accuracy by effectively scaling features and utilizing the RBF kernel to handle the complex relationships between budget and critical acclaim.


## 📋 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/movie-success-svm.git](https://github.com/YOUR_USERNAME/movie-success-svm.git)
