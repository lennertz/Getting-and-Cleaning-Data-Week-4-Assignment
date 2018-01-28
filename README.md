# Getting-and-Cleaning-Data-Week-4-Assignment
This is a repository for completing the peer graded assignment for week 4 of Johns Hopkins Coursera course

Summary

The data set was derived from the 'UCI HAR Dataset' which is available at:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The purpose of the code is to merge subsets of the data into an intermediary (Data) and final tidy dataset (Data2, tidydata.txt) and to 
extract variables to create a dataset including the averages for each measured activity and subject.

The data set consists of one single file:
file://data/tidydata.txt

Run

Please note that the data files obtained will be zipped.  The file "run_analysis.R" includes procedures for obtaining the file, for unzipping ,
and for loading the file into the working directory.

The script will create the result data file "tidy_dataset.txt" in the working directory. In order to see the results more clearly, please view 
Data (cleaned data) and Data2 (tidy data) in Rstudio.

The script executes the following steps required for the assignment:

    Merges the training and the test sets to create one data set using the rbind command.
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    Uses descriptive activity names to name the activities in the data set 
    Appropriately labels the data set with descriptive variable names. Converts labels to more human readable text
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
