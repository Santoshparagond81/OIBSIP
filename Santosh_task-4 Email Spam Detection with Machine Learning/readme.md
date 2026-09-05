# 📧 Task 4 – Email Spam Detection with Machine Learning

## 📌 Project Overview

This project is about detecting whether an email/message is **Spam** or **Ham (legitimate)** using Machine Learning.

The system learns from previously labeled messages and then predicts whether a new message is spam or legitimate.

---

## 🎯 Objective

The main objective is to build a machine learning model that can:

- Identify spam messages
- Identify legitimate messages
- Reduce unwanted spam messages
- Evaluate how accurately the model detects spam

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK / Regular Expressions
- Matplotlib
- Seaborn
- Jupyter Notebook
- TF-IDF
- Machine Learning

---

## 📊 Dataset

The project uses a dataset containing messages labeled as either:

- **Spam** – unwanted or suspicious messages
- **Ham** – genuine and legitimate messages

The dataset is first loaded and analyzed to understand how many spam and ham messages are present.

---

## 🔄 Project Workflow

The project follows these main steps:

### 1. Load the Dataset

The email/message dataset is loaded into the notebook.

### 2. Understand the Data

The number of spam and legitimate messages is checked.

### 3. Clean the Text

The messages are converted into a suitable format by removing unnecessary characters, punctuation, and common words.

### 4. Convert Text into Numbers

TF-IDF is used to convert text messages into numerical values that a machine learning model can understand.

### 5. Split the Data

The dataset is divided into training data and testing data.

### 6. Train Machine Learning Models

Two different classification algorithms are trained to detect spam.

### 7. Make Predictions

The trained models predict whether messages are spam or ham.

### 8. Evaluate the Models

The models are evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

---

## 🤖 Machine Learning Models

Two classification algorithms are used in this project.

### Multinomial Naive Bayes

Multinomial Naive Bayes is commonly used for text classification. It is suitable for problems such as email spam detection.

### Logistic Regression / SVM

A second machine learning algorithm is used to compare its performance with Multinomial Naive Bayes.

---

## 📈 Model Evaluation

The models are evaluated using the following metrics:

- **Accuracy** – Shows how many predictions are correct overall.
- **Precision** – Shows how many messages predicted as spam are actually spam.
- **Recall** – Shows how many actual spam messages are successfully detected.
- **F1-Score** – Provides a balance between precision and recall.
- **Confusion Matrix** – Shows the correct and incorrect predictions.

---

## 🚨 Why Is Recall Important?

Recall is especially important in spam detection because we want to identify as many **actual spam messages as possible**.

If the model has low recall, some spam messages may be incorrectly classified as legitimate emails.

However, recall should also be balanced with precision so that genuine emails are not incorrectly marked as spam.

---

## ☁️ WordCloud

As an optional feature, WordClouds can be created to show the most commonly used words in:

- Spam messages
- Ham messages

This helps us visually understand the difference between spam and legitimate messages.

---

## ✅ Features

- Dataset loading and analysis
- Spam and ham classification
- Text preprocessing
- TF-IDF feature extraction
- Train/test splitting
- Multinomial Naive Bayes
- Second classification model
- Accuracy calculation
- Precision calculation
- Recall calculation
- F1-score calculation
- Confusion matrix
- Recall discussion
- Optional WordCloud visualization

---

## 🎓 Key Learning Outcomes

Through this project, we learn:

- How NLP can be used for text classification
- How to clean and prepare text data
- How TF-IDF converts text into numerical features
- How machine learning can detect spam
- How to train multiple classification models
- How to evaluate machine learning models
- Why precision and recall are important in classification problems

---

## 🏁 Conclusion

This project demonstrates how **Natural Language Processing and Machine Learning** can be used to detect spam messages.

By using text preprocessing, TF-IDF, and classification algorithms, the system can learn the patterns of spam and legitimate messages and classify new messages accordingly.

**Task 4 successfully demonstrates the practical application of Machine Learning in Email Spam Detection.**

---

## 👨‍💻 Author

**Santosh**

**Project:** Task 4 – Email Spam Detection with Machine Learning