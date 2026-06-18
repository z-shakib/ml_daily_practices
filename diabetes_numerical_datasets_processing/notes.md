# Numerical dataset preprocessing for diabetes prediction.

## Dataset
The dataset contains patient health information such as glucose level, blood pressure, insulin, BMI, age, and outcome.

Target column:

* `Outcome`
* 0 = Non-Diabetic
* 1 = Diabetic

## What I Learned

This practice focused on handling numerical data before training a Machine Learning model.

## Main Steps

1. Loaded the diabetes dataset
2. Checked the first few rows using `head()`
3. Checked dataset size using `shape`
4. Used `describe()` to understand mean, standard deviation, minimum, maximum, and quartiles
5. Separated features and target
6. Standardized numerical features using `StandardScaler`
7. Split the dataset into training and testing data

## Key Concepts

### Standardization

Standardization converts numerical values into a similar scale.

It helps because different columns have different ranges, such as age, glucose, insulin, and BMI.

### Train-Test Split

The dataset is divided into two parts:

* Training data: used to teach the model
* Testing data: used to check model performance

## Key Learning

* Numerical data should be checked before model training
* `describe()` helps understand the data distribution
* Features and target must be separated
* Scaling helps models learn better
* Train-test split is needed to evaluate the model fairly

## Summary

Today I practiced basic numerical dataset handling using the diabetes dataset. I learned how to inspect data, separate input and output columns, standardize numerical features, and split the dataset for Machine Learning training and testing.
