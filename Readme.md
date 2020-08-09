# Sparkify Udacity Data Scientist Nano Degree Capstone Project:

## Index:
Dependencies
Project Motivation
Files Description
Results
Acknowledgements
## Dependencies
The following libraries are used to implement this project:
Pandas
PySpark
Spark
Matplotlib
Seaborn
## Project Motivation
The current project is a part of the Udacity's Data Scientist Nanodegree program analyzing the behaviour of users for an app called Sparkify to predict user churn. Sparkify is an app similar to Spotify and the dataset contains user behaviour log for the past few months. It contains some basic information about the users as well as information about a particular action they have taken. A user can have multiple actions which leads to multiple entries for a user, we can identify when a user churned through the action of account cancellation.
## Sparkify file  Description
Sparkify.ipynb is the main notebook where we do all the preprocessing, feature engineering and modelling.
## Results
Support Vector Machines, Random Forest and Gradient Boosted Trees are trained on the data set. Performance between the three models and Gradient Boosted Trees outperformed the rest by a large margin. The metric we used to evaluate performance is F-1 Score as that gives us a better representation of the model performance.
The final metrics for our Gradient Boosted Trees Classifier are as follows:
The accuracy is 0.866
The F-1 Score is 0.869
