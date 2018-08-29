# **_Project Statement_**  
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be required to submit:   
1) a tidy data set as described below     
2) a link to a Github repository with your script for performing the analysis, and  
3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  
**tidy_data_set description:**  
Merges the training and the test sets to create one data set.Extracts only the measurements on the mean and standard deviation for each measurement.Uses descriptive activity names to name the activities in the data set Appropriately labels the data set with descriptive variable names.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

**_Data for the project can be downloaded from this link:_**
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

 # _Working with data_   
 - Run the script **run_analysis.R**(_it will download the data set in the directory mentioned in the "destfile", so put a suitable adress in the destfile variable if the default fails_)   
 - Please make sure that UC HAR DATASET is set as the working directory  
 - My code uses "plyr" and "data.table" library, please make sure its installed in your R environment(eg. Rstudio)  
 - The code performs the following major functions:  
   1.combines two data set into one    
   2.subsets data based on mean and sd   
   3.lables the data columns   
   4.creates a new dataset as required by the problem statement  
   
 
