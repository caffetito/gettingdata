# gettingdata
A peer assesment for the Getting and Cleaning Data on Coursera


1. Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip, rename the folder with "data".
2. The folder "data" and the run_analysis.R script hav to be in the same working directory.
3. Run the run_analysis.R script.
4. The 2 files with cleaned data sets will be generated: 
- merged_data.txt
- data_with_means.txt.
5. Read the file data_with_means with following command:
data <- read.table("data_with_means.txt")

