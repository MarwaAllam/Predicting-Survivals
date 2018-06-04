# Predicting Survivals

The project main objective is to predict the survivals using many supervised learning techniques they are the following:
     Logistic Regression
     Decision Trees 
     Random Forest
     Support Vector Machine
     Support Vector Machine With Grid Search

All using Titanic dataset and this project is only 2 trials to compare between the different techniques in Python and each file contains the following file structure

# Trail 1

### Decision Trees and Random Forest Trail
  * Exploratory Data Analysis
      1. Plotting the data
  * Cleansing data
      1. Dealing with a missing data by the following
            Filled in some missing values 
            Dropped some few missing values
      2. Dealing with categorical features by the following
            Creating a dummy variables
  * Modeling
      1. Splitting the data into training and testing  
      2. Training the classification model 
      3. Building the Confusion Matrix

# Trail 2

What i changed trail 2 are the following:
  1. The way I organized the code and models
  2. Splitting the data into training, validation and testing
  3. Adding classifcation report on the training 
  4. Comparing between the models using the validation set
  5. Report the final F1 using the max F1 accorss all the models which was belong to Logistic Regression

The file structure are the following:

* Data Preparation and Exporatory Data Analysis

    1. Dealling with a missing data by the following
         Filled in some missing values using imputation
         Dropped few missing values
    2. Dealing with categorical features by the following
         Creating a dummy variables

* Modeling Phase    
  
    1. Split the test set into validation and testing
    2. Train the classification models (Logistic Regression, Dicision Trees, Random Forest, SVM and SVM with grid search) using the training data
    3. Confusion Matrix and Classification Report for training and validation sets
    4. Report the overall metric using max F1 
