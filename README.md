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

# Exploratory Data Analysis
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from my analysis.

![by_mental_illness](https://user-images.githubusercontent.com/60106788/136690836-34be11ca-fe4c-4a89-9304-eba70889c192.PNG)
![by_gen](https://user-images.githubusercontent.com/60106788/136690838-eb24019e-949a-41a7-a5da-46ec54eb5ea5.PNG) 
![by_race](https://user-images.githubusercontent.com/60106788/136690841-452a0dc0-4730-490c-84ca-1eba6a5f05b5.PNG)
![heatmap](https://user-images.githubusercontent.com/60106788/136690847-7b1ecdcd-ab25-4981-a63a-ca310f6df800.PNG)
![States Cases](https://user-images.githubusercontent.com/60106788/136690638-12705cf9-ccaa-4eb1-a387-0fed28f4d650.png) 

