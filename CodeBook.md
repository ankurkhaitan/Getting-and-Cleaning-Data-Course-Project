# Code Book

This code book describes the variables of the data set, and any transformations performed to clean up the data in `unique_act_sub.txt` 

## Feature Selection and Sample Aggregation

- The training and test set are concatnated into one data set

- Features regarding **Mean value** and **Standard deviation** are selected from the original data

- Samples with the same `activity_name` and `subject_id` are reduced to the corresponding **mean value**

## List of Features

### Identifiers
* `subject_id`: The ID of the volunteer ranging from 1 - 30
* `activity_name`: specific activities individuals were performing, includes: `WALKING`, `WALKING_UPSTAIRS`, `WALKING_DOWNSTAIRS`, `SITTING`, `STANDING`, `LAYING`

### Measured Variables
#### feature info
* `t`: time domain signal
* `Acc`: acceleration signal
* `Gyro`: gyroscope signal
* `Jerk`: jerk signal obtained from linear acceleration and angular velocity
* `Mag`: magnitude of signal
* `-XYZ`: 3-axial signals in the `X`, `Y`, `Z` directions
* `f`: fast Fourier transform of the signal
* `mean()`: statistical mean applied to the time domain signal
* `std()`: standard deviation of the time domain signal
* `Body`: results from human movement
* `Gravity`: results from gravitational force

#### feature detail
* `tBodyAcc-mean()-X`
* `tBodyAcc-mean()-Y`
* `tBodyAcc-mean()-Z`
* `tBodyAcc-std()-X`
* `tBodyAcc-std()-Y`
* `tBodyAcc-std()-Z`
* `tGravityAcc-mean()-X`
* `tGravityAcc-mean()-Y`
* `tGravityAcc-mean()-Z`
* `tGravityAcc-std()-X`
* `tGravityAcc-std()-Y`
* `tGravityAcc-std()-Z`
* `tBodyAccJerk-mean()-X`
* `tBodyAccJerk-mean()-Y`
* `tBodyAccJerk-mean()-Z`
* `tBodyAccJerk-std()-X`
* `tBodyAccJerk-std()-Y`
* `tBodyAccJerk-std()-Z`
* `tBodyGyro-mean()-X`
* `tBodyGyro-mean()-Y`
* `tBodyGyro-mean()-Z`
* `tBodyGyro-std()-X`
* `tBodyGyro-std()-Y`
* `tBodyGyro-std()-Z`
* `tBodyGyroJerk-mean()-X`
* `tBodyGyroJerk-mean()-Y`
* `tBodyGyroJerk-mean()-Z`
* `tBodyGyroJerk-std()-X`
* `tBodyGyroJerk-std()-Y`
* `tBodyGyroJerk-std()-Z`
* `tBodyAccMag-mean()`
* `tBodyAccMag-std()`
* `tGravityAccMag-mean()`
* `tGravityAccMag-std()`
* `tBodyAccJerkMag-mean()`
* `tBodyAccJerkMag-std()`
* `tBodyGyroMag-mean()`
* `tBodyGyroMag-std()`
* `tBodyGyroJerkMag-mean()`
* `tBodyGyroJerkMag-std()`
* `fBodyAcc-mean()-X`
* `fBodyAcc-mean()-Y`
* `fBodyAcc-mean()-Z`
* `fBodyAcc-std()-X`
* `fBodyAcc-std()-Y`
* `fBodyAcc-std()-Z`
* `fBodyAcc-meanFreq()-X`
* `fBodyAcc-meanFreq()-Y`
* `fBodyAcc-meanFreq()-Z`
* `fBodyAccJerk-mean()-X`
* `fBodyAccJerk-mean()-Y`
* `fBodyAccJerk-mean()-Z`
* `fBodyAccJerk-std()-X`
* `fBodyAccJerk-std()-Y`
* `fBodyAccJerk-std()-Z`
* `fBodyAccJerk-meanFreq()-X`
* `fBodyAccJerk-meanFreq()-Y`
* `fBodyAccJerk-meanFreq()-Z`
* `fBodyGyro-mean()-X`
* `fBodyGyro-mean()-Y`
* `fBodyGyro-mean()-Z`
* `fBodyGyro-std()-X`
* `fBodyGyro-std()-Y`
* `fBodyGyro-std()-Z`
* `fBodyGyro-meanFreq()-X`
* `fBodyGyro-meanFreq()-Y`
* `fBodyGyro-meanFreq()-Z`
* `fBodyAccMag-mean()`
* `fBodyAccMag-std()`
* `fBodyAccMag-meanFreq()`
* `fBodyBodyAccJerkMag-mean()`
* `fBodyBodyAccJerkMag-std()`
* `fBodyBodyAccJerkMag-meanFreq()`
* `fBodyBodyGyroMag-mean()`
* `fBodyBodyGyroMag-std()`
* `fBodyBodyGyroMag-meanFreq()`
* `fBodyBodyGyroJerkMag-mean()`
* `fBodyBodyGyroJerkMag-std()`
* `fBodyBodyGyroJerkMag-meanFreq()`
