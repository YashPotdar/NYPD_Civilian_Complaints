# NYPD Civilian Complaints

This collection of projects examines a dataset that contains information about complaints made against the New York Police Department (NYPD) to the Civilian Complaint Review Board. The dataset has 33,358 individual civilian complaints made in New York City ranging from September 1985 to January 2020. The dataset is used in the project to generate insights on police misconduct on the different minority communities in New York.

I worked on these projects with Kenneth Nguyen, a fellow Data Science major at UC San Diego.

## nypd_permutation_test.ipynb
**Goal**: To determine whether complaints made by Black individuals have a varying degree of success than complaints made by non-Black individuals

This project has three focuses:
1. Data cleaning process and exploratory data analysis (EDA)
2. Assessment of Missingness of Data
3. Permutation test

## nypd_classification_model.ipynb
**Goal**: To develop a classification model which predicts whether a case a civilian initiated was substantiated or not.
The classification algorithm has a Baseline model that uses 12 features in order to compare it to the model with engineered features to determine an improvement. We then engineered four features and compared the F-1 score to the baseline score. Finally, to evaluate the fairness and ethical implications of the machine learning model, we conducted a permutation test to compare the true positive rate for complaints made by black and non-black individuals.

This project has three parts:
1. Baseline model
2. Engineered model
3. Fairness evaluation using the True Positive Parity measure
