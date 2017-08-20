# Coursera: Getting and Cleaning Data Course : Course Project

This repository contains course project, made for the Coursera's "Getting and Cleaning Data" course.
Files in this repo:

1. run_analysis.R - script, that make all the computation, that are need to be made, according to course project task.
2. README.md - this file
3. README_RU.txt - source dataset's readme file translated into my native language
4. features_info_RU.txt - source dataset's features_info file, translated to my native language
5. LICENSE - MIT license file
6. .gitignore - git ignore file

**Usage:**

1. Get run_analysis.R somehow (download or git clone)
2. Run run_analysis.R in RStudio

**What script does:**

1. If source dataset doesn't exists, download it from the website and extract from zip
2. Load features and activities names
3. Load train and test data
4. Merge train and test data into single dataframe
5. Remove unneded data features from dataframe
6. Get average data per subject and per activity
7. Save the last mentioned data into tidy.txt file