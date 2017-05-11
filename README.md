The repository contains the required files for the Getting and Cleaning Data course at Coursera. The R script, run_analysis.R, does the following:

Download the dataset (if not already existing in the working directory)
Load the activity labels and features from the corresponding txt files.
Load both the training and test datasets (only the columns for the mean and standard deviation for each measurement are kept)
Load the activity and subject data for each dataset, and merge respective columns with the dataset
Merge both datasets and add labels
Convert the activity and subject columns into factors
Creates an independant tidy dataset that contains the average of each variable for each activity and each subject
The result is stored in the file tidy.txt. The file CodeBook.md explains the data elements of tidy.txt
