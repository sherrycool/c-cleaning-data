#CodeBook.md
## Data source
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
## Variable Selection
### data table
### labels
### colnames
### dataset
### function
## Transforming process
###1. Merges the training and the test sets to create one data set.
###2. Extracts only the measurements on the mean and standard deviation for each measurement.
###3. Uses descriptive activity names to name the activities in the data set
###4. Appropriately labels the data set with descriptive activity names.
###5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
## Process in detail
###1. require packages(data.table) and (reshape2)
###2. load the data(labels,colnames) from the txts.
###3. bind and merge the data together
###4. apply the mean function to the dataset and get the tidy data
