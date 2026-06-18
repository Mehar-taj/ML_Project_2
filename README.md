# 🎗️ Breast Cancer Prediction using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📖 Project Overview

This project develops a **Breast Cancer Prediction System** using Machine Learning techniques to classify breast tumors as **Benign (Non-Cancerous)** or **Malignant (Cancerous)**. The model is trained using the Breast Cancer Wisconsin Dataset, which contains diagnostic measurements computed from digitized images of breast mass cell nuclei.

As part of my continuous journey in **Artificial Intelligence, Machine Learning, Data Science, and Generative AI**, this project demonstrates the complete machine learning workflow, including data preprocessing, feature selection, model training, evaluation, and prediction.

---

## 🎯 Project Objectives

* Analyze and understand a real-world healthcare dataset.
* Perform data cleaning and preprocessing.
* Build a binary classification model using Logistic Regression.
* Evaluate model performance using accuracy metrics.
* Develop a predictive system for classifying breast tumors.
* Strengthen practical machine learning skills through hands-on implementation.

---

## 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

**Number of Records:** 569

**Number of Features:** 30

**Target Variable:** Diagnosis

| Label | Meaning                |
| ----- | ---------------------- |
| B     | Benign (Non-Cancerous) |
| M     | Malignant (Cancerous)  |

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Logistic Regression
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection

* Loaded the Breast Cancer Wisconsin Dataset.

### 2. Data Exploration

* Examined dataset structure.
* Checked data types.
* Identified missing values.
* Reviewed feature statistics.

### 3. Data Preprocessing

* Removed unnecessary columns (`id`, `Unnamed: 32`).
* Converted diagnosis labels:

  * Malignant (M) → 1
  * Benign (B) → 0

### 4. Feature Selection

* Selected 30 diagnostic measurements as input features.
* Selected diagnosis as the target variable.

### 5. Train-Test Split

* Split data into training and testing datasets.
* Training Data: 80%
* Testing Data: 20%

### 6. Model Training

* Trained a Logistic Regression classifier using the training dataset.

### 7. Model Evaluation

* Calculated training accuracy.
* Calculated testing accuracy.

### 8. Prediction System

* Built a predictive system that accepts new patient measurements and predicts tumor diagnosis.

---

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for binary classification problems. It predicts the probability that a given input belongs to a particular class and is widely used due to its simplicity, interpretability, and effectiveness.

---

## 📊 Model Performance

| Metric            | Score  |
| ----------------- | ------ |
| Training Accuracy | 93.63% |
| Testing Accuracy  | 93.86% |

The model demonstrates strong performance and generalization capability on unseen data.

---

## 🎗️ Sample Prediction

### Input

Diagnostic measurements from a patient containing 30 features.

### Output

```python
Prediction: Malignant Tumor (Cancerous)
```

or

```python
Prediction: Benign Tumor (Non-Cancerous)
```

---

## 📁 Project Structure

```text
Breast-Cancer-Prediction/
│
├── Breast_Cancer_Prediction.ipynb
├── Breast_cancer_data.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

* Apply Feature Scaling using StandardScaler.
* Add Confusion Matrix Visualization.
* Generate Classification Report.
* Compare Multiple Machine Learning Algorithms.
* Build a Streamlit Web Application.
* Deploy the model for real-world use.

---

## 📚 Key Learnings

Through this project, I gained practical experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Selection
* Logistic Regression
* Model Evaluation
* Predictive System Development
* Healthcare Data Analysis

---

## 🌱 Learning Journey

This project is part of my ongoing learning journey in:

* Artificial Intelligence (AI)
* Machine Learning (ML)
* Data Science
* Generative AI

Each project helps me strengthen my understanding of real-world problem solving using data-driven approaches and intelligent systems.

---

## 👩‍💻 Author

### Mehar-taj

Aspiring Data Scientist | Machine Learning Enthusiast | AI & Generative AI Learner

GitHub: https://github.com/Mehar-taj

LinkedIn: https://www.linkedin.com/in/mehar-taj-a654102b6

---

⭐ If you found this project useful, consider giving it a star and exploring my other AI and Machine Learning projects.
