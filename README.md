# Class 1 Survey Data Analysis

## Project Description

This repository contains the Class 1 survey dataset and the R Markdown code used to analyze the survey data. The project is part of an Advanced Data Analysis exercise designed to practice importing, cleaning, summarizing, and analyzing survey data using R.

## Files Included

* `class1_survey.csv`: Class 1 survey dataset used for the analysis
* `analysis_code.Rmd`: R Markdown code used to import, clean, and analyze the survey data
* `README.md`: Description of the project, dataset, and analysis code

## What the Code Does

* Imports the Class 1 survey dataset from the Advanced Data Analysis GitHub repository
* Determines the number of observations and variables in the dataset
* Renames the survey variables using shorter and more descriptive names
* Determines the types of variables in the dataset
* Checks the birth day and birth month variables for missing and unusual values
* Converts the birth day and birth month variables to numeric variables
* Treats birth days outside 1–31 and birth months outside 1–12 as missing values
* Calculates the median birth day and birth month
* Creates a new variable called `bseason` based on Northern Meteorological seasons
* Uses frequency tables to check the season coding
* Uses `addmargins()` to determine the number of classmates born in each season
* Examines which season has the most classmates' birthdays

## Dataset Description

The Class 1 survey dataset contains responses from 27 classmates and includes 27 variables. The variables include information about preferences, interests, academic program and specialization, statistical software experience, R experience, coding comfort, birth day, birth month, country, state, city, and highest education level.

The birth day and birth month variables were examined for missing and unusual values. After cleaning these variables, a new birth season variable was created to classify respondents into winter, spring, summer, or fall according to Northern Meteorological seasons.

## Results

The analysis found that Fall had the largest number of classmates' birthdays, with 12 classmates born in Fall. There were 2 classmates born in Spring, 5 in Summer, and 3 in Winter. Five classmates had a missing birth month.

## How to Run the Code

1. Download or clone this repository to your computer.
2. Open `analysis_code.Rmd` in RStudio.
3. Make sure the required R packages are installed.
4. Run the R Markdown code in RStudio.
5. The analysis will import and analyze the Class 1 survey dataset.

## Author

* Name: Biniyam Dana
* Course: Advanced Data Analysis (ADA)
