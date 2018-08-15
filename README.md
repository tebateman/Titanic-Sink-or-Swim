# Titanic-Sink-or-Swim


This repo is a response to the classic Kaggle Titanic challenge - https://www.kaggle.com/c/titanic/data.

The objective of the challenge is to predict the passengers that survived and died based on the available variables (e.g. age, class).

The following approach achieved an accuracy score of 0.77033:

#Cleaning data - imputed age using median and embarked using mode
#One-hot encoding - dummy variables for all categorical variables
#Feature engineering - created age groups, salutation, famiy size features
#Model - trained random forest model (scikitlearn implementation)
