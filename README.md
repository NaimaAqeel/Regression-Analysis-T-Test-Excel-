

# Statistics Assignment – Iris Dataset Analysis

## Overview

This project demonstrates the application of **descriptive statistics, correlation analysis, hypothesis testing, and regression analysis** on the Iris dataset. The analysis provides insights into the patterns, relationships, and variations among different Iris species.

---

## 1. Descriptive Statistics

Descriptive statistics summarize and describe the main features of a dataset. Here, we analyze three Iris species: **Iris-Setosa, Iris-Versicolor, and Iris-Virginica**.

### Iris-Setosa

* **Mean:** Sepal Length = 5.006, Sepal Width = 3.418, Petal Length = 1.464, Petal Width = 0.244
* **Median:** Sepal Length = 5, Sepal Width = 3.4, Petal Length = 1.5, Petal Width = 0.2
* **Mode:** Sepal Length = 5.1, Sepal Width = 3.4, Petal Length = 1.5, Petal Width = 0.2
* **Standard Deviation:** Sepal Length = 0.352, Sepal Width = 0.381, Petal Length = 0.174, Petal Width = 0.107
* **Variance:** Sepal Length = 0.124, Sepal Width = 0.145, Petal Length = 0.030, Petal Width = 0.011

### Iris-Versicolor

* **Mean:** Sepal Length = 5.843, Sepal Width = 3.094, Petal Length = 2.862, Petal Width = 0.785
* **Median:** Sepal Length = 5.8, Sepal Width = 3.05, Petal Length = 2.45, Petal Width = 0.8
* **Mode:** Sepal Length = 5, Sepal Width = 3, Petal Length = 1.5, Petal Width = 0.2
* **Standard Deviation:** Sepal Length = 0.828, Sepal Width = 0.476, Petal Length = 1.449, Petal Width = 0.566
* **Variance:** Sepal Length = 0.686, Sepal Width = 0.227, Petal Length = 2.098, Petal Width = 0.321

> Observation: Petal length shows greater variability compared to other features, suggesting diversity within the Iris-Versicolor species.

### Iris-Virginica

* **Mean:** Sepal Length = 6.588, Sepal Width = 2.974, Petal Length = 5.552, Petal Width = 2.026
* **Median:** Sepal Length = 6.5, Sepal Width = 3, Petal Length = 5.55, Petal Width = 2
* **Mode:** Sepal Length = 5.9, Sepal Width = 3, Petal Length = 5.1, Petal Width = 1.8
* **Standard Deviation:** Sepal Length = 0.828, Sepal Width = 0.434, Petal Length = 1.764, Petal Width = 0.763
* **Variance:** Sepal Length = 0.686, Sepal Width = 0.188, Petal Length = 3.113, Petal Width = 0.582

---

## 2. Correlation Analysis

Correlation measures the strength and direction of the linear relationship between two variables:

* **Sepal Length vs Sepal Width:** -0.109 → weak negative relationship
* **Sepal Length vs Petal Length:** 0.872 → strong positive relationship
* **Petal Width vs Sepal Length:** 0.818 → strong positive relationship
* **Petal Length vs Sepal Width:** -0.421 → moderate negative relationship
* **Petal Width vs Sepal Width:** -0.357 → moderate negative relationship
* **Petal Length vs Petal Width:** 0.963 → strong positive relationship

> Observation: Petal length and petal width are strongly correlated, indicating that longer petals tend to be wider.

---

## 3. Hypothesis Testing

We conducted a **two-tailed t-test** to compare sepal length between **Iris-Setosa** and **Iris-Versicolor**:

* **Null Hypothesis (H0):** There is a significant difference in sepal length between the two species
* **Alternative Hypothesis (H1):** There is no significant difference in sepal length between the two species
* **p-value:** 0.4287 → **Fail to reject H0**

> Conclusion: There is no statistically significant difference in sepal length between Iris-Setosa and Iris-Versicolor.

---

## 4. Regression Analysis

Regression analysis estimates relationships between a dependent and independent variable.

**Model:** Effect of Sepal Width on Sepal Length

* **Equation:** Y = a + bX
* **R-squared:** 0.012 → Only \~1% of variation in sepal length explained by sepal width
* **Coefficient (b):** -0.209 → Negative relationship
* **p-value:** 0.183 → Not statistically significant

> Conclusion: Sepal width does not significantly affect sepal length in this dataset.

---

## 5. Summary

* Descriptive statistics provide insights into **average sizes, variability, and central tendencies** of Iris species.
* Correlation analysis identifies **strong and weak relationships** between features.
* Hypothesis testing suggests **no significant difference** in sepal length between certain species.
* Regression analysis shows **no significant predictive relationship** between sepal width and sepal length.

---


