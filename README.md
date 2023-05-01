# Predicting Ad Clicks with Logistic Regression
This project involves building a logistic regression model to predict whether an internet user will click on an advertisement based on various features. The data set used in this project is a fake advertising data set that includes the following features:

Daily Time Spent on Site: consumer time on site in minutes
Age: customer age in years
Area Income: average income of the geographical area of consumer
Daily Internet Usage: average minutes a day consumer is on the internet
Ad Topic Line: headline of the advertisement
City: city of the consumer
Male: whether or not consumer was male
Country: country of the consumer
Timestamp: time at which consumer clicked on Ad or closed window
Clicked on Ad: binary variable indicating whether the consumer clicked on the advertisement (1) or not (0)
The goal of this project is to build a logistic regression model that can predict whether a user will click on an advertisement based on these features.

## Steps
The following steps were taken to build the logistic regression model:

Exploratory Data Analysis: Exploring the data set to understand the distribution of the features and the relationship between the features and the target variable (clicked on ad).
Data Preprocessing: Preprocessing the data set to handle missing values, encode categorical variables, and standardize the numerical features.
Feature Selection: Selecting the features that are most relevant to predicting whether a user will click on an advertisement.
Training the Model: Splitting the data set into training and testing sets, and training a logistic regression model on the training set.
Evaluating the Model: Evaluating the performance of the logistic regression model on the testing set using various metrics such as accuracy, precision, recall, and F1 score.

## Results
The model has an average precision, recall, and f1-score of 0.91. This suggests that the model has good performance in predicting both classes. However, since class 1 has a lower recall score, the model may have difficulty in predicting the positive class accurately. It is important to consider the nature of the problem and the cost associated with false positives and false negatives before deciding on a threshold for classification.

## Conclusion
In conclusion, this project involved building a logistic regression model to predict whether an internet user will click on an advertisement based on various features. The results of the project show that a logistic regression model can be used to predict ad clicks with reasonable accuracy.
