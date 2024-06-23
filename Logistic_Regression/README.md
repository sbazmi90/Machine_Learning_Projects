Machine Learning Projects: Logistic Regression

• This repository contains simple machine learning projects to demonstrate the use of logistic regression in predicting binary 

outcomes based on input data.


Table of Contents:

    • Project 1: Titanic Survival Prediction

        Introduction
        Data
        Features
        Model
        Usage

    • Project 2: Advertisement Click Prediction

        Introduction
        Data
        Features
        Model
        Usage

$\star$ Project 1: Titanic Survival Prediction

• Introduction

In this project, we aim to predict whether a passenger survived or did not survive the Titanic disaster. This is a 

classification problem, and we will use logistic regression to create a model that can predict the survival status based on 

various features of the passengers.

• Data

The dataset used for this project is a "semi-cleaned" version of the Titanic dataset. It contains information about the 

passengers aboard the Titanic.

• Features

The dataset includes the following columns:

    PassengerId: Unique ID for each passenger.

    Survived: Survival status (0 = No, 1 = Yes).

    Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).

    Name: Name of the passenger.

    Sex: Sex of the passenger.

    Age: Age of the passenger.

    SibSp: Number of siblings/spouses aboard the Titanic.

    Parch: Number of parents/children aboard the Titanic.

    Ticket: Ticket number.

    Fare: Passenger fare.

    Cabin: Cabin number.

    Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

• Model

A logistic regression model is used to predict the Survived status of passengers based on the other features in the dataset.

• Usage

    Load the dataset.

    Preprocess the data (handle missing values, encode categorical variables, etc.).

    Split the data into training and testing sets.

    Train the logistic regression model on the training data.

    Evaluate the model on the testing data.

    Use the model to predict survival status for new passengers.


$\star$ Project 2: Advertisement Click Prediction

• Introduction

In this project, we aim to predict whether an internet user will click on an advertisement on a company website. This is a 

binary classification problem, and we will use logistic regression to create a model that can predict the click behavior based 

on various features of the users.

• Data

The dataset used for this project is a fake advertising dataset. It contains information about internet users and their behavior.

• Features

The dataset includes the following columns:

    Daily Time Spent on Site: Consumer time on site in minutes.

    Age: Customer age in years.

    Area Income: Average income of the geographical area of the consumer.

    Daily Internet Usage: Average minutes a day consumer is on the internet.

    Ad Topic Line: Headline of the advertisement.

    City: City of the consumer.

    Male: Whether or not the consumer is male.

    Country: Country of the consumer.

    Timestamp: Time at which the consumer clicked on the ad or closed the window.

    Clicked on Ad: 0 or 1 indicating whether the user clicked on the ad.

• Model

A logistic regression model is used to predict the Clicked on Ad status based on the other features in the dataset.

• Usage

    Load the dataset.

    Preprocess the data (handle missing values, encode categorical variables, etc.).

    Split the data into training and testing sets.

    Train the logistic regression model on the training data.

    Evaluate the model on the testing data.

    Use the model to predict whether a user will click on an ad based on features.



