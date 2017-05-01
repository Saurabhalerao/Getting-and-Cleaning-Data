 CODE BOOK

Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


The attached R script (run_analysis.R) performs the following to clean up the data:

Merges the training and test sets to create one data set.( Data )

Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement. 

Reads activity_labels.txt and applies descriptive activity names to name the activities in the data set:

1) walking

2) walkingupstairs

3) walkingdownstairs

4) sitting

5) standing

6) laying

The script also appropriately labels the data set with descriptive names: 
 The names of the features are similar to the following:

timeBodyAccelerometer-XYZ
timeGravityAccelerometer-XYZ
timeBodyAccelerometerJerk-XYZ
timeBodyGyroscope-XYZ
timeBodyGyroscopeJerk-XYZ
timeBodyAccelerometerMagnitude
timeGravityAccelerometerMagnitude
timeBodyAccelerometerJerkMagnitude
timeBodyGyroscopeMagnitude
timeBodyGyroscopeJerkMagnitude
frequencyBodyAccelerometer-XYZ
frequencyBodyAccelerometerJerk-XYZ
frequencyBodyGyroscope-XYZ
frequencyBodyAccelerometerMagnitude
frequencyBodyAccelerometerJerkMagnitude
frequencyBodyGyroscopeMagnitude
frequencyBodyGyroscopeJerkMagnitude

Finally, the script creates a 2nd, independent tidy data set with the average of each measurement for each activity and each subject
It is saved in File name tidydata.txt