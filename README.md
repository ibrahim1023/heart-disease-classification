# Heart Disease Classification
This project uses machine learning models to determine whether or not a patient has got heart disease.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Dataset](#dataset)
* [Features](#features)
* [Models](#models)
* [Graphs](#graphs)
* [Dependencies](#dependencies)

## General info
The project takes an in-depth approach in creating a heart disease classifier based on the data provided. The jupyter notebook carries the complete cycle for determining the best form of measures we can take in order to determine a good machine learning model. 

## Technologies
* Python
* Anaconda-Navigator 

## Setup
* Download Python: https://www.python.org/downloads/
* Download Anaconda-Navigator: https://www.anaconda.com/products/individual

## Dataset
The original data is from the Cleveland database from UCI Machine Learning Repository. It contains contains 76 attributes, but here only 14 attributes will be used. Attributes (also called features) are the variables what we'll use to predict our target variable.

### Features
The following are the features we'll use to predict our target variable (heart disease or no heart disease).
* Age
* Sex
* Chest pain type
* Resting resting blood pressure 
* Serum cholestoral in mg/dl
* Fasting blood sugar
* Resting electrocardiographic results
* Maximum heart rate achieved
* Exercise induced angina
* ST depression
* Slope of the peak exercise ST segment
* Number of major vessels (0-3) colored by flourosopy
* Thalium stress result
* **Target** - Have disease or not

![Data Preview](https://github.com/ibrahim1023/heart-disease-classification/blob/main/Images/table.png?raw=true "Data Preview")

## Models
Machine learning models discussed in this project

| Model | Accuracy (Highest achieved) |
| :---  |     :---:      |
| `LogisticRegression` | 88.5 %|
| `RandomForestClassifier` | 86.8 % |
| `KNN` | 75.4 % |

## Graphs 
Some graphs visualized using Matplotlib

![Heart Disease based on Gender](https://github.com/ibrahim1023/heart-disease-classification/blob/main/Images/gender.png?raw=true "Heart Disease based on Gender")

![Heart Disease in function of Age and Max Heart Rate](https://github.com/ibrahim1023/heart-disease-classification/blob/main/Images/age.png?raw=true "Heart Disease in function of Age and Max Heart Rate")

![Heart Disease Frequency Per Chest Pain Type](https://github.com/ibrahim1023/heart-disease-classification/blob/main/Images/cpt.png?raw=true "Heart Disease Frequency Per Chest Pain Type")

![Cross-Validated Metrics](https://github.com/ibrahim1023/heart-disease-classification/blob/main/Images/cvm.png?raw=true "Cross-Validated Metrics")

## Dependencies
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
