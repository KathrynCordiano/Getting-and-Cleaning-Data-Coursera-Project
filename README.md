# Getting and Cleaning Data
##Coursera Project
The object of this repo is to create a tidy data set about wearable computer data originally from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

##Files in this Repo
* README.md: This file
* CodeBook.md: Describes the variables, the data, and any transformations or work that was performed to clean up the data
* run_analysis.R: Actual R code

##Goals of run_analysis.R
1. Merges the training and test sets to create one data set
2. Extracts only the measurements on the mean and standard deviation for each measurement
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names
5. From the data set in set 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

##Steps needed to use run_analysis.R
1. Download the data source onto your local drive. The folder should read "UCI Har Dataset"
2. Run run_analysis.R in the parent folder of "UCI Har Dataset", and then set is as your working directory using the setwd() function
3. Run source("run_analysis.R"), which will generate a new file named tidy_data.txt in your current working directory
