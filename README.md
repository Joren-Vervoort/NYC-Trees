# Data Cleaning: NYC-Trees

- Data preprocessing - nyc-trees
- Repository: nyc-crashes
- Type of Challenge: Learning
- Duration: 1 day
- Deadline: 12/03/2021 04:00 PM
- Team challenge : solo

## Mission objectives

Be able to use pandas
Be able to clean a data set
Be able to do prepare a data set for a machine learning model

## The Mission
The Department of Environmental Conservation, from New York city, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York city, whether young or old, to go to the nearest tree in their street and gather information about that tree. This is all in an effort to make the population aware that nature is important, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy.


## Must-have features

- The dataset contains no missing values ("" or null)
- No duplicates
- Values are consolidated
- Data format is correct
- No blank spaces (ex: " I love python " => "I love python")

## Nice-to-have features

The more rows of data you use, the better. However, pay attention that the more data you have, the longer each operation needs to execute.
Add new features computed using the features present that you think are going to be useful.
Apply the preprocessing steps needed so that a future machine learning model can make the best use out of it (feature selection, feature engineering, feature normalization, and resampling)

## The Repository

In this repository there are different versions of cleaned data from the same origin data_100000.csv file:
1. Clean_Data_GOOD_ENOUGH

Each of these contain a .ipynb file containing the cleaning process and two .csv files with the results of this cleaning process.

### Description of the different versions

1. Clean_Data_GOOD_ENOUGH

In this version of the cleaned data, the main focus is on the "tree_id", if this value is not present in a row, or has a duplicate in the dataframe, it will have been removed. The rest of the file is than processed as described in the .ipynb file. 

The results consists of 2 different .csv files:
- Clean_Data_GOOD_ENOUGH_unofficial.csv
- Clean_Data_GOOD_ENOUGH_official.csv

The reason for having 2 different .csv files is because of the mission. The goal was to make the population aware that nature is important. This does not mean that every "Volunteer" will return accurate/official data. This is why there is a Clean_Data_GOOD_ENOUGH_unofficial.csv dataset with the results of the "Volunteers" included and a Clean_Data_GOOD_ENOUGH_official.csv where the data of the "Volunteers" is excluded and for scientific purposes.

## Things to improve

- Improving the run time of the Clean_Data_Good .ipynb file
- More regex checks of the values of the different column to ensure the data is filled in correctly.

# THANK YOU FOR READING!

