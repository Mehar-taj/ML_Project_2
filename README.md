# 🎗️ Breast Cancer Prediction using Machine Learning

<p align="center">
  <img src="banner.png" alt="Breast Cancer Prediction Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📖 Overview

As part of my ongoing journey in **Artificial Intelligence, Machine Learning, and Generative AI**, this project focuses on developing a **Breast Cancer Prediction System** using Machine Learning techniques. The objective is to classify breast tumors as **Benign (Non-Cancerous)** or **Malignant (Cancerous)** based on diagnostic measurements from the Breast Cancer Wisconsin Dataset.

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and deployment of a predictive system. By applying Logistic Regression, the model learns patterns within medical data and provides accurate predictions that can support healthcare decision-making.

---

## 🎯 Project Objectives

* Understand and explore real-world healthcare data.
* Perform data cleaning and preprocessing.
* Build a binary classification model using Logistic Regression.
* Evaluate model performance using accuracy metrics.
* Develop a predictive system for new patient data.
* Strengthen practical machine learning skills as part of my AI and Generative AI learning path.

---

## 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

**Records:** 569

**Features:** 30 Diagnostic Measurements

**Target Variable:**

| Diagnosis | Meaning                |
| --------- | ---------------------- |
| B         | Benign (Non-Cancerous) |
| M         | Malignant (Cancerous)  |

The dataset contains measurements computed from digitized images of breast mass cell nuclei, making it a popular benchmark dataset for binary classification tasks.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Logistic Regression
* Jupyter Notebook

---

## 🔄 Machine Learning Workflow

### 1️⃣ Data Collection

Loaded the Breast Cancer Wisconsin Dataset.

### 2️⃣ Data Preprocessing

* Removed unnecessary columns.
* Handled missing values.
* Converted categorical labels into numerical values.

### 3️⃣ Feature Selection

Separated input features and target labels.

### 4️⃣ Train-Test Split

Split the dataset into training and testing datasets.

### 5️⃣ Model Training

Trained a Logistic Regression classifier on the training data.

### 6️⃣ Model Evaluation

Evaluated performance using training and testing accuracy.

### 7️⃣ Prediction System

Built a predictive system capable of classifying new patient data.

---

## 🤖 Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. It estimates the probability of a data point belonging to a specific class and is widely used because of its simplicity, interpretability, and effectiveness.

---

## 📊 Results

| Metric            | Score  |
| ----------------- | ------ |
| Training Accuracy | 93.63% |
| Testing Accuracy  | 93.86% |

The model achieved strong performance on both training and testing datasets, indicating good generalization capability.

---

## 🎗️ Sample Prediction

### Input:

Patient diagnostic measurements (30 features)

### Output:

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
└── banner.png
```

---

## 🚀 Future Improvements

* Apply Feature Scaling using StandardScaler
* Compare Multiple Classification Algorithms
* Add Confusion Matrix and Classification Report
* Build an Interactive Streamlit Application
* Deploy the Model for Public Use

---

## 📚 Key Learnings

Through this project, I gained hands-on experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Binary Classification
* Logistic Regression
* Model Evaluation
* Building Predictive Systems
* Applying Machine Learning to Healthcare Data

---

## 🌱 My AI & Generative AI Journey

This project is part of my continuous learning journey in:

* Artificial Intelligence (AI)
* Machine Learning (ML)
* Data Science
* Generative AI

Each project helps me strengthen my understanding of real-world problem-solving using data and intelligent systems while building a strong foundation for advanced AI applications.

---

## 👩‍💻 Author

### Mehar-taj

Aspiring Data Scientist | Machine Learning Enthusiast | AI & Generative AI Learner

⭐ If you found this project interesting, feel free to explore my other projects and connect with me.
