# CourseraDataScience-3-Getting-and-Cleaning-Data

## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this course project

1. Make sure you have write access in the working directory.
2. Put ```run_analysis.R``` in the working directory.
3. Run ```source("run_analysis.R")``` and then invoke the function ```runAnalysis```.
4. The function will first download the dataset into a file called ```data.zip``` and then unzip it and work with it.
5. After the function finishes, it will generate a new file ```tiny_data.txt``` in the working directory folder.

## Dependencies

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```. 
