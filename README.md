# Analysis of US Police Shootings: Project Overview
This project is an analysis of the dataset of every fatal shooting in the US since Jan 1st, 2015 by The Washington Post. The Post began tracking more than a dozen details about each killing by culling local news reports, law enforcement websites and social media and by monitoring independent databases such as Killed by Police and Fatal Encounters.

Link to the dataset: https://www.kaggle.com/andrewmvd/police-deadly-force-usage-us

# Code and Libaries Used
* Python Version: 3.9.5
* Packages: pandas, matplotlib, seaborn, plotly express

# Columns
* ID
* Name
* Date
* Manner of Death
* Armed
* Age
* Gender
* Race
* City
* State
* Signs of Mental Illness
* Threat Level
* Flee
* Body Camera

# Data Cleaning
After importing the data, I needed to clean it up then made the following changes and created the following variables:
* Fill null values with Unspecified except the age column
* Transformed the gender and race columns into their real names instead of letters
* Parsed the month and year out of the date column then made new columns for them
* Grouped the age column then made a new column named generation
* Renamed the state column to code then made a new column named state that has been mapped with the state's real name instead of abbreviation


