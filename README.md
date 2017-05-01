# Introduction

This repository contains my submission for Coursera: Getting and Cleaning Data course, week 4 Peer-graded assignment.

The root directory contains:
run_analysis.R and the CodeBook.md

This submission shows a tidy-data.txt file containing the tidy data set with the average of each variable for each activity and each subject.

run_analysis.R reads in:

'features_info.txt': Shows information about the variables used on the feature vector.

'features.txt': List of all features.

'activity_labels.txt': Links the class labels with their activity name.

'train/X_train.txt': Training set.

'train/y_train.txt': Training labels.

'test/X_test.txt': Test set.

'test/y_test.txt': Test labels.

Combines the test and controls sets

Adds the activity labels

Cleans the labels

and creates the dataset combinedmnsd

Groupby and summarise are then used to create all variable means in the dataset summarySet
