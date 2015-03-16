
=========================================================================
Shaped data for the Human Activity Recognition Using Smartphones Dataset
=========================================================================
###Version 1.0

Course Project for the Coursera MOCC: Cleaning and Getting data Course Project
=========================================================================
###Author of the R script: Matias Thayer

The purpose of this project was to download and transform experimental data into a more readable way. 

The source data comes from: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

And the data set can be downloaded from here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Here is a description of the experiments as described in the original dataset:
"The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data."

The dataset includes the following files:
=========================================

- 'README.md'

- 'run_analysis.R': Script that get and clean data for the Samsung dataset. Particularly, it performs the following tasks:
    - Merges the training and the test sets to create one data set.
    - Extracts only the measurements on the mean and standard deviation for each measurement. 
    - Apply descriptive activity names to name the activities in the data set
    - Apply appropriate labels to the data set with descriptive variable names. 
    - Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
    - Export the tidy data set produced to the file: 'cleanDataSet.txt'

- 'cleanDataSet.txt': Output file. It was generated running the 'run_analysis.R' script

- 'SamsungDataSet.zip': Original data set


For more information about this work contact: chechir@gmail.com

