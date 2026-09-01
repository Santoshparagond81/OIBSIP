# 🚗 Car Price Prediction with Machine Learning

## 📌 Project Overview

This project focuses on predicting the **selling price of used cars** using Machine Learning regression techniques.

The model predicts the selling price based on different features such as **car brand, car age, present price, kilometers driven, fuel type, seller type, transmission, and previous ownership**.

The project covers the complete Machine Learning workflow, including data cleaning, feature engineering, exploratory data analysis, categorical encoding, model training, evaluation, and feature importance analysis.

---

## 🎯 Objective

The main objective of this project is to build a regression model that can accurately predict the **selling price of a used car** based on its available features.

The project also compares multiple regression algorithms to identify the model that provides the best prediction performance.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook** – Development environment

---

## 📂 Dataset

The project uses a used-car dataset containing information about cars and their selling prices.

### Important Features

| Feature       | Description                       |
| ------------- | --------------------------------- |
| Car_Name      | Name of the car                   |
| Year          | Manufacturing year                |
| Selling_Price | Selling price of the car (Target) |
| Present_Price | Current/ex-showroom price         |
| Kms_Driven    | Kilometers driven                 |
| Fuel_Type     | Type of fuel used                 |
| Seller_Type   | Type of seller                    |
| Transmission  | Transmission type                 |
| Owner         | Number of previous owners         |

---

## 🧹 Data Cleaning

The dataset was checked and cleaned before applying Machine Learning algorithms.

The following data-cleaning steps were performed:

* Checked for missing/null values
* Removed duplicate records
* Checked data types
* Identified inconsistent categorical values
* Standardized categorical values where required
* Verified the dataset after cleaning

---

## ⚙️ Feature Engineering

Feature engineering was performed to create useful information from the existing dataset.

### 1. Car Age

The manufacturing year was converted into **car age**.

**Car Age = Current Year − Manufacturing Year**

This helps the model understand how the age of a vehicle affects its selling price.

### 2. Brand Extraction

The brand was extracted from the `Car_Name` column.

For example:

* Toyota Corolla → Toyota
* Honda City → Honda
* Maruti Swift → Maruti

This creates a separate **Brand** feature that can be used by the Machine Learning models.

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the relationships and patterns in the dataset.

### Visualizations Included

#### Selling Price Distribution

A distribution plot was created to understand how used-car selling prices are distributed.

#### Selling Price vs Fuel Type

A box plot was used to compare selling prices across different fuel types such as:

* Petrol
* Diesel
* CNG

#### Selling Price vs Car Age

A scatter plot was created to analyze the relationship between car age and selling price.

The analysis helps identify whether older cars generally have lower selling prices.

---

## 🔤 Encoding Categorical Variables

Machine Learning models require numerical input, so categorical variables were converted into numerical form.

Categorical features such as:

* Brand
* Fuel Type
* Seller Type
* Transmission

were encoded using appropriate encoding techniques such as **One-Hot Encoding**.

---

## 🔥 Feature Correlation Analysis

A correlation heatmap was created to understand the relationship between numerical features.

The heatmap helps identify:

* Strong positive correlations
* Strong negative correlations
* Weak correlations
* Features that may have a significant relationship with selling price

---

## ✂️ Train/Test Split

The dataset was divided into training and testing sets.

* **90%** of the data was used for training
* **10%** of the data was used for testing

The training data was used to build the models, while the testing data was used to evaluate their performance on unseen data.

---

## 🤖 Machine Learning Models

At least two regression models were trained and compared.

### 1. Linear Regression

Linear Regression was used as a baseline regression model to predict the selling price based on the selected features.

### 2. Random Forest Regressor

Random Forest Regressor was used to capture more complex relationships between the car features and selling price.

The performance of both models was compared to determine the better-performing model.

---

## 📏 Model Evaluation

The trained models were evaluated using three important regression metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between the actual and predicted prices.

**Lower MAE is better.**

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

**Lower RMSE is better.**

### R² Score

Measures how well the model explains the variation in selling prices.

**Higher R² is better.**

### Model Comparison

| Model                   | MAE | RMSE | R² Score |
| ----------------------- | --: | ---: | -------: |
| Linear Regression       |   — |    — |        — |
| Random Forest Regressor |   — |    — |        — |

The values in the table can be updated with the actual results obtained from the Jupyter Notebook.

---

## 📈 Feature Importance

Feature importance was analyzed for the best-performing model.

The feature importance chart shows which features have the greatest influence on the model's predictions.

This helps understand which factors contribute most to the predicted selling price.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Categorical Encoding
   ↓
Correlation Analysis
   ↓
Train/Test Split
   ↓
Train Regression Models
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Feature Importance
   ↓
Best Performing Model
```

---

## 📁 Project Structure

```text
Car-Price-Prediction/
│
├── Car_Price_Prediction.ipynb
├── car_data.csv
├── README.md
└── visualizations/
```

---

## ✅ Feature Checklist

* [x] Downloaded a suitable used-car dataset
* [x] Checked and cleaned the dataset
* [x] Handled null values
* [x] Removed duplicate records
* [x] Addressed inconsistent categorical values
* [x] Calculated car age
* [x] Extracted car brand
* [x] Performed Exploratory Data Analysis
* [x] Created selling-price distribution
* [x] Created price vs fuel-type box plot
* [x] Created price vs car-age scatter plot
* [x] Encoded categorical variables
* [x] Created feature correlation heatmap
* [x] Performed train/test split
* [x] Trained at least two regression models
* [x] Evaluated models using MAE, RMSE and R²
* [x] Compared model performance
* [x] Created feature importance chart for the best model

---

## 🎯 Conclusion

This project demonstrates the complete process of building a **used-car price prediction system using Machine Learning**.

Through data cleaning, feature engineering, visualization, encoding, model training, and evaluation, different regression models were compared to identify the model most suitable for predicting used-car selling prices.

The project also provides insights into which car features have the greatest influence on selling price.

---

## 👨‍💻 Author

**Santosh Paragond**

### Project

**Car Price Prediction with Machine Learning**

### Task

**Task 3 – Machine Learning Regression Project**
