# Getting and Cleaning Data Course Project

## Motivation of Data Set
This data set is motivated by the course project of Getting and Cleaning Data from Coursera John Hopkins University Data Science Special Section. The purpose of the project is to obtain tidy dataset by collecting, working with, and cleaning a raw data set. The original data set is obtained from the *Human Activity Recognition Using Smartphones Data Set* in **UCI Machine Learning Repository**.

This smartphone data set is one of the typical examples of wearable computing - see for example [this article](http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/). Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. A full description of the smartphone data set is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones (a newly updated version is also available).

For the smartphone data set, relevant experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years old. Each individual performed six different activities wearing a smartphone, including walking, walking upstairs, walking downstairs, sitting, standing and laying. The smartphone was embedded accelerometer and gyroscope to capture the movement of the individuals. The experiments were also video-recorded to label the data manually. 

## This repository includes the following files

1. `README.md`: explains how all of the scripts work and how they are connected.

2. `unique_act_sub.txt`: a tidy data set with unique identifiers *subject* and *activity*, with 180 observations and 81 variables including *subject_id* and *activity_name*

3. `run_analysis.R`: code generating the tidy data set from raw data recorded in the *Human Activity Recognition Using Smartphones Data Set*. The process of generating tidy data set includes the following steps:

   - Merges the training and the test sets to create one data set called `mergedata`.
   - Extracts only the measurements on the mean and standard deviation for each measurement to get `feature_mean_std`.
   - Uses descriptive activity names to name the activities in the data set, replace `activity_id` with descriptive names in `activity_label`.
   - Appropriately labels the data set with descriptive variable names given in `feature_name`.
   - From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject `unique_act_sub`.

4. `CodeBook.md`: a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data

