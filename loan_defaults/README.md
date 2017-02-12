# Classifying good vs bad loans

The purpose of this project was to identify which loans are good (will not default) vs which ones are bad (will default) as well as develop business insights from the analysis. The original dataset from Lending Club had over 400,000 people in it.

# Data Cleaning 

The data cleaning steps involved checking for null values, dummifying the categorical variables and adding the new dummified features to the original dataset while removing the redundant ones. This was followed by normalizing the data and selecting a random sample of it.

# Exploratory Data Analysis (EDA)

We next create several various 3-dimensional scatterplots to establish the relationship between several features in the dataset and extract business value from them.

# Predictive Modeling

Created a logistic regression model using both the Bayesian approach and the traditional frequentist approach in scikit learn and conducted various accuracy tests particularly, cross validation and various metrics from the confusion matrix.