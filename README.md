# Sonar Rock vs Mine Prediction

## Overview

This project develops a Machine Learning classification model capable of distinguishing between sonar signals reflected from rocks and those reflected from underwater mines. The model is trained using the Sonar dataset and learns patterns from sonar signal measurements to make accurate predictions on unseen data.

## Problem Statement

Underwater object detection is an important application in marine navigation and defense systems. The objective of this project is to build a classification model that can identify whether a sonar signal corresponds to a rock or a mine based on the signal's frequency response measurements.

## Dataset

The Sonar dataset consists of 208 observations and 60 numerical features representing energy measurements at different frequencies.

**Target Classes:**

* R → Rock
* M → Mine

Each record contains 60 sonar signal attributes and one target label.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-Learn

## Machine Learning Workflow

1. Data Collection and Loading
2. Data Exploration and Analysis
3. Data Preprocessing
4. Feature and Label Separation
5. Train-Test Data Splitting
6. Model Training using Logistic Regression
7. Performance Evaluation
8. Prediction on New Input Data

## Model

**Algorithm:** Logistic Regression

Logistic Regression was selected as a supervised classification algorithm to learn the relationship between sonar signal measurements and their corresponding classes.

## Evaluation

The dataset was divided into training and testing sets using stratified sampling to maintain class balance.

Performance was evaluated using classification accuracy on:

* Training Data
* Testing Data

## Results

The trained model successfully classifies sonar signals as either rocks or mines and demonstrates strong predictive performance on unseen data.

## Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing using Pandas
* Numerical computing with NumPy
* Train-Test Split methodology
* Logistic Regression for classification
* Model evaluation and accuracy analysis
* Building end-to-end Machine Learning pipelines

## Author

**N C Kartheek Reddy**

B.Tech Computer Science & Engineering
VIT-AP University
