 CODE BOOK


The attached R script (run_analysis.R) performs the following to clean up the data:

Identifiers 
         • subject - The ID of the test subject 
         • activity - The type of activity performed when the corresponding measurements were taken

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


timeBodyAccelerometer-mean()-X	 timeBodyAccelerometer-mean()-Y	 timeBodyAccelerometer-mean()-Z	 timeBodyAccelerometer-std()-X	timeBodyAccelerometer-std()-Y 	timeBodyAccelerometer-std()-Z	 timeGravityAccelerometer-mean()-X	 timeGravityAccelerometer-mean()-Y	timeGravityAccelerometer-mean()-Z	 timeGravityAccelerometer-std()-X	 timeGravityAccelerometer-std()-Y	 timeGravityAccelerometer-std()-Z	timeBodyAccelerometerJerk-mean()-X	 timeBodyAccelerometerJerk-mean()-Y	 timeBodyAccelerometerJerk-mean()-Z	 timeBodyAccelerometerJerk-std()-X	 timeBodyAccelerometerJerk-std()-Y	 timeBodyAccelerometerJerk-std()-Z	 timeBodyGyroscope-mean()-X	 timeBodyGyroscope-mean()-Y	timeBodyGyroscope-mean()-Z	timeBodyGyroscope-std()-X	timeBodyGyroscope-std()-Y	timeBodyGyroscope-std()-Z	timeBodyGyroscopeJerk-mean()-X	timeBodyGyroscopeJerk-mean()-Y	timeBodyGyroscopeJerk-mean()-Z	timeBodyGyroscopeJerk-std()-X	timeBodyGyroscopeJerk-std()-Y	timeBodyGyroscopeJerk-std()-Z	timeBodyAccelerometerMagnitude-mean()	timeBodyAccelerometerMagnitude-std()	timeGravityAccelerometerMagnitude-mean()	timeGravityAccelerometerMagnitude-std()	timeBodyAccelerometerJerkMagnitude-mean()	timeBodyAccelerometerJerkMagnitude-std()	timeBodyGyroscopeMagnitude-mean()	timeBodyGyroscopeMagnitude-std()	timeBodyGyroscopeJerkMagnitude-mean()	timeBodyGyroscopeJerkMagnitude-std()	frequencyBodyAccelerometer-mean()-X	frequencyBodyAccelerometer-mean()-Y	frequencyBodyAccelerometer-mean()-Z	frequencyBodyAccelerometer-std()-X	frequencyBodyAccelerometer-std()-Y	frequencyBodyAccelerometer-std()-Z	frequencyBodyAccelerometerJerk-mean()-X	frequencyBodyAccelerometerJerk-mean()-Y	frequencyBodyAccelerometerJerk-mean()-Z	frequencyBodyAccelerometerJerk-std()-X	frequencyBodyAccelerometerJerk-std()-Y	frequencyBodyAccelerometerJerk-std()-Z	frequencyBodyGyroscope-mean()-X	frequencyBodyGyroscope-mean()-Y	frequencyBodyGyroscope-mean()-Z	frequencyBodyGyroscope-std()-X	frequencyBodyGyroscope-std()-Y	frequencyBodyGyroscope-std()-Z	frequencyBodyAccelerometerMagnitude-mean()	frequencyBodyAccelerometerMagnitude-std()	frequencyBodyAccelerometerJerkMagnitude-mean()	frequencyBodyAccelerometerJerkMagnitude-std()	frequencyBodyGyroscopeMagnitude-mean()	frequencyBodyGyroscopeMagnitude-std()	frequencyBodyGyroscopeJerkMagnitude-mean()	frequencyBodyGyroscopeJerkMagnitude-std()

Finally, the script creates a 2nd, independent tidy data set with the average of each measurement for each activity and each subject
It is saved in File name "final tidydata.txt"
