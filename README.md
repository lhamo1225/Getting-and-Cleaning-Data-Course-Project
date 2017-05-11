# Coursera Course Getting and Cleaning Data

The repository contains the required files for the Getting and Cleaning Data course at Coursera.
The R script, `run_analysis.R`, does the following:

1. Download the dataset (if not already existing in the working directory)
2. Load the activity labels and features from the corresponding `txt` files.
3. Load both the training and test datasets (only the columns for the mean and standard deviation for each measurement are kept)
4. Load the activity and subject data for each dataset, and merge respective
   columns with the dataset
5. Merge both datasets and add labels
6. Convert the `activity` and `subject` columns into factors
7. Creates an independant tidy dataset that contains the average of each variable for each activity and each subject

The result is stored in the file `tidy.txt`.
The file `CodeBook.md` explains the data elements of `tidy.txt`
