# Cleaning and Getting Data - Project
Repository for the Getting and Cleaning Data course project

What we have here is the R script called `run_analysis.R` which does:
* Get the data from the dataset
* Loads information about activity and feature
* Loads columns from training and test data that reflects a dispersion measure.
* Loads activity and subject for each dataset and merges those with the dataset.
* Merges the 2 datasets.
* Converts into factors the columns `activity` and `subject`
* Creates a tidy dataset with the mean for each subjet and activity pair.

You can see the results in `tidy.txt`
