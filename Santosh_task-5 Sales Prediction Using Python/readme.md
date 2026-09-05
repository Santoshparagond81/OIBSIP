# 📊 Task 5 – Sales Prediction Using Python

## 📌 Project Overview

This project focuses on predicting product sales based on advertising spending across different media channels such as **TV, Radio, and Newspaper**.

A Machine Learning regression model is used to understand the relationship between advertising expenditure and sales and to predict sales based on advertising budgets.

---

## 🎯 Objective

The main objective is to build a machine learning model that can:

- Predict product sales
- Understand the relationship between advertising spend and sales
- Compare different regression models
- Identify which advertising channel has the highest impact on sales
- Evaluate the performance of the models

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Machine Learning

---

## 📊 Dataset

The project uses an advertising dataset containing information about spending on different advertising channels:

- **TV** – TV advertising expenditure
- **Radio** – Radio advertising expenditure
- **Newspaper** – Newspaper advertising expenditure
- **Sales** – Product sales

The dataset is analyzed to understand the relationship between advertising expenditure and sales.

---

## 🔄 Project Workflow

The project follows these main steps:

### 1. Load the Dataset

The advertising dataset is loaded into the Jupyter Notebook.

### 2. Explore the Data

The dataset is examined using:

- Null value checking
- Descriptive statistics
- Data inspection
- Pairplot visualization

### 3. Analyze Advertising Channels

Individual scatter plots are created to understand the relationship between:

- Sales and TV spending
- Sales and Radio spending
- Sales and Newspaper spending

### 4. Correlation Analysis

A correlation matrix and heatmap are used to understand the strength of relationships between advertising channels and sales.

### 5. Split the Data

The dataset is divided into training data and testing data.

### 6. Train a Linear Regression Model

Linear Regression is used as the baseline model to predict sales.

### 7. Train an Additional Model

Another regression model, such as Random Forest Regressor or Polynomial Regression, is trained and compared with Linear Regression.

### 8. Make Predictions

The trained models are used to predict sales for the test data.

### 9. Evaluate the Models

The models are evaluated using MAE, RMSE, and R² score.

### 10. Analyze Residuals

A residual plot is created for the best-performing model to check whether the prediction errors are randomly distributed or show a pattern.

---

## 🤖 Machine Learning Models

### Linear Regression

Linear Regression is used as the baseline model.

It helps understand the relationship between advertising expenditure and product sales.

### Random Forest Regressor / Polynomial Regression

An additional regression model is trained to compare its performance with Linear Regression.

The better-performing model is selected based on the evaluation metrics.

---

## 📈 Model Evaluation

The models are evaluated using the following metrics:

- **MAE (Mean Absolute Error)** – Measures the average absolute difference between actual and predicted sales.
- **RMSE (Root Mean Squared Error)** – Measures the prediction error while giving more importance to larger errors.
- **R² Score** – Shows how well the model explains the variation in sales.

A model with lower MAE and RMSE and a higher R² score generally indicates better performance.

---

## 📉 Residual Analysis

A residual plot is created for the best model.

Residuals represent the difference between the actual sales and the predicted sales.

The residual plot helps determine whether the errors are randomly distributed or whether there is a systematic pattern in the predictions.

---

## 📺 Which Advertising Channel Has the Highest Impact?

The impact of each advertising channel is analyzed using model coefficients or feature importance.

The analysis helps determine whether **TV, Radio, or Newspaper advertising** has the strongest relationship with sales.

The channel with the highest coefficient or feature importance is considered to have the greatest impact according to the selected model.

---

## 📊 Visualizations

The project includes the following visualizations:

- Pairplot
- Sales vs. TV scatter plot
- Sales vs. Radio scatter plot
- Sales vs. Newspaper scatter plot
- Correlation heatmap
- Residual plot

These visualizations help understand the relationships between advertising expenditure and sales.

---

## ✅ Features

- Dataset loading and analysis
- Null value checking
- Descriptive statistics
- Pairplot visualization
- TV vs. Sales analysis
- Radio vs. Sales analysis
- Newspaper vs. Sales analysis
- Correlation matrix
- Correlation heatmap
- Train/test split
- Linear Regression model
- Additional regression model
- Sales prediction
- MAE evaluation
- RMSE evaluation
- R² score evaluation
- Residual analysis
- Advertising channel impact analysis

---

## 🎓 Key Learning Outcomes

Through this project, we learn:

- How regression problems work
- How to explore and analyze datasets
- How advertising spending affects sales
- How to visualize relationships between variables
- How to build a Linear Regression model
- How to train and compare different regression models
- How to evaluate regression models
- How to analyze residuals
- How to identify important features

---

## 🏁 Conclusion

This project demonstrates how **Machine Learning can be used to predict product sales based on advertising expenditure**.

By analyzing TV, Radio, and Newspaper advertising spending, regression models can learn the relationship between advertising budgets and sales.

The project also compares different models and evaluates their performance using MAE, RMSE, and R² score.

Finally, feature coefficients or importance are used to determine which advertising channel has the highest impact on sales.

---

## 👨‍💻 Author

**Santosh**

**Project:** Task 5 – Sales Prediction Using Python