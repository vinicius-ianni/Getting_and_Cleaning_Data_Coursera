##Brief explanation:

The data used here, has a full description here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

And can be downloaded here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The tasks need to be performed in this cnclusion project are:

"You should create one R script called run_analysis.R that does the following. 

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names. 

    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
"

##About the variables:

file_features, file_activity_labels, file_subject_train, file_x_train, file_y_train, file_subject_test, file_x_test,file_y_test
loads the features.txt, activity_labels.txt, subject_train.txt, X_train.txt, y_train.txt, subject_test.txt, X_test.txt, y_test.txt respectively.

full_training & full_test contains entire trainning and test sets.

combined_files contains entire trainning and test sets merged.

column_names contains only the names of columns to be manipulated later.

bol_var is a boolean variable to peform the asked in step 2 of the task.

mini_combined performs the last step of the task.
