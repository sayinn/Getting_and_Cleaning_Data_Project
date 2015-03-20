# Getting_and_Cleaning_Data_Project

## Course Project  

You should create one R script called run_analysis.R that does the following.

1.Merges the training and the test sets to create one data set.  
2.Extracts only the measurements on the mean and standard deviation for each measurement.  
3.Uses descriptive activity names to name the activities in the data set.  
4.Appropriately labels the data set with descriptive variable names.  
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The files that will be used to load data are listed as follows:  
- test/subject_test.txt  
- test/X_test.txt  
- test/y_test.txt  
- train/subject_train.txt  
- train/X_train.txt  
- train/y_train.txt  

## Steps
1. Read all the test and training files
2. Read data from the files into the variables and look at their properties
3. To create one data set, concatenate the data tables by rows, set names to variables and merge columns
4. Subset name of features by measurements on the mean and standard deviation
5. Subset the data frame by seleted names of features and check the structures
6. Read descriptive activity names, factorise, check
7. Replace labels with descriptive variable names
8. Write table to create second, independent tidy data set
