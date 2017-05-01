Getting and Cleaning Data - Coursera Project

This is the course project for Getting and Cleaning Data course on Coursera. Code is written in R in file. Source file is run_analysis.R. This R script does the following things:

1) download the zip file and save it in data folder

2)  unzip the file

3) unzip files are in the folder UCI HAR Dataset

4) Read the data from the files into the variables

Read the Activity files.
Read the Subject files.
Read Features files.

5) Merge the training & test data set to create one data set
 
 Merging the data set by rows
 set names to variables
 Merging the data set by colunmes to get final data frame
 
6) Extracting the measurements on the mean & std deviation for each measurement
 
 Subset Name of Features by measurements on the mean and standard deviation
 subset data frame by feature names

7) Descriptive activity names to name the activities

8) label the data set with appropriate descriptive variable name

9) create tidy ,independent data set

Concatenate the data tables by rows.
set names to variables.
Merge columns to get the data frame Data for all data.
Extracts only the measurements on the mean and standard deviation for each measurement.

Subset Name of Features by measurements on the mean and standard deviation.
Subset the data frame Data by selected names of Features.
Uses descriptive activity names to name the activities in the data set.

Read descriptive activity names from activity_labels.txt
Factorize variable activity in the data frame Data using descriptive activity names.
Appropriately labels the data set with descriptive variable names.

Creates a independent tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

Final output file is tidydata.txt