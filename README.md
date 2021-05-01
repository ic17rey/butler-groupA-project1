
# How Player Height Affects the NBA
### Team Members
*Lindsay Reynolds, Nick Sheets*
### Project Description
Examine the height of NBA players to determine if height impacts performance or salary  

##### Gather player info and stats  
* name 
* team
* height
* other personal info like college
* points per game
* blocks per game
  * not able to include this stat in analysis 
* rebounds per game
* assists per game
* salary

##### Analyze data looking for the impact of height on performance or salary
* height v. ppg
* height v. blocks per game
  * not able to include this stat in analysis  
* height v. rebounds per game
* height v. assists per game
* height v. salary  

##### Analyze the data looking for impact of performance on salary
* use similar plots as above

##### Research Questions to Answer
Players:  
* What is the average height of an NBA player?
* Does height impact performance (ppg, blocks, rebounds or assists per game)?  
  * Do taller players score more often?
  * Do taller players make more blocks? 
    * expecting strong correlation
    * not able to include this stat in analysis
  * Do taller players make more rebounds?
    * expecting strong positive correlation
  * Do taller players have more or less assists per game than shorter players?
    * potential for negative correlation     
* Does height impact salary? 
  * Do taller or shorter players make more money?
  * Is there any correlation?
* Which stats impact salary?
  * How strongly are points and salary correlated?
  * Is there correlation between rebounds and salary?
  * Is there correlation between assists and salary?   

##### Research Questions that were not pursued
Teams:
* What teams have the highest average player height and what teams have the lowest?
* Does height have an impact on W/L percentage?

### Datasets/Resources to be used  
* [Kaggle:  NBA Players, Justinas Cirtautas](https://www.kaggle.com/justinas/nba-players-data)  
* [Sports Reference LLC: Basketball-Reference.com "2020-21 NBA Player Contracts" (4/22/2021)](https://www.basketball-reference.com/contracts/players.html) 

### APIs considered  
* [NBA-API:  API available as a pip install](https://pypi.org/project/nba-api/)  
* [rapidapi.com](https://rapidapi.com/blog/nba-basketball-stats-api/#:~:text=Updated%3A%20The%20API%2DNBA%20is,TheRundown)  
* [sportradar.com](https://developer.sportradar.com/docs/read/Home)

 
### Rough Breakdown of Tasks  
#### Jupyter Notebook 1: Describe the data exploration and cleanup processes
- [x] Identify the sources to be used and gather the data
- [x] Determine years to be used and what data to retrieve from where
- [x] Import the data to a jupyter notebook for analysis
- [x] Clean the data for any duplicates or other issues with pandas
- [x] Make any updates needed for formatting
- [x] Put the data into a dataframe
- [x] Load the dataframe to csv to retrieve for notebook 2
- [x] Determine best plots to use


#### Jupyter Notebook 2: Data Analysis
- [x] Using the dataframes created, create the plots needed to help analyze the data
- [x] Perform calcs as needed for averages or binning
- [x] Add linear regression models to plots and look at relationships
- [x] Look at correlation and p-values
- [x] Use this info to make observations about the research questions 
 
#### Jupyter Notebook 2 also includes user input opportunity
* To see plots in Jupyter Notebook 2 a user input must be entered, even if it is only to hit enter in the user input box

#### Prepare a summary of observations
#### Prepare for the presentation  
Presentation of PowerPoint slides
