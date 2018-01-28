CODEBOOK

Summary

The data set was derived from the 'UCI HAR Dataset' which is available at:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The data set was created as part of the Peer-graded Assignment: Getting and Cleaning Data Course Project.This code book summarizes the resulting data fields in tidy.txt.

Data set

The data set consists of one single file:

file://data/tidydata.txt

The file is a CSV text file (ASCII), the values are separated by white space.


Identifiers

    subject - The ID of the test subject
    activity - The type of activity performed when the corresponding measurements were takens
Activity Labels

    WALKING (value 1): subject was walking during the test
    WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
    WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
    SITTING (value 4): subject was sitting during the test
    STANDING (value 5): subject was standing during the test
    LAYING (value 6): subject was laying down during the test

Variables overview

    Variable 	Column 	Class 	Explanation
    subject 	1 	factor 	ID of subject
    activity 	2 	factor 	Activity label
 
    Variable	Column	Class	Explanation
        subject	1	factor	ID of subject
        activity	2	factor	Activity label
         timeBodyAccelerometer-mean()-X  	3	numeric	Measurement variable
        timeBodyAccelerometer-mean()-Y  	4	numeric	Measurement variable
         timeBodyAccelerometer-mean()-Z 	5	numeric	Measurement variable
        timeBodyAccelerometer-std()-X     	6	numeric	Measurement variable
        timeBodyAccelerometer-std()-Y	7	numeric	Measurement variable
        timeBodyAccelerometer-std()-Z 	8	numeric	Measurement variable
        timeGravityAccelerometer-mean()-X 	9	numeric	Measurement variable
        timeGravityAccelerometer-mean()-Y 	10	numeric	Measurement variable
        timeGravityAccelerometer-mean()-Z   	11	numeric	Measurement variable
        timeGravityAccelerometer-std()-X	12	numeric	Measurement variable
        timeGravityAccelerometer-std()-X	13	numeric	Measurement variable
        timeGravityAccelerometer-std()-Z   	14	numeric	Measurement variable
        timeBodyAccelerometerJerk-mean()-X    	15	numeric	Measurement variable
        timeBodyAccelerometerJerk-mean()-Y	16	numeric	Measurement variable
        timeBodyAccelerometerJerk-mean()-Z 	17	numeric	Measurement variable
        timeBodyAccelerometerJerk-std()-X 	18	numeric	Measurement variable
        timeBodyAccelerometerJerk-std()-Y   	19	numeric	Measurement variable
        timeBodyAccelerometerJerk-std()-Z   	10	numeric	Measurement variable
        timeBodyGyroscope-mean()-X 	12	numeric	Measurement variable
        timeBodyGyroscope-mean()-Y   	22	numeric	Measurement variable
        timeBodyGyroscope-mean()-Z 	23	numeric	Measurement variable
        timeBodyGyroscope-std()-X  	24	numeric	Measurement variable
        timeBodyGyroscope-std()-Y	25	numeric	Measurement variable
        timeBodyGyroscope-std()-Z 	26	numeric	Measurement variable
        timeBodyGyroscopeJerk-mean()-X	27	numeric	Measurement variable
        timeBodyGyroscopeJerk-mean()-Y	28	numeric	Measurement variable
        timeBodyGyroscopeJerk-mean()-Z	29	numeric	Measurement variable
        timeBodyGyroscopeJerk-std()-X	30	numeric	Measurement variable
        timeBodyGyroscopeJerk-std()-Y	31	numeric	Measurement variable
        timeBodyGyroscopeJerk-std()-Z	32	numeric	Measurement variable
        timeBodyAccelerometerMagnitude-mean()	33	numeric	Measurement variable
        timeBodyAccelerometerMagnitude-std()	34	numeric	Measurement variable
timeGravitimeyAccelerometerMagnitude-mean()	35	numeric	Measurement variable
timeGravitimeyAccelerometerMagnitude-std()	36	numeric	Measurement variable
timeBodyAccelerometerJerkMagnitude-mean()	37	numeric	Measurement variable
timeBodyAccelerometerJerkMagnitude.std()	38	numeric	Measurement variable
timeBodyGyroscopeMagnitude-mean()	39	numeric	Measurement variable
timeBodyGyroscopeMagnitude-std()	40	numeric	Measurement variable
timeBodyGyroscopeJerkMagnitude-mean()	41	numeric	Measurement variable
timeBodyGyroscopeJerkMagnitude-std()	42	numeric	Measurement variable
frequencyBodyAccelerometer-mean()-X	43	numeric	Measurement variable
frequencyBodyAccelerometer-mean()-Y	44	numeric	Measurement variable
frequencyBodyAccelerometer-mean()-Z	45	numeric	Measurement variable
frequencyBodyAccelerometer-std()-X	46	numeric	Measurement variable
frequencyBodyAccelerometer-std()-Y	47	numeric	Measurement variable
frequencyBodyAccelerometer-std()-Z	48	numeric	Measurement variable
frequencyBodyAccelerometerJerk-mean()-X	49	numeric	Measurement variable
frequencyBodyAccelerometerJerk-mean()-Y	50	numeric	Measurement variable
frequencyBodyAccelerometerJerk-mean()-Z	51	numeric	Measurement variable
frequencyBodyAccelerometerJerk-std()-X	52	numeric	Measurement variable
frequencyBodyAccelerometerJerk-std()-Y	53	numeric	Measurement variable
frequencyBodyAccelerometerJerk-std()-Z	54	numeric	Measurement variable
frequencyBodyGyroscope-mean()-X	55	numeric	Measurement variable
frequencyBodyGyroscope-mean()-Y	56	numeric	Measurement variable
frequencyBodyGyroscope-mean()-Z	57	numeric	Measurement variable
frequencyBodyGyroscope-std()-X	58	numeric	Measurement variable
frequencyBodyGyroscope-std()-Y	59	numeric	Measurement variable
frequencyBodyGyroscope-std()-Z	60	numeric	Measurement variable
frequencyBodyAccelerometerMagnitude-mean()	61	numeric	Measurement variable
frequencyBodyAccelerometerMagnitude.std()	62	numeric	Measurement variable
frequencyBodyAccelerometerJerkMagnitude-mean() 	63	numeric	Measurement variable
frequencyBodyAccelerometerJerkMagnitude.std()	64	numeric	Measurement variable
frequencyBodyGyroscopeMagnitude-mean()	65	numeric	Measurement variable
frequencyBodyGyroscopeMagnitude.std()	66	numeric	Measurement variable
frequencyBodyGyroscopeJerkMagnitude-mean()	67	numeric	Measurement variable
frequencyBodyGyroscopeJerkMagnitude.std()	68	numeric	Measurement variable


