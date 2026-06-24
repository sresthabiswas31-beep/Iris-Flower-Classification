# IRIS Flower Classification using Logistic Regression and Random Forest

## Summer Internship Program 2026

**Institute of Data Engineering, Analytics and Science Foundation (IDEAS)**

**Created by:** Srestha Biswas
**Designation:** Summer Intern

---

## Project Overview

This project demonstrates the application of Machine Learning classification algorithms on the famous IRIS Flower Dataset. The objective is to classify Iris flowers into three species—Setosa, Versicolor, and Virginica—based on their sepal and petal measurements.

Two supervised learning algorithms were implemented and evaluated:

* Logistic Regression
* Random Forest Classifier

---

## Dataset Information

The IRIS dataset contains:

* 150 samples
* 4 numerical features

  * Sepal Length (cm)
  * Sepal Width (cm)
  * Petal Length (cm)
  * Petal Width (cm)
* 3 target classes

  * Iris Setosa
  * Iris Versicolor
  * Iris Virginica

The dataset was loaded using Scikit-Learn's built-in `load_iris()` function.

---

## Project Workflow

### 1. Import Libraries

* Pandas
* Scikit-Learn

### 2. Load and Explore Dataset

* Dataset description
* Feature information
* Class distribution

### 3. Data Preprocessing

* Created a Pandas DataFrame
* Added target labels
* Verified class balance

### 4. Feature and Target Separation

* Independent variables (X)
* Dependent variable (y)

### 5. Train-Test Split

* 80% Training Data
* 20% Testing Data
* Random State = 42

### 6. Model Training

#### Logistic Regression

* Trained using Scikit-Learn's LogisticRegression

#### Random Forest

* Trained using RandomForestClassifier
* Number of Trees = 100

### 7. Model Evaluation

* Accuracy Score
* Classification Report
* Precision
* Recall
* F1-Score

---

## Results

### Random Forest Classification Report

| Class | Precision | Recall | F1-Score |
| ----- | --------- | ------ | -------- |
| 0     | 1.00      | 1.00   | 1.00     |
| 1     | 1.00      | 1.00   | 1.00     |
| 2     | 1.00      | 1.00   | 1.00     |

**Overall Accuracy: 100%**

The Random Forest model successfully classified all test samples with perfect accuracy on the test dataset.

---

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* Jupyter Notebook

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Data preprocessing
* Exploratory data analysis
* Classification algorithms
* Model training and evaluation
* Machine Learning workflow using Python

---

## Acknowledgements

This project was completed as part of the **Summer Internship Program 2026** conducted by the **Institute of Data Engineering, Analytics and Science Foundation (IDEAS)**.

---

## Author

**Srestha Biswas**
B.Sc. Microbiology Student
Interested in Bioinformatics, Computational Biology, Machine Learning, and Data Science.
