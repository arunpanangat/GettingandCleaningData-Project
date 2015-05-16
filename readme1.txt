The program run_analysis.R was created as part of the Project on Getting and Cleaning Data module of the Data Science Specialization from Coursera.

The code performs the following functions

1.Download the file from " https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"" to the data folder.( creates a folder if none exists)

2.Unzips the file


3.Prints the list of the files in the directory UCI HAR Dataset

4. Reads the data from the Activity files , Subject files & Features files through 3 separate pieces of code

5. Looks at the properties of the 3 files

6. Then it merges  the training and test data sets and does and Rbind on the data tables


7. Next task performed is the naming of variables

8. then it merges the columns to get dataframe "data"

9. Next function performed is extraction mean and Std.Dev for each measurement

10. Afyer that , it  creates subsets of selected variables and creates descriptive names for activities in data set. these labels are further refined to creating appropriate labels.

11. The last step is to create cleaned data set (tidydata.txt) as output


