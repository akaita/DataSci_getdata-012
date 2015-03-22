Getting and Cleaning Data Course Project
========================================

This is a repository for the code written for the Getting and Cleaning Data Course by Johns Hopkins University and Coursera.

## Usage

* Unzip the source file (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive. For example: C:\Users\yourname\Documents\getdata-012
\

* You should now have a directory called: C:\Users\yourname\Documents\getdata-012
\UCI HAR Dataset\

* Copy run_analysis.R into C:\Users\yourname\Documents\getdata-012
\UCI HAR Dataset\

* In RStudio: setwd("C:\\\\Users\\\\yourname\\\\Documents\\\\getdata-012\\\\UCI HAR Dataset\\\\")

* In RStudio: source("run_analysis.R"). The resulting clean data will be stored in a file called "data_set_with_the_averages.txt"

* In RStudio, you can just do: data <- read.table("data_set_with_the_averages.txt") to read the data
