<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/ironhack.png">

# Data-Cleaning
With regard to getting the right data for a project, a survey of data scientists in 2016 found that 79 percent of their time is spent on data preparation. The time spent across the major tasks in the project was distributed as follows: collecting data sets, 19 percent; cleaning and organizing data, 60 percent; building training sets, 3 percent; mining data for patterns, 9 percent; refining algorithms, 4 percent; and performing other tasks, 5 percent (CrowdFlower 2016).

Kelleher, John D.. Data Science (MIT Press Essential Knowledge series) (p. 66). The MIT Press. Edición de Kindle. 

**Luis Fernando López Corrales for IronHack**

## Data
The data is from Kaggle, an open data science hub where you can find free data to work with, among other things.
https://www.kaggle.com/teajay/global-shark-attacks

## Scope
This was one of the first projects in the IronHack bootcamp, where the main goal was merely dive into the cleaning of data. So, the data set was quite messy...
In this repo you can find the csv before the cleaning and after the cleaning. The one cleaned is 'sharks_clean_lflc.csv'

## Before cleaning

### Date
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/date_before.PNG">

### Injury
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/injury_before.PNG">

### Species
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/species_before.PNG">

### Age
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/age_before.PNG">

## After cleaning

### Date
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/date_after.PNG">

### Injury
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/injury_after.PNG">

### Species
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/species_after.PNG">

### Age
<img src="https://github.com/luisferlc/Data-Cleaning/blob/master/images/age_after.PNG">

## Summary of main cleaning points
* Drop duplicates (like the last columns in the original dataset)
* Eliminate syntax errors
* Convert each column to it's corresponding type
* Standarize the data (like the Species column in this data)
* Manage NA's


Also, you can check this article which is a complete guide to do a good cleaning: https://towardsdatascience.com/the-ultimate-guide-to-data-cleaning-3969843991d4
