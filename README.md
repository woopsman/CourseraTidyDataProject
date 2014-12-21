Repo for Coursera Data Science / R Data Cleaning Project

This serves as both the README and the code book for the data.

This analysis makes use of the "reshape2" package. Please install it before performing the analysis.

NOTE: Since the data has been processed already to calculate the various absolute displacements, it was determined that since the processed measurements were included, the individual X, Y, Z acelerometer were excluded.

This file uses the UCI HAR dataset available from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones (University of California Irvine Human Activity Recognition) which are tracking accelerometer data collected from smartphones while test subjects performed various activities.

The data is provided in separate files and in two folders. There is both a 'test' and 'train' folder with data used to train an algorithm and one to test the predictions made. This analysis will combine the two sets as we are not performing any computer-directed learning on them.

In the data set, there is a file activity_labels.txt which translates the numeric activity designations into the 6 activities performed. The numeric activities are stored in the y_*.txt files and range from integers 1 to 6, inclusive.

The subject_*.txt files in the test and train directories associate the number of the subject being recorded, so there are multiple data readings for combinations of subject and activity.

The X_*.txt files contain the actual sensor readings and are described by the features_info.txt in the main directory of the data set.

The analysis combined these files and, per the directions, selected out only the mean and standard deviation for each measurement.
