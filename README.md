# Getting-and-Cleaning-Data


-Unzip the source ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )

into a folder on your local drive, say C:/Users/<YourName>/Documents/R/Coursera/data/

-Put run_analysis.R to C:\Users\yourname\Documents\R\data\

and then: source("run_analysis.R")

-The latter will run the R script, it will read the dataset and write these files:

signals_Aggby_subject.txt
signals_all_subject.txt

-Use data <- read.table("signals_Aggby_subject.txt") to read the latter.  

