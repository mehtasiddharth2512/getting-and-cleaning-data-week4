# Getting-and-Cleaning-Data-Week-4-Assignment

### Data description
The variables in the data X are sensor signals measured with waist-mounted smartphone from its users. The variable in the data Y indicates activity type. 

### New dataset
The new generated dataset has variables calculated based on the mean and standard deviation.

The code possesses the following features: 

1. Merges the training and the test sets to create one data set. Use command rbind to combine training and test set. 
2. Extracts only the measurements on the mean and standard deviation for each measurement. Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set. Converts activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names and gives the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
