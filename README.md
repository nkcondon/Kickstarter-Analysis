# Kickstarting with Excel

## Overview of Project
	Provide data analysis over 4,000 crowdfunding projects from 19 countries from 2009-2017 to uncover any hidden trends. 
These projects are associated with entertainment, publishing, food and technology.  The analysis is to look at the outcome 
of the campaigns for futures insights on their success.  Upon reivew, Theater project fundraising represented 34% of the projects with a 60% success 
in regards to outcomes. (Number_of_Projects_Per Parent_Category.png).

### Purpose
	The purpose is to review the Kickstarter dataset and prepare an analysis on the relationship between theater outcomes by launch date.
Secondly, perform an analysis for the subcategory "plays" based on outcomes and goal amount ranges and create a chart.

## Analysis and Challenges
	

### Analysis of Outcomes Based on Launch Date
A pivotal table was created from the data set; Parent Category was filtered to "Theater" and Year Filtered "All".
Colums are outcomes (Successful, Failed, Canceled) based on launch date and Rows are the months of the year; 2009-2017.
The results are as follows:

![screenshot](https://github.com/nkcondon/Kickstarter-Analysis/blob/main/Pivot%20table.PNG)

The data reflects that failed and canceled outcomes remained somewhat consistant and successful outcome
showed a steady decline from July to December with a slight bump up in October (Theater Outcomes Based on Launch Date.png).
Average Donation per month declined from January's donation was 28% at December.
(Average Donation png.)




### Analysis of Outcomes Based on Goals
 The data represented in the Outcomes Based on Goals graph was filtered to subcategory "plays".  
There were 1047 plays reviewed over 2009-2017 and the analysis breaks down the plays by
outcome (success, failed, canceled) in relation to goal dollar range. Using the COUNTIFs function in EXCEL
, ranges were broken into 5,000 dollar increments from 1,00 to 49,999 and last category over 50,000. 
(See Outcomes Based On Goal.png)
To note, none of the plays were canceled during this timeframe. 


### Challenges and Difficulties Encountered
On reflection, completing the challenge was a positive exercise in putting concepts learned in class together.
The biggest challenges are submitting the assignment in GITHUB (still not sure if it will be submitted properly) and the logic used in COUNTIFs function. It was unclear why I had to 
enter the ending range in a seperate criteria versus the first criteria. 





## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. That success rate of theater outcomes peak in May/June  and decline through December.  Thus successful
and failed outcomes are probably equal in December.  
2.Failed and canceled outcomes are consistent throughout the year


- What can you conclude about the Outcomes based on Goals?
The higher the goal, may increase the risk for an outcome of failure.
The percentage of success seems to be with a lower goal with the exception of 35,000-40,000. 



- What are some limitations of this dataset?
It is about reaching the goal (process measure) and not about an outcome of the project.
I looked at average donations, backers, type of project, etc; could not find the 3rd "why" of 
success. I would probably add measures for the project itself.


- What are some other possible tables and/or graphs that we could create?
Add complete dataset statistics.
Develop some information regarding the 'blurb' column; maybe see a trend in the themes.
