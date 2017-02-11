# Employee Retention Churn Model

Classification Model for Employees leaving/staying at the company. The Human Resource Analytics dataset from Kaggle was used for this project. It has 15,000 employees in the dataset with 10 different features. The purpose of the project was to develop business insights as to why good employees leave and what can be done in order to retain them as well as develop a classification model that improves upon the baseline prediction.

# Data Cleaning

The dataset was cleaned by checking for null values, dummifying categorical variables (adding them to the original dataset and removing the original redunant ones), and normalizing the data using the MinMaxScaler.


# Exploratory Data Analysis (EDA)

Multiple graphs and plots were created in attempt to establish relationships in the dataset. In particular, several scatterplots were used to identify the features that were most important for determining which employees would stay/leave (Salary, Promotions, Hours worked, time spent at company).

![EC](/images/Satisfaction_Level vs Evaluation_Level.png)



# Predictive Modelling

Built the following models utilizing Scikit-Learn (Logistic Regression, KNN, Support Vector Machines, Bagging, Random Forest, AdaBoost and Gradient Boost). Random Forest in particular did especially well having approximately 98% accuracy using various measures in the confusion matrix.