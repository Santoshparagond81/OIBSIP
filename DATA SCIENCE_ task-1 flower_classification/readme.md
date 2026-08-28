# Iris Dataset Analysis

## 1. Import Modules

The required Python libraries are imported for data analysis and visualization.

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

## 2. Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to understand the dataset, its structure, features, and basic statistics.

The following steps are performed:

* Load the Iris dataset
* Display the first few rows
* Check the shape of the dataset
* Check data types
* Check for missing values
* Generate descriptive statistics

Example:

```python
iris.head()
iris.shape
iris.info()
iris.isnull().sum()
iris.describe()
```

## 3. Visualisations

Visualizations are created to understand the relationships and distributions of the Iris flower features.

### Pairplot

A pairplot is used to show relationships between the numerical features and distinguish the different Iris species.

```python
sns.pairplot(iris, hue="species")
plt.suptitle("Pairplot of Iris Features by Species", y=1.02)
plt.show()
```

### Box Plots

Box plots are used to compare the distribution of each feature across different Iris species.

```python
features = ['sepal_length', 'sepal_width',
            'petal_length', 'petal_width']

for feature in features:
    plt.figure(figsize=(7, 5))
    sns.boxplot(data=iris, x='species', y=feature)
    plt.title(f'{feature.title()} Distribution by Species')
    plt.show()
```

## 4. Training Dataset

The Iris dataset is used as the training dataset for analysis and machine learning.

The dataset contains four input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable is:

* Species

The dataset contains three species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## Conclusion

The Iris dataset was explored using Exploratory Data Analysis and visualizations. Pairplots and box plots help identify relationships, distributions, and differences between the three Iris species.
=======
# OIBSIP
>>>>>>> 765e1457c54c011dc7a50925a0e51d19c1effbd1
