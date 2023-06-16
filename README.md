# Rossmann Store Project

![Rossmann](https://github.com/PedroFerraresi/rossmann_sales/blob/main/img/rossmann.png?raw=true)

**Author**: Bruno Piato

**Date**: 2021-03-03

**Description**: This is a portfolio project I developed along with the "DS em Produção" classes of Comunidade Data Science. We used a drugstores dataset to predict sales for the next six weeks for each store using time series analysis and machine learning algorithms.

---
## 1. Introduction

Rossmann company operates over 4,000 drugstores around European countries such as Germany, Poland, Hungary, the Czech Republic, Turkey, Albania, Kosovo, Israel and Spain with a revenue of over €10 billion. 

In 2015 they published their data on Kaggle and created a [Kaggle competition](https://www.kaggle.com/c/rossmann-store-sales). The main goal was to predict the sales for the next 6 weeks once the CFO was intending to invest in improvements to the stores.

## 2. The approach
To achieve this, we used a combination of time series analysis and machine learning algorithms, following the steps inside the CRISP-DM methodology:

![CRISP-DS](https://raw.githubusercontent.com/brunopiato/RossmannProject/master/img/crisp_ds.png)

### The steps of CRISP-DM adapted to a Data Science project

#### 1. Problem definition
In this step we focus in understanding the problem and the needs of the stakeholders so we can better develop the solutuion.

#### 2. Business understanding
Here we deepen our business understanding so we can better assess the details and characteristics of the problem.

#### 3. Data collection
Acquiring the data needed to bring out a data solution is not always a simple task. Here the data needed to solve the problem was collected by Rossmann company and made available through Kaggle platform.

#### 4. Data cleaning
We need to make the dataset as cleaning and uniform as possible, to make it easier for the machine learning algorithms to work with. We need to standadize the features names, treat outliers and missing values, etc.

#### 5. Exploratory data analysis
The Exploratory data analysis (EDA) is the first step in the data science process. Here we can see and compare the features and understand its characteristics, such as maximum, minimum, mean, stadandard deviation, etc. We can also assess the relationship between the features in bivariate and multivariate analysis.

#### 6. Data preparation 
After the EDA step we are read to prepare the data for machine learning algorithms. We may need to transforme, standardize and rescale some features. We may need some feature engineering and feature selection as well to assure the best model performance possible.

#### 7. Model training
This is the core step of a Data Science project. It is in this step that the machine learning algorithms are trained and it is our job to evaluate our business problem and choose the best models to solve it.

#### 8. Model selection and evaluation
Once the models are trained, we need to evaluate them and choose the best one to move on to the next step. We can use a variety of evaluation metrics, such as accuracy, precision, recall, F1 score, etc depending on the type of problem we are aiming to solve.

#### 9. Deployment
In this final step we can deploy the best model to the production environment so the users benefit from it making the needed predictions to make their business decisions.

## 3. 