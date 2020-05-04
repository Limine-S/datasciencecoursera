# 1. Merge the training and the test sets to create one data set.

## step 1: download zip file from website

## step 2: unzip data

## step 3: load data into R
train.x 
train.y 
train.subject 
test.x
test.y 
test.subject 

## step 4: merge train and test data
trainData
testData 
fullData 

# 2. Extract only the measurements on the mean and standard deviation for each measurement. 

## step 1: load feature name into R
featureName

## step 2:  extract mean and standard deviation of each measurements
featureIndex 
finalData 
colnames

# 3. Uses descriptive activity names to name the activities in the data set

## step 1: load activity data into R
activityName 

## step 2: replace 1 to 6 with activity names
finalData$activity

# 4. Appropriately labels the dataset with descriptive variable names.

# 5. From the data set in step 4, creates a second, independent tidy dataset with the average of each variable for each activity and each subject.
groupData 


