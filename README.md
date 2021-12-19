# GettingCleaningCP
Course Project for the Getting and Clenaing Data Course


The aim of the project is to collect, work with, and clean a data set. The data set is extracted from the accelerometers from the Samsung Galaxy S smartphone. More information about the dataset is available in http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

For achieving the assingment a R file should be created and it must do the following:
1) Merge the training and the test sets to create one data set.
2) Extract only the measurements on the mean and standard deviation for each measurement. 
3) Use descriptive activity names to name the activities in the data set
4) Appropriately label the data set with descriptive variable names. 
5) From the data set in step 4, create a second, independent tidy data set with the average of each variable for each activity and each subject.

Therefore, the code has been divided in 7 parts which perform the following:
1) Extraction and download of the untidy dataset. Creates an unzipped file available in the working directory.
2) Assignment of the names of each of the tables in the file, creation of the dataframes which will be merged later.
3) Merging the dataframes, creation of the Merged_Data dataframe.
4) Extraction of the mean and standard deviation, creation of the Tidy_Data dataframe.
5) Naming the activities following the activities dataframe.
6) Correct labeling of the data.
7) Creation of the new and tidy dataset
