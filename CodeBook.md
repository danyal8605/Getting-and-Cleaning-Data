##Getting-and-Cleaning-Data Peer Assessment ###run_analysis.R Input:Raw data

./UCI HAR Dataset/train/X_train.txt
./UCI HAR Dataset/train/Y_train.txt
./UCI HAR Dataset/train/subject_train.txt
./UCI HAR Dataset/test/X_test.txt
./UCI HAR Dataset/test/Y_test.txt
./UCI HAR Dataset/test/subject_test.txt
Output:Tidy data

tidydata.txt
Processing:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
###CodeBook.md Describes the variables, the data, and transformations of the raw data
