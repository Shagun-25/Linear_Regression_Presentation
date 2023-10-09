# Linear Regression- A Practical Perspective

## Introduction

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/cb83c857-75e9-455e-8b83-39841c9c7eaf)

Welcome to the Linear Regression Presentation! In this presentation, we will delve into the fascinating world of linear regression, a fundamental statistical technique with wide-ranging applications.

## Table of Contents
1. [Understanding Linear Regression](#understanding-linear-regression)
2. [Core Concepts of Linear Regression](#core-concepts-of-linear-regression)
3. [Applications of Linear Regression](#applications-of-linear-regression)
4. [Assumptions and Limitations in Linear Regression](#assumptions-and-limitations-in-linear-regression)
5. [Case Study: Failing Assumptions](#case-study-failing-assumptions)
6. [Model Diagnosis and Selection Steps](#model-diagnosis-and-selection-steps)
7. [Correlation does not imply causation](#correlation-does-not-imply-causation)
8. [Analogy of Linear Regression with Neural Network](#analogy-of-linear-regression-with-neural-network)

### Understanding Linear Regression

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/13231537-112d-480e-b410-60ffa188f0e9)

* Linear regression is a statistical method used to model the relationship between a dependent variable (Y) and one or more independent variables (X).
* It aims to find the best-fitting line (or hyperplane in multiple dimensions) that minimizes the sum of squared differences between observed and predicted values.
* It's widely used for prediction and understanding the influence of variables.

### Core Concepts of Linear Regression

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/9532f285-bfc9-4b85-940e-a64f43ad4383)
![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/af4d646b-1525-46b6-8cab-e5d8ffc0eebb)

* Dependent Variable (Y): The variable we are trying to predict or explain.
* Independent Variable(s) (X): The variable(s) used to make predictions.
* Regression Line: The line that best fits the data points, representing the relationship between X and Y.
* Residuals: The differences between observed and predicted values.

### Applications of Linear Regression

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/f49d93ae-8d9a-41da-b887-820d5935724f)

1. Impact Assessment (Hypothesis Testing)
* Helps determine if there's a meaningful connection between the independent and dependent variables.
* Example: Analyzing the impact of marketing spending on product sales to identify which factors significantly contribute to revenue.

2. Prediction and Forecasting
* Linear regression is a powerful tool for making predictions based on historical data. It provides a mathematical model that can be used to estimate future values of the dependent variable.
* Example: Predicting future housing prices based on features like square footage, number of bedrooms, and location.

### Assumptions and Limitations in Linear Regression

#### Assumptions

1. Linearity: The relationship between the independent and dependent variables is linear.
2. Independence: Observations in the dataset are independent of each other.
3. Homoscedasticity: The residuals (errors) have constant variance at every level of the independent variable(s).
4. Normality: The residuals of the model are normally distributed.

#### Limitations

1. All assumptions are limitations of linear regression.
2. May oversimplify real-world complex relationships.
3. Can be heavily influenced by outliers.
4. Assumes a constant slope across independent variables.

### Case Study: Failing Assumptions

#### Predicting Income with Age

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/d71d60df-d9f3-4b01-9d05-9cc2b2e59965)

* Linearity Assumption: Relationship between age and income isn't always linear. 
* Independence of Observations: Independence may fail with repeated observations from the same individual. 
* Homoscedasticity: Income variability might not be consistent across ages. 
* Normality of Residuals: Income data can be right-skewed. This might break the normality assumption.
* No Multicollinearity: Age could correlate with variables like education or experience, leading to multicollinearity issues.

### Model Diagnosis and Selection Steps

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/3092b2d9-749d-4c3f-ab68-573f944e0edf)

### Correlation does not imply causation

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/01e7be96-fecd-4726-9bb0-875983ed95f8)

While correlation measures the strength and direction of a linear relationship between two variables, causation determines whether changes in one variable are responsible for changes in another.

### Analogy of Linear Regression with Neural Network

While linear regression is a simple and interpretable model, a neural network's strength lies in its ability to learn complex relationships in data. It accomplishes this through multiple layers, non-linear activation functions, and optimization techniques. Linear regression can be seen as a special case of a neural network, which serves as a useful foundation for understanding more sophisticated machine learning models.

![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/03d8327b-4523-4fdc-8ade-0dbe82f04d06)

Neural Network is just a non-linear regression.
![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/b7e4c0aa-86a5-43cf-8dbc-4866808ddef4)
![image](https://github.com/Shagun-25/Linear_Regression_Presentation/assets/65088716/28a8c715-a325-498d-be8d-d0fe24d02743)

## Collaborators:
* Shagun Kala: www.github.com/Shagun-25
* Krit Poshakrishna: www.github.com/Kritpofrankss

## Conclusion
Thank you for exploring the world of linear regression with us! We hope this presentation provided valuable insights into this foundational statistical technique and its applications. Feel free to reach out for any further questions or discussions.

## References
1. https://en.m.wikipedia.org/wiki/File:UK_Income_by_Age_and_Gender.png
2. https://www.varsitytutors.com/common_core_high_school__statistics_and_probability-help/correlation-vs-causation-ccss-math-content-hss-id-c-9
3. https://joshuagoings.com/2020/05/05/neural-network/
