## Peer-graded Assignment: Getting and Cleaning Data Course Project

# Downloading
Url = Download link
Path = Directory Path
Files = Recursive file creation

# Assigning files
# All file names
labelTrain
labelTest
subTrain
subTest  
setTrain
setTest

# Merging
rSub = rbind subs
rLabel = rbind labels
rSet = rbind set
rSetNames = row set names
dataCombine = combine columns
merge = cbind the rest of the data

# Read in Labels
activityLabels = Activity Labels data


newData = Tidy data




## About R script
File on R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work)

## About variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
