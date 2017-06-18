##Source
Human Activity Recognition Using Smartphones Data downloaded from:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Data source description can be found at:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

#variables
1) x_train, y_train, subject_train (read from train folder)
2) x__test, y_test, subect_test (read from test folder)
3) train (combined data set for train folder)
4) test (combined data set for test folder)
5) features (header names for x data sets)

#run_analysis.R description
Required data sets are downloaded and stored in the working directory.
Script takes the 2 data sets and merges them into one data set.
Steps:
1) Reading the data sets
2) Naming the columns of the data sets
3) Merging the data sets
4) Adding the description to the combined data set
5) Creating the final tidy data set# GettingandCleaningDataWeek4Assignment
