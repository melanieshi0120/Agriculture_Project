# Agriculture_Project

## Project Managers
 - Hua Shi
 - Trevor O'Hearn

## Goal
 - To research the relationship between income and other variables and to determine which one affects the income the most; as well as, do a Regression on the different Regions of the United States of America
 
 # Data Process
 - Clean five tables of Census Data from 2017.
 - Removed columns with more than 20% missing data
 - Removed data outside the 95th percent quantile
 - Created categorical dummy variables for region and land size
 - Took the square root of the target variable
 
 # Linear Models used
 - Scaled the data using the standard scalar
 - Train-test-split the data 
 - Determined the proper feature selection based on 5000 iterations of train-test-splitting the data 
 - Performed three regression models on the overall data as well as the the four separate regions of the U.S
 - Found the best model to be the Ridge Regression
 
 # Feature Explanation
 - The top, and most obscure feature, overall, is the inventory of the farm's horses and ponies
 - The other four top features dealt with either money or land
 - The amount of government funding received or 
 - The efficiency of the land used
 - Market value of equipment on site such as machinery
 
 # Conclusion
 - The horse business is large and has a massive impact on the farming business
 - There is a target amound of land to have and efficient use of that land is important
 - Major assets help determine the farm's ability to thrive in the market
 
 ### Sources
  - https://www.nass.usda.gov/Publications/AgCensus/2017/index.php#highlights
