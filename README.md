# Ahmed-Getting-and-Cleaning-Data

## Summary

The script file "run_analysis.R", is writen for the purpose to merge data from the Human Activity Recognition Using Smartphones Data Set project at the UCI Machine Learning Repository.
We produce averages values per user / per activity for the dataset's mean and standard deviation features.
The work is more explained in "codebook.md".

## Course Project

The R script file called run_analysis.R :

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Usage

Set the activity recognition dataset in the working directory.
Run the script run_analysis.R.
The script produces an output file named "tidy-data.csv".
"tidy-data.csv" contains the merged and transformed data.

## Steps to work on this course project

1. Download the data source and put into a folder on your local drive. You'll have a ```UCI HAR Dataset``` folder.
2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```, then set it as your working directory using ```setwd()``` function in RStudio.
3. Run ```source("run_analysis.R")```, then it will generate a new file ```tiny_data.txt``` in your working directory.

## Dependencies

run_analysis.R file will install the dependencies automatically. 
run_analysis.R depends on :
1) ```reshape2```
2) ```data.table```
