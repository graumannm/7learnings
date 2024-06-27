# 7Learnings Data Science Challenge
This repository contains a notebook for the data science coding challenge for 7Learnings. The dataset is a time series dataset with wheather data from a number of weather stations. The task is to predict whether it will snow tomorrow. 

# Approach
The approach was to extract the data using Big Query, clean and prepare it for model training using pandas and then train and evaluate the model using a simple logistic regression model as a baseline model using the sklearn library in Python. In 'Future Directions' I discuss potential techniques to improve model performance.

# Overview

### Installations
Install packages that were not included in the requirements.txt fil.e

### Imports
Import packages.

### Introduction
Description of the tasks.

# Part 1.
### Task 1
Extract data and filter for years and wheather stations using Big Query. Save data as a pandas dataframe.

### Task 2
Take a smaller subset from the wheather stations. Clean and prepare the data.
- Remove columns
- Fill missing values
- Inspect outliers
- Feature engineering
- data exploration

### Task 3
Split data into trainig, evaluation and test set. The test set contains the data of tomorrow 15 years ago.

# Part 2
Train classification model on time series data to predict whether it will snow tomorrow 15 years ago using the dataset prepared in part 1.

### Training and validation
I am using a simple logistic regression as a baseline model.

### Testing on tomorrow's data

### Conclusion
Overall conclusions from results

### Future directions
Possibilities on how to improve the results.


