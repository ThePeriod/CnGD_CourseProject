# Cleaning and Getting Data - Project
Repository for the Getting and Cleaning Data course project

What we have here is the R script called `run_analysis.R` which does:
1 Get the data from the dataset
2 Loads information about activity and feature
3 Loads columns from training and test data that reflects a dispersion measure.
4 Loads activity and subject for each dataset and merges those with the dataset.
5 Merges the 2 datasets.
6 Converts into factors the columns `activity` and `subject`
7 Creates a tidy dataset with the mean for each subjet and activity pair.

You can see the results in `tidy.txt`
