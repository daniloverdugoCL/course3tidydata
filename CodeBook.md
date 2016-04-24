#CodeBook.md

## Script Description

## Request:
3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 



# final script: run_analysis.R 

##task in sequential order:
* set working folder. user must change!! 
* downloads data base from link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
* unzips file
* results to folder
* load features.txt file, use like name columns

## Test set
* load dataset using X_test.txt, y_test.txt, subject_test.txt
* X_train: data using as columns to the feature data set
* y_train: activity labels
* subject_test: ids

## TRain set
* load train in X, train in Y and subject_train.txt
* X_train: data using as columns to the feature data set
* y_train: activity labels
* subject_train: ids

* appends (train and test)
* rearrange by id 
* clean memory with rm()

## TAREA 1
Merges the training and the test sets to create one data set.
## mydataframe created.

## TAREA 2
Extracts only the measurements on the mean and standard deviation for each 
measurement.
## meanystd object data.frame created

* load activity_labels.txt with column name.

## TAREA 3 and 4
Uses descriptive activity names to name the activities in the data set

## TAREA 5
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
Set in tidy label to activities with activity names.
Saves tidy data set with ONLY mean and std into:

# mitidydata.txt

Contain:
180 observations
81 variables


Names variables:
*  id	
*  activity	
*  tBodyAcc.std...X__mean	
*  tBodyAcc.std...Y__mean	
*  tBodyAcc.std...Z__mean	
*  tGravityAcc.std...X__mean	
*  tGravityAcc.std...Y__mean	
*  tGravityAcc.std...Z__mean	
*  tBodyAccJerk.std...X__mean	
*  tBodyAccJerk.std...Y__mean	
*  tBodyAccJerk.std...Z__mean	
*  tBodyGyro.std...X__mean	
*  tBodyGyro.std...Y__mean	
*  tBodyGyro.std...Z__mean	
*  tBodyGyroJerk.std...X__mean	
*  tBodyGyroJerk.std...Y__mean	
*  tBodyGyroJerk.std...Z__mean	
*  tBodyAccMag.std..__mean	
*  tGravityAccMag.std..__mean	
*  tBodyAccJerkMag.std..__mean	
*  tBodyGyroMag.std..__mean	
*  tBodyGyroJerkMag.std..__mean	
*  fBodyAcc.std...X__mean	
*  fBodyAcc.std...Y__mean	
*  fBodyAcc.std...Z__mean	
*  fBodyAccJerk.std...X__mean	
*  fBodyAccJerk.std...Y__mean	
*  fBodyAccJerk.std...Z__mean	
*  fBodyGyro.std...X__mean	
*  fBodyGyro.std...Y__mean	
*  fBodyGyro.std...Z__mean	
*  fBodyAccMag.std..__mean	
*  fBodyBodyAccJerkMag.std..__mean	
*  fBodyBodyGyroMag.std..__mean	
*  fBodyBodyGyroJerkMag.std..__mean	
*  tBodyAcc.mean...X__mean	
*  tBodyAcc.mean...Y__mean	
*  tBodyAcc.mean...Z__mean	
*  tGravityAcc.mean...X__mean	
*  tGravityAcc.mean...Y__mean	
*  tGravityAcc.mean...Z__mean	
*  tBodyAccJerk.mean...X__mean	
*  tBodyAccJerk.mean...Y__mean	
*  tBodyAccJerk.mean...Z__mean	
*  tBodyGyro.mean...X__mean	
*  tBodyGyro.mean...Y__mean	
*  tBodyGyro.mean...Z__mean	
*  tBodyGyroJerk.mean...X__mean	
*  tBodyGyroJerk.mean...Y__mean	
*  tBodyGyroJerk.mean...Z__mean	
*  tBodyAccMag.mean..__mean	
*  tGravityAccMag.mean..__mean	
*  tBodyAccJerkMag.mean..__mean	
*  tBodyGyroMag.mean..__mean	
*  tBodyGyroJerkMag.mean..__mean	
*  fBodyAcc.mean...X__mean	
*  fBodyAcc.mean...Y__mean	
*  fBodyAcc.mean...Z__mean	
*  fBodyAcc.meanFreq...X__mean	
*  fBodyAcc.meanFreq...Y__mean	
*  fBodyAcc.meanFreq...Z__mean	
*  fBodyAccJerk.mean...X__mean	
*  fBodyAccJerk.mean...Y__mean	
*  fBodyAccJerk.mean...Z__mean	
*  fBodyAccJerk.meanFreq...X__mean	
*  fBodyAccJerk.meanFreq...Y__mean	
*  fBodyAccJerk.meanFreq...Z__mean	
*  fBodyGyro.mean...X__mean	
*  fBodyGyro.mean...Y__mean	
*  fBodyGyro.mean...Z__mean	
*  fBodyGyro.meanFreq...X__mean	
*  fBodyGyro.meanFreq...Y__mean	
*  fBodyGyro.meanFreq...Z__mean	
*  fBodyAccMag.mean..__mean	
*  fBodyAccMag.meanFreq..__mean	
*  fBodyBodyAccJerkMag.mean..__mean	
*  fBodyBodyAccJerkMag.meanFreq..__mean	
*  fBodyBodyGyroMag.mean..__mean	
*  fBodyBodyGyroMag.meanFreq..__mean	
*  fBodyBodyGyroJerkMag.mean..__mean	
*  fBodyBodyGyroJerkMag.meanFreq..__mean


