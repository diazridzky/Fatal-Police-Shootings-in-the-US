# Analysis of US Police Shootings: Project Overview
This project is an analysis on the data containing every fatal police shooting in the US since Jan 1st, 2015 collected by The Washington Post. I engineered features from the generation of the victim's age to mapping the state's real name, made several graphs for each features, and created geographical plotting for every state.

Link to the dataset: https://www.kaggle.com/andrewmvd/police-deadly-force-usage-us

# Motivation
I'm trying to understand the trend of police shootings in the US plus trying to solve what factors made the shootings occured.

# Code and Libaries Used
* Python Version: 3.9.5
* Packages: pandas, matplotlib, seaborn, plotly

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
* Filled null values with 'Unspecified' except age 
* Transformed the gender and race into their real names instead of letters
* Parsed the month and year out of the date then made new columns for them
* Grouped the age column then made a new column named generation
* Renamed the state column to code then made a new column named state that has been mapped with the state's real name instead of abbreviation

# Exploratory Data Analysis
Below are a few highlights from my analysis.

![by_mental_illness](https://user-images.githubusercontent.com/60106788/136690836-34be11ca-fe4c-4a89-9304-eba70889c192.PNG)
![by_gen](https://user-images.githubusercontent.com/60106788/136727027-5703a3f7-5448-4ab4-a160-74258ad5859b.PNG)
![top_ten_states](https://user-images.githubusercontent.com/60106788/136726720-db9a4184-e5da-4f0e-82c4-0d02b111f146.PNG)
![by_race](https://user-images.githubusercontent.com/60106788/136690841-452a0dc0-4730-490c-84ca-1eba6a5f05b5.PNG)
![top_5_cities](https://user-images.githubusercontent.com/60106788/140319313-58348138-260c-4d8a-a367-95ee59f75618.PNG)
![heatmap](https://user-images.githubusercontent.com/60106788/136691246-db79eca0-82fb-48e1-8ac0-0f487268fb87.PNG)
![states_cases](https://user-images.githubusercontent.com/60106788/136691244-441fbcb3-777a-4488-878b-319b804fea1e.png)


