# Credit-Card-Approval

## Introduction: This project involves solving a binary classification machine learning problem in the Banking and Finance industry.

## Aim: The aim of this project is to make accurate predictions from historical data in regards to whether a customer will get Approve for credit cared or Not.

## Methodology: While the fine details of the methodology followed in this project will be elaborated further in the relevant sections to come, it is to be mentioned that 16 standard machine learning models and 10 machine learning optimization have been implemented, compared, and contrasted to identify the best performing one.

### 01. Import CPU Python Libraries 
### 02. Function Helper
### 03. Import Dataset & Data Description
        - Import CSV File
        - Data Description
### 04. Data Understanding
        - Data Information
        - Data Summary Statistic
        - Data Variance
### 05. Select the Featurs
### 06. Data Pre-Processing
        - Drop Variables 
        - Convert Data Type
        - Missing Value
### 07. Exploratory Data Analysis
        - DV Visualization
        - Categorical IDV
        - Categorical IDV With DV
        - Numerical IDV
        - Numerical IDV With DV
### 08. Data Transformation
        - Minmax Scale
### 9. Feature Selection
        - Wrapper - Forward
### 10. Feature Engineering 
        - LableEncoder
### 11. Statistics
        - Correlations IDV with DV
        - Correlation between all the Variables
### 12. Resampling Data
        - SMOTE
### 13. Data Splitting 
### 14. Standard Machine Learning Models 
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Naive Bayes Classifiers
        -        Naive Bayes Classifier for Multivariate Bernoulli
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        XGBoost Classifiers
        -        Support Vector Machines Classifiers
        -        Linear Support Vector Classification
        -        Multilayer Perceptron Classifier
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
### 15. Optmization Machine Learning Models 
        - random grid for CPU Machine Learning Models
        - Hyperparameters for CPU Machine Learning Models
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        XGBoost Classifiers
        -        Support Vector Machines Classifiers
        -        Linear Support Vector Classification
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
### 16. Accuracy Score Summary 

## Results:

![stml](https://user-images.githubusercontent.com/82437810/175313606-e262015c-5d41-4daf-a6d1-d8e224191749.png)

![newplot](https://user-images.githubusercontent.com/82437810/175313663-0a2cb0d1-828a-41ba-8a78-93a026573655.png)


The results for the Standered Machine Learning it is showing Logistic Regression Classifier, Linear Support Vector Classification, Logistic Regression CV Classifier with accuracy (90.9, 90.2, and 90.2) respectively.


![opml](https://user-images.githubusercontent.com/82437810/175313582-8ce3efc3-3f36-41d3-949a-8585fde911bc.png)

![newplot](https://user-images.githubusercontent.com/82437810/175313592-6f147d31-da36-46d8-a8df-c3e6a2c72173.png)

The results for the Optimization Machine Learning it is showing Logistic Regression Classifier, Extra Trees Classifier, AdaBoost Classifier with accuracy (92.8, 92.2, and 91.5) respectively.

## Discussion:

![Screenshot 2022-06-23 205743](https://user-images.githubusercontent.com/82437810/175313546-288efab0-2d51-4ce8-bfeb-fbbad66eec3e.png)


The table above provides information about the Accuracy Standered CPU Models vs Accuracy Optimization CPU Models. as it is showing 'Logistic Regression Classifier', 'Random Forest Classifier', 'Linear Perceptron Classifier', 'Gradient Boosting Classifier', 'AdaBoost Classifier', 'Histogram-based Gradient Boosting Classification Tree' , 'Stochastic Gradient Descent Classifier', 'Extra Trees Classifier'the accuracy increased between 1% and 4% for each model.
