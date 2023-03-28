# Human Activity Cluster Analysis

Abstract:
We want to provide statistical analysis of the daily life activities of people which can form a base for various health-beneficial observations by exploring and comparing various concepts of Clustering and Dimensionality reduction techniques. The comparison is based on homogeneity, completeness and V-measure evaluation
metrics.

Dataset Description:
The dataset that we are working on is from the UCI Machine Learning Repository.
It is basically the data collected from the observations from an experiment that is carried out on a group of 30 volunteers. The volunteers have a smart gadget attached to their waist which records the data regarding different activities they undertake during their routine life.
The activities that are being tracked include
- WALKING
- WALKING_UPSTAIRS
- WALKING_DOWNSTAIRS
- SITTING
- STANDING
- LAYING
The dataset consists of a total of 10299 instances which is split into training and test data in the ratio of 70:30 respectively.
Training Data:
a) X_train.txt - Contains the reading collected from sensors.
b) y_train.txt - Contains the labels for the activities.
Test Data:
a) X_test.txt - Contains the reading collected from sensors for testing purposes.
b) y_test.txt - Contains the labels for the activities for testing purposes.

There are a few common files that can be used for both training and test data which include:
- features.txt - Contains the list of all features (561)
- features_info.txt - contains information regarding the features in the dataset
- activity_labels.txt - Numerical labels mapped to the categorical labels.

The features that we have are from the sensors like the accelerometer and gyroscope in X, Y, and Z directions.
