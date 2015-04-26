# Getting-and-Cleaning-data
1)Merge the training and the test sets to create one data set.

After setting the source directory for the files, read into tables the data located in

features.txt
activity_labels.txt
subject_train.txt
x_train.txt
y_train.txt
subject_test.txt
x_test.txt
y_test.txt
Assign column names and merge to create one data set.

2)Extract only the measurements on the mean and standard deviation for each measurement.

3) Use descriptive activity names to name the activities in the data set

Merge data subset with the activityType table to include the descriptive activity names

4)Appropriately label the data set with descriptive activity names.

Use gsub function for pattern replacement to clean up the data labels.

5)Create a second, independent tidy data set with the average of each variable for each activity and each subject.

