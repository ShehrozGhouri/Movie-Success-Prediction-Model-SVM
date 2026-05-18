# 🎬 Movie Success Prediction using SVM

This project implements a **Support Vector Machine (SVM)** classifier to predict whether a movie will be a "Success" or a "Failure" based on its budget, runtime, critic scores, and audience ratings.

## 🚀 Overview
Predicting movie success is a complex task due to the heavily mixed factors behind consumer behavior. This project explores the use of the **Radial Basis Function (RBF)** kernel in SVMs to map out non-linear decision boundaries between successful and unsuccessful films.

## 🛠️ Key Features & Learning Milestones
* **Data Preprocessing:** Handled raw movie data metadata, including feature selection and splitting.
* **Feature Scaling:** Implemented `StandardScaler` to normalize the data, which is critical for margin- and distance-based algorithms like SVM to prevent large budget numbers from biasing the boundary.
* **Hyperparameter Tuning:** Tuned the classifier by optimizing the regularization parameter `C` and the kernel coefficient `gamma`.
* **Performance Metrics:** Evaluated classification thresholds using Accuracy, Precision, Recall, and F1-Score metrics.
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
    * `Scikit-Learn` (Machine Learning, Scaling, and Validation)
    * `Matplotlib` & `Seaborn` (Visualization)

## 📈 Results
The model achieves high accuracy by effectively scaling features and utilizing the RBF kernel to handle the complex, intertwined relationships between budget size and critical acclaim.

---

## 📋 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ShehrozGhouri/Movie-Success-Prediction-Model-SVM.git](https://github.com/ShehrozGhouri/Movie-Success-Prediction-Model-SVM.git)
    cd Movie-Success-Prediction-Model-SVM
    ```

2.  **Install Required Dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

3.  **Run the project:**
    Execute your training python file or Jupyter notebook to preprocess the features and view the trained classification boundary performance.
