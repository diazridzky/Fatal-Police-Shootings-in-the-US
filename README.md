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
![by_gen](https://user-images.githubusercontent.com/60106788/136690896-85d6938f-1bdb-471c-8820-609fb4eefb6d.PNG)
![by_race](https://user-images.githubusercontent.com/60106788/136690841-452a0dc0-4730-490c-84ca-1eba6a5f05b5.PNG)
![heatmap](https://user-images.githubusercontent.com/60106788/136691246-db79eca0-82fb-48e1-8ac0-0f487268fb87.PNG)
![states_cases](https://user-images.githubusercontent.com/60106788/136691244-441fbcb3-777a-4488-878b-319b804fea1e.png)


