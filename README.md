# Titanic-Survival-Prediction

This is a kaggle "getting started" data competition, that I have started working on. I got the dataset from kaggle website.
The data set consists of list of survived and non-survived passangers in the tragic Titanic accident. The goal is to apply machine 
learning tools to identify the passangers likely to survive such a shipwreck.

Data Exploration:
• I have dropped	Variables passengerId, Name, Ticket and cabin ( cabin has lot of missing values) from the training data as these variables would not be good predictors

Handling missing values:
• Embarked - Replaced with 'S' most occured type
• Age - replaced by random numbers selected from range ((mean-std.dev),(mean+std.dev))

Applied decision tree and randomforestclassifier algorithms from scikit-learn package.


