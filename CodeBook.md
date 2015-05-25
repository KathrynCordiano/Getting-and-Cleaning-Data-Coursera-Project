#Getting and Cleaning Data Code Book
Describes the variables, the data, and any transformations or work that was performed to clean up the data

##The Data Source
The original data source can be found here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
The original description of the data set can be found here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

##Files Used (Inside the original folder "UCI HAR Dataset")
* 'README.txt'
* 'features_info.txt': Shows information about the variables used on the feature vector.
* 'features.txt': List of all features.
* 'activity_labels.txt': Links the class labels with their activity name.
* 'train/X_train.txt': Training set.
* 'train/y_train.txt': Training labels.
* 'test/X_test.txt': Test set.
* 'test/y_test.txt': Test labels.

##The Analysis Creates the Following Data:
* 'data': a dataframe including both train and test data labeled by subject and by activity
* 'data.mean.std': a subset of 'data' including only observations of the mean and standard deviation for each measurement
* 'aggregate.means': a dataframe containing the mean of the data for each combination of subject and activity
* 'tidy.txt': a text file containg the data in the 'aggregate.means' dataframe

