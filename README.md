# Project-2-Pluto-Academy
Second Machine Learning Project on Titanic Dataset From Kaggle

# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning. It includes data preprocessing, feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

The goal is to build an accurate predictive model while understanding which passenger characteristics had the greatest impact on survival.

---

## 🎯 Objectives

* Clean and preprocess the Titanic dataset.
* Handle missing values and encode categorical features.
* Perform feature engineering to improve model performance.
* Train and compare multiple machine learning models.
* Evaluate models using classification metrics.
* Identify the best-performing model.

---

## 📂 Dataset

The project uses the **Titanic Dataset** from Kaggle.

### Files

* `train.csv` – Training dataset
* `test.csv` – Test dataset
* `gender_submission.csv` – Sample submission file

### Features

* PassengerId
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked
* Survived (Target Variable)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns (`PassengerId`, `Ticket`, `Cabin`)
* Extracted passenger titles from the `Name` column
* Filled missing values in `Age` and `Embarked`
* Encoded categorical features
* Created new features such as **FamilySize** and **FarePerPerson**
* Applied **StandardScaler** to numerical features

---

## 🤖 Machine Learning Models

The following classification models were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

---

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

---

## 🏆 Best Model

The best-performing model was:

**K-Nearest Neighbors (K=19)**

### Performance

* Accuracy: **82.68%**
* F1-Score: **0.7704**
* ROC-AUC: **0.8567**

---

## 📈 Key Findings

* Feature engineering improved model performance.
* Passenger **Sex**, **Age**, **Pclass**, **Title**, and **FarePerPerson** were the most important features.
* Proper preprocessing and feature scaling helped improve prediction accuracy.
* KNN produced the best overall performance among the tested models.



## 📷 Visualizations

The notebook includes:

* Missing Value Analysis
* Correlation Heatmap
* Feature Importance
* Model Comparison
* Confusion Matrix

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data Cleaning
* Feature Engineering
* Data Preprocessing
* Feature Scaling
* Classification Algorithms
* Model Evaluation
* Machine Learning Workflow

---

## 👨‍💻 By:

**Krishna Jaiswal**

B.Tech CSE (AI & ML) Student

---
