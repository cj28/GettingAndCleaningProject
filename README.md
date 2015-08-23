#Getting And Cleaning Project
#####Getting and Cleaning Data Project
run_analysis.R -- The R code will check for the Samsung data. If the file does not exist in you current working directory, the code will download
the zip file from the source
This code will produce one space separated file that contains the mean of each "subject" for each "activity"
The variables are taken as is from the "features.txt" and "activity_label.txt" provided in the downloaded data.

You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
