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


