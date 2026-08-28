# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

This project focuses on **classifying Iris flowers into different species using Machine Learning**.

The Iris dataset contains measurements of iris flowers, and the objective is to build a machine learning model that can predict the species of an iris flower based on its features.

The project includes **Exploratory Data Analysis (EDA), data preprocessing, model training, prediction, and model evaluation**.

---

## 🎯 Objective

The main objective of this project is to:

* Understand the Iris dataset
* Perform Exploratory Data Analysis (EDA)
* Analyze relationships between different features
* Prepare the dataset for machine learning
* Train a classification model
* Make predictions on unseen data
* Evaluate the performance of the model

---

## 📊 Dataset

The **Iris dataset** contains **150 observations** of iris flowers belonging to three different species.

### Species

* Iris Setosa
* Iris Versicolor
* Iris Virginica

### Features

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |
| Species      | Target variable     |

The dataset contains:

* **150 rows**
* **4 input features**
* **1 target variable**
* **3 flower classes**

---

## 🔍 Exploratory Data Analysis

The following EDA techniques were performed:

* Checking dataset shape
* Checking data types
* Checking for missing/null values
* Generating descriptive statistics
* Examining class distribution
* Analyzing relationships between features
* Visualizing the dataset

Example checks:

```python
df.shape
df.dtypes
df.isnull().sum()
df.describe()
```

---

## 🤖 Machine Learning Model

### Logistic Regression

**Logistic Regression** was used as a classification algorithm to predict the species of Iris flowers.

The dataset was divided into:

* Training data
* Testing data

The model was trained using the training dataset and evaluated using the testing dataset.

---

## 📈 Model Evaluation

The model was evaluated using the following metrics:

### 1. Accuracy

Accuracy measures the percentage of predictions that were correctly classified.

### 2. Confusion Matrix

The confusion matrix shows the number of correct and incorrect predictions for each Iris species.

### 3. Classification Report

The classification report provides:

* Precision
* Recall
* F1-score
* Support

Example:

```python
from sklearn.metrics import confusion_matrix, classification_report

confusion_matrix(y_test, y_pred)

print(classification_report(y_test, y_pred))
```

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 📂 Project Structure

```text
Iris-Dataset/
│
├── Iris_Classification.ipynb
├── README.md
└── dataset/
    └── iris.csv
```

---

## ▶️ How to Run the Project

### Step 1: Clone the repository

```bash
git clone https://github.com/Santoshparagond81/OIBSIP.git
```

### Step 2: Navigate to the project folder

```bash
cd OIBSIP
```

Then navigate to the Iris project folder:

```bash
cd Iris-Dataset
```

### Step 3: Install required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Iris_Classification.ipynb
```

Run the cells sequentially to reproduce the analysis and results.

---

## 📌 Results

The Logistic Regression model was trained successfully to classify the three Iris flower species.

The performance of the model was evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-score

The evaluation results demonstrate the effectiveness of Logistic Regression for the Iris flower classification problem.

---

## 💡 Key Learnings

Through this project, I learned:

* How to load and inspect a dataset
* How to perform EDA
* How to identify missing values
* How to analyze statistical information
* How to split data into training and testing sets
* How to train a Logistic Regression model
* How to make predictions
* How to evaluate a classification model
* How to interpret a confusion matrix
* How to understand precision, recall, and F1-score

---

## 🚀 Future Improvements

The project can be further improved by:

* Comparing multiple classification algorithms
* Performing hyperparameter tuning
* Using cross-validation
* Creating an interactive prediction interface
* Deploying the model as a web application

---

## 👨‍💻 Author

**Santosh Paragond**

GitHub:
https://github.com/Santoshparagond81

---

## ⭐ Acknowledgement

This project was completed as part of my learning and practical experience in **Machine Learning and Data Science**.

If you found this project useful, consider giving the repository a ⭐.
