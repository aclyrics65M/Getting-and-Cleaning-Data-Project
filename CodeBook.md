Source Data:
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 
A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

R Script:
You should create one R script called run_analysis.R that does the following:
1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement.
3. Using descriptive activity names to name the activities in the data set.
4. Appropriately labeling the data set with descriptive variable names.
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

Variables:
Variables that include the data from the downloaded files: x_train, y_train, x_test, y_test, subject_train and subject_test
Variables that merge the previous datasets to further analysis: x_data, y_data and subject_data
