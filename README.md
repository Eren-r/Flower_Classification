# 🌸 Iris Flower Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)


## 📌 Project Overview

This project implements a Machine Learning-based classification system to identify Iris flower species using their physical characteristics. The model is trained on the famous Iris dataset and compares the performance of two supervised learning algorithms:

* Logistic Regression
* K-Nearest Neighbors (KNN)

The project also includes Exploratory Data Analysis (EDA), data visualization, model training, performance evaluation, and comparative analysis.

---

## 🎯 Problem Statement

Accurately classifying flower species based on measurable features is a fundamental machine learning classification problem.

The objective of this project is to build predictive models capable of classifying Iris flowers into:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

using:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 📂 Dataset Information

The Iris dataset is one of the most widely used datasets in Machine Learning and Pattern Recognition.

### Features

| Feature      | Description          |
| ------------ | -------------------- |
| Sepal Length | Length of Sepal (cm) |
| Sepal Width  | Width of Sepal (cm)  |
| Petal Length | Length of Petal (cm) |
| Petal Width  | Width of Petal (cm)  |

### Target Variable

Species of Iris Flower

* Setosa
* Versicolor
* Virginica

Dataset Size:

* 150 Samples
* 4 Features
* 3 Classes

---

## 🚀 Project Workflow

### 1. Data Loading

* Import dataset using Pandas
* Inspect structure and features

### 2. Data Preprocessing

* Encode categorical target labels
* Prepare feature matrix and target vector

### 3. Exploratory Data Analysis (EDA)

* Pairplot Visualization
* Feature Relationship Analysis
* Class Distribution Inspection

### 4. Model Development

#### Logistic Regression

A linear classification algorithm used for multiclass classification.

#### K-Nearest Neighbors (KNN)

A distance-based classification algorithm that predicts labels using the nearest neighboring data points.

### 5. Model Evaluation

Performance metrics:

* Accuracy Score
* Classification Report
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 6. Comparative Analysis

Both models are compared visually using:

* Accuracy Comparison Bar Chart
* Confusion Matrix Visualization

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

### Machine Learning Techniques

* Classification
* Logistic Regression
* K-Nearest Neighbors
* Label Encoding
* Model Evaluation

---

## 📊 Data Visualization

The project includes several visualizations:

### Pairplot Analysis

Visual representation of relationships between all flower features.

### Confusion Matrix

Provides insight into classification performance.

### Model Comparison Chart

Compares accuracy scores of Logistic Regression and KNN.

---

## 📈 Results

The models achieve high classification accuracy on the Iris dataset.

Typical Performance:

| Model               | Accuracy    |
| ------------------- | ----------- |
| Logistic Regression | ~95% - 100% |
| KNN Classifier      | ~95% - 100% |

Both algorithms demonstrate excellent performance due to the well-separated nature of the Iris dataset.

---

## 🏗️ Project Structure

```text
Iris-Flower-Classification/
│
├── Iris.csv
├── iris_classification.py
├── screenshots/
│   ├── pairplot.png
│   ├── confusion_matrix_lr.png
│   ├── confusion_matrix_knn.png
│   └── accuracy_comparison.png
│
├── requirements.txt
├── README.md
└── LICENSE
```


## 📚 Learning Outcomes

This project demonstrates practical understanding of:

* Machine Learning Classification
* Data Preprocessing
* Feature Analysis
* Exploratory Data Analysis
* Model Evaluation Techniques
* Data Visualization
* Comparative Model Analysis

---

## 🔮 Future Enhancements

* Hyperparameter Tuning
* Cross Validation
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* Streamlit Web Application
* Model Deployment

---

## 👨‍💻 Author

Eren

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer

Focused on building data-driven solutions, predictive models, and AI-powered applications.

---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ and exploring other projects in my Data Science & AI portfolio.

