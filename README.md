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

Final output file is "final tidydata.txt"
