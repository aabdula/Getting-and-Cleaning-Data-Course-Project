code book
## Getting and Cleaning Data Project
+
##Abdul Abdulai

### Description
Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.

### Source Data
A full description of the data used in this project can be found at [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

here is the source data for this project (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

### Data Set Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

### Attribute Information
For each record in the dataset it is provided:
.- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
.- Triaxial Angular velocity from the gyroscope.
.- A 561-feature vector with time and frequency domain variables.
.- Its activity label.
.- An identifier of the subject who carried out the experiment.

### DataSet1
Each row of this dataset represents a different experiment, where data was acquired while the subject was performing one of the six following activities: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING. The variables stored are the result of post-processing the acquired data (where post-processing was done by the authors of the original data set). In DataSet1, for each experiment, only the mean and standard deviation variables have been kept.

The first and second column correspond to the subject's identification number and to the activity being performed by the subject during the data acquisition. The rest of the columns correspond to the mean and standard deviation of various features of the acquired data curves. These features are the following ([column_number] feature_name, the first two colums are included for clarity):
+ [1] "subject"
+ [2] "activity"
+ [3] "tBodyAcc-mean()-X"
+ [4] "tBodyAcc-mean()-Y"
+ [5] "tBodyAcc-mean()-Z"
+ [6] "tBodyAcc-std()-X"
+ [7] "tBodyAcc-std()-Y"
+ [8] "tBodyAcc-std()-Z"
+ [9] "tGravityAcc-mean()-X"
+[10] "tGravityAcc-mean()-Y"
+[11] "tGravityAcc-mean()-Z"
+[12] "tGravityAcc-std()-X"
+[13] "tGravityAcc-std()-Y"
+[14] "tGravityAcc-std()-Z"
+[15] "tBodyAccJerk-mean()-X"
+[16] "tBodyAccJerk-mean()-Y"
+[17] "tBodyAccJerk-mean()-Z"
+[18] "tBodyAccJerk-std()-X"
+[19] "tBodyAccJerk-std()-Y"
+[20] "tBodyAccJerk-std()-Z"
+[21] "tBodyGyro-mean()-X"
+[22] "tBodyGyro-mean()-Y"
+[23] "tBodyGyro-mean()-Z"
+[24] "tBodyGyro-std()-X"
+[25] "tBodyGyro-std()-Y"
+[26] "tBodyGyro-std()-Z"
+[27] "tBodyGyroJerk-mean()-X"
+[28] "tBodyGyroJerk-mean()-Y"
+[29] "tBodyGyroJerk-mean()-Z"
+[30] "tBodyGyroJerk-std()-X"
+[31] "tBodyGyroJerk-std()-Y"
+[32] "tBodyGyroJerk-std()-Z"
+[33] "tBodyAccMag-mean()"
+[34] "tBodyAccMag-std()"
+[35] "tGravityAccMag-mean()"
+[36] "tGravityAccMag-std()"
+[37] "tBodyAccJerkMag-mean()"
+[38] "tBodyAccJerkMag-std()"
+[39] "tBodyGyroMag-mean()"
+[40] "tBodyGyroMag-std()"
+[41] "tBodyGyroJerkMag-mean()"
+[42] "tBodyGyroJerkMag-std()"
+[43] "fBodyAcc-mean()-X"
+[44] "fBodyAcc-mean()-Y"
+[45] "fBodyAcc-mean()-Z"
+[46] "fBodyAcc-std()-X"
+[47] "fBodyAcc-std()-Y"
+[48] "fBodyAcc-std()-Z"
+[49] "fBodyAcc-meanFreq()-X"
+[50] "fBodyAcc-meanFreq()-Y"
+[51] "fBodyAcc-meanFreq()-Z"
+[52] "fBodyAccJerk-mean()-X"
+[53] "fBodyAccJerk-mean()-Y"
+[54] "fBodyAccJerk-mean()-Z"
+[55] "fBodyAccJerk-std()-X"
+[56] "fBodyAccJerk-std()-Y"
+[57] "fBodyAccJerk-std()-Z"
+[58] "fBodyAccJerk-meanFreq()-X"
+[59] "fBodyAccJerk-meanFreq()-Y"
+[60] "fBodyAccJerk-meanFreq()-Z"
+[61] "fBodyGyro-mean()-X"
+[62] "fBodyGyro-mean()-Y"
+[63] "fBodyGyro-mean()-Z"
+[64] "fBodyGyro-std()-X"
+[65] "fBodyGyro-std()-Y"
+[66] "fBodyGyro-std()-Z"
+[67] "fBodyGyro-meanFreq()-X"
+[68] "fBodyGyro-meanFreq()-Y"
+[69] "fBodyGyro-meanFreq()-Z"
+[70] "fBodyAccMag-mean()"
+[71] "fBodyAccMag-std()"
+[72] "fBodyAccMag-meanFreq()"
+[73] "fBodyBodyAccJerkMag-mean()"
+[74] "fBodyBodyAccJerkMag-std()"
+[75] "fBodyBodyAccJerkMag-meanFreq()"
+[76] "fBodyBodyGyroMag-mean()"
+[77] "fBodyBodyGyroMag-std()"
+[78] "fBodyBodyGyroMag-meanFreq()"
+[79] "fBodyBodyGyroJerkMag-mean()"
+[80] "fBodyBodyGyroJerkMag-std()"
+[81] "fBodyBodyGyroJerkMag-meanFreq()"

### DataSet2

This data-set is a summary of the previous data-set "DataSet1". It is an independent tidy data set with the average of each variable for each activity and each subject.

The first and second column correspond to the subject's identification number and to the activity being performed by the subject during the data acquisition. The rest of the columns correspond to the mean (of the means) of all similar experiments performed by the same subject executing the same activity. The columns of DataSet2 are the following ([column_number] column_name or feature_name):

+ [1] "subject"
+ [2] "activity"
+ [3] "tBodyAcc-mean()-X"
+ [4] "tBodyAcc-mean()-Y"
+ [5] "tBodyAcc-mean()-Z"
+ [6] "tGravityAcc-mean()-X"
+ [7] "tGravityAcc-mean()-Y"
+ [8] "tGravityAcc-mean()-Z"
+ [9] "tBodyAccJerk-mean()-X"
+[10] "tBodyAccJerk-mean()-Y"
+[11] "tBodyAccJerk-mean()-Z"
+[12] "tBodyGyro-mean()-X"
+[13] "tBodyGyro-mean()-Y"
+[14] "tBodyGyro-mean()-Z"
+[15] "tBodyGyroJerk-mean()-X"
+[16] "tBodyGyroJerk-mean()-Y"
+[17] "tBodyGyroJerk-mean()-Z"
+[18] "tBodyAccMag-mean()"
+[19] "tGravityAccMag-mean()"
+[20] "tBodyAccJerkMag-mean()"
+[21] "tBodyGyroMag-mean()"
+[22] "tBodyGyroJerkMag-mean()"
+[23] "fBodyAcc-mean()-X"
+[24] "fBodyAcc-mean()-Y"
+[25] "fBodyAcc-mean()-Z"
+[26] "fBodyAcc-meanFreq()-X"
+[27] "fBodyAcc-meanFreq()-Y"
+[28] "fBodyAcc-meanFreq()-Z"
+[29] "fBodyAccJerk-mean()-X"
+[30] "fBodyAccJerk-mean()-Y"
+[31] "fBodyAccJerk-mean()-Z"
+[32] "fBodyAccJerk-meanFreq()-X"
+[33] "fBodyAccJerk-meanFreq()-Y"
+[34] "fBodyAccJerk-meanFreq()-Z"
+[35] "fBodyGyro-mean()-X"
+[36] "fBodyGyro-mean()-Y"
+[37] "fBodyGyro-mean()-Z"
+[38] "fBodyGyro-meanFreq()-X"
+[39] "fBodyGyro-meanFreq()-Y"
+[40] "fBodyGyro-meanFreq()-Z"
+[41] "fBodyAccMag-mean()"
+[42] "fBodyAccMag-meanFreq()"
+[43] "fBodyBodyAccJerkMag-mean()"
+[44] "fBodyBodyAccJerkMag-meanFreq()"
+[45] "fBodyBodyGyroMag-mean()"
+[46] "fBodyBodyGyroMag-meanFreq()"
+[47] "fBodyBodyGyroJerkMag-mean()"
+[48] "fBodyBodyGyroJerkMag-meanFreq()"