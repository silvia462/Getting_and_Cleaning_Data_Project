# Getting_and_Cleaning_Data_Project

## Introduction
The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

In this project, there will be:
- a tidy data set as described below. 
- a link to a Github repository with the script for performing the analysis. 
- a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. There will also be a README.md in the repo with the scripts. This repo explains how all of the scripts work and how they are connected.

## Data
A full description is available at the site where the data was obtained [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

[Here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) are the data for the project. 

## Files
- "run_analysis.R" is the R script for running all functions to fulfil this project tasks. 
- "codebook.md" gives the relevant information about the data and steps to run the project.
- "MeanData.txt" is a tidy dataset that contains mean of each measurement for each activity and each subject.
- "README.md" is the file you are reading.

## Explanation

The R script which is called "run_analysis.R" should contain the following:

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set. 
- Appropriately labels the data set with descriptive variable names.
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


