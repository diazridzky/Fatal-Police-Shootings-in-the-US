# Analysis of US Police Shootings: Project Overview
This project is an analysis on the data containing every fatal police shooting in the US with the purpose of understanding the trend of these incidents and trying to solve what factors made the shootings occurred.

Link to the dataset: https://www.kaggle.com/andrewmvd/police-deadly-force-usage-us

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
* Parsed the month and year out of date then made new columns for them
* Grouped the age column then made a new column named generation
* Renamed the state column to code then made a new column named state that has been mapped with the state's real name instead of abbreviation

# Exploratory Data Analysis & Data Visualization
After I cleaned and engineered the data, I analyze the data so I could get an insight out of it.

Below are a few highlights from my analysis.

![by_mental_illness](https://user-images.githubusercontent.com/60106788/136690836-34be11ca-fe4c-4a89-9304-eba70889c192.PNG)
![race_ _gen](https://user-images.githubusercontent.com/60106788/141271193-ec9947e0-152e-4431-aa2c-55574741a6b9.PNG)
![by_gen](https://user-images.githubusercontent.com/60106788/136727027-5703a3f7-5448-4ab4-a160-74258ad5859b.PNG)
![by_item](https://user-images.githubusercontent.com/60106788/140647332-62928e7f-d64f-4fe2-88e0-67089e9671f3.PNG)
![by_race](https://user-images.githubusercontent.com/60106788/140647320-1b357855-f756-4f14-a5d4-2f2b5b7e5900.PNG)
![top_5_cities](https://user-images.githubusercontent.com/60106788/140647914-c4ec7546-75da-4429-b362-7ca8e9501b82.PNG)
![heatmap](https://user-images.githubusercontent.com/60106788/136691246-db79eca0-82fb-48e1-8ac0-0f487268fb87.PNG)

# Geographical Plotting
After I did some analysis I made a geographical plotting for cases in every US state using Plotly Express.

![states_cases](https://user-images.githubusercontent.com/60106788/136691244-441fbcb3-777a-4488-878b-319b804fea1e.png)


