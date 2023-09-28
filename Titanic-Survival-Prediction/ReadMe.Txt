# Titanic Survival Prediction using K-Nearest Neighbors (KNN) Classification 🤖

## Project Overview 🌟
This Python code demonstrates K-Nearest Neighbors (KNN) classification, a machine-learning algorithm used for classification tasks.

## Dataset Description 📊
We are using the "tested.csv" dataset for this project. It contains information about passengers, including features like age, gender, ticket class, and more. Our goal is to predict whether a passenger survived (1) or not (0) based on this data.

## Code Overview 🖥️
This code performs the following steps:

### 1. Loading the Data 📁
The dataset is loaded from a CSV file using the Pandas library. This is the initial step in preparing the data for analysis.

### 2. Data Preprocessing 🧹
Data preprocessing is crucial for cleaning and preparing the data. We handle missing values and convert categorical variables into numerical form for machine learning.

### 3. Selecting Features and Target Variable 🎯
We specify which attributes (features) from the dataset will be used to make predictions and which one is the target variable to predict.

### 4. Splitting the Data 📊
The dataset is divided into two sets: training and testing data. The training data is used to build the model, while the testing data helps evaluate its performance.

### 5. Building and Training the KNN Model 🤓
A K-Nearest Neighbors (KNN) classifier is created. KNN works by finding the k-nearest data points in the training set to a given test data point and assigning the most common class among these neighbors to the test point. The choice of 'k' is a parameter you can customize. The formula for KNN is:

![KNN Formula](knn_formula.png)

### 6. Making Predictions 🎲
The trained KNN model is used to make predictions on both the training and testing data.

### 7. Evaluating the Model 📈
The code calculates and displays the accuracy score, which measures how well the model's predictions align with the actual outcomes, for both the training and testing datasets.

## Getting Started 🚀
1. Ensure you have Python and the required libraries (Pandas, Scikit-learn) installed.

2. Replace `"tested.csv"` with your dataset file in the code.

3. Customize the number of neighbors (`k`) based on your preferences.

4. Run the code to perform KNN classification and evaluate the model's accuracy.

## Resources 📖
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/index.html)

And finally Suiiiiiiiiiiiiiiiii ! 🚀🤖
