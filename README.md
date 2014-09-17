# Getting and Cleaning Data - Project 


## Usage  
Uses the `run_analysis.R` script to create the tidy output files. The Samsung data must be copied to the same working directory as the script without any changes being applied to the directory structure.  

## Requirements  
The `data.table` package must be loadaed into the R environment. Most of the requirements are actually satisfied by using the features available in this package, like the averaging of each variable.

## Transformations  
This script performs transformations on the Samsung dataset consistent with the requests on the work requested on the course project. In summary, it does the following:  

* Merges the training and the test sets to create one data set.  
* Extracts only the measurements on the mean and standard deviation for each measurement.  
* Uses descriptive activity names to name the activities in the data set.
* Appropriately labels the data set with descriptive activity names. (`tidy_data.txt`)
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject. (`summary_data.txt`)  

## Output  

The scripts creates two files upon being run:  

* tidy_data.txt - CSV file which has the tidy dataset as required by the project.
* summary_data.txt - CSV file which has the second, independent tidy data set with the average of each variable for each activity and each subject. 
