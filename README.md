# Tourism_Triad
This repository contains a Jupyter Notebook file that analyzes event feedback data using machine learning techniques. The analysis is performed on a dataset named "eventfeedbackcleanest.csv" which is located in the "Resources" folder.

## Prerequisites
Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-Learn

## Getting Started
Clone this repository on your computer.
Install the required packages by running pip install -r requirements.txt in your command prompt or terminal.
Start Jupyter Notebook and open the "event-feedback-analysis.ipynb" file.
Run the cells in the notebook to reproduce the analysis.

## Contents
The analysis includes the following steps:

1. Loading the data from the CSV file.
2. Cleaning the data by dropping missing values and unnecessary columns.
3.Performing exploratory data analysis by visualizing the data using scatter plots and histograms.
4. Preprocessing the data by scaling it using the StandardScaler.
5. Splitting the data into training and testing sets.
6. Building a Bagging Classifier model using Decision Tree Classifier as the base estimator.
7. Evaluating the model using various metrics, such as accuracy, confusion matrix, and classification report.
8. Visualizing the decision tree of the base estimator.

## Dataset

The dataset used in this analysis contains feedback from attendees of various events held in a city. It includes the ratings for different aspects of the event, such as the overall value of the city, the ease of doing business, cleanliness, and entertainment/attractions, among others. The goal of the analysis is to predict whether an attendee would rebook for a future event based on these ratings.

## Results

The Bagging Classifier model achieved an accuracy of approximately 80% on the test set, which indicates that the model is reasonably good at predicting whether an attendee would rebook for a future event. The confusion matrix and classification report also show that the model has a good balance between precision and recall for both classes. The decision tree of the base estimator provides insight into the factors that contribute the most to the prediction of whether an attendee would rebook.
