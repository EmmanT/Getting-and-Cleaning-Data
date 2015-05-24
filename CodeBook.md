# THE CODE BOOK

## How the run_analysis.R Works

1. install the library "plyr" first if plyr is not found in your R library.
2. Downloads source data when the data does not exist.
3. Merges the training and test sets to create one data set.
4. Rearrange the data using id
5. Use descriptive activity names in the data set
6. label the data set with descriptive activity name.
7. Extract the measurement on the mean and std dev for each measurement.
8. Save results in dataresult1
9. Create a tidy data with the mean of each variable & each activity.
10.  Adds "_mean" to colnames
11. Save the tidy dataset into dataresult2
	
## dataresult1.csv
contains 10299 rows and 81 columns in a default csv format.

## dataresult2.csv
contains 180 rows and 81 columns in a default csv format.
