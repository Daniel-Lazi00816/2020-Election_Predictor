# 2020-Prediction-Model-
**Problem Statement:**
With the 2020 Democractic Primary winding down we read, and hear more and more about youth turnout levels versus elder turnout levels. Senator Sanders, the main challenger to now Joe Biden rests his campaign on the hope of younger voters turning out, while the vormer Vice President is looking to keep together the Obama coalition now twelve years older. Prediciting voter turnout in and of itself is a difficult calculation to make and one that has a high variation of methods and processes. 

This project, will look to use  Bayesian inference and MCMC with prior data gotten from the previous Democratic primary cycle methods to create posterior distributions 

the preceeding notebook/notebooks and code will look to answer the questions, how many people from each age bucket do we expect to vote in upcomming elections?

**What are My Metrics:**


**Executive Statement:**
The beggining of the notebook takes a look at how many polls we are dealing with per state. Of course, there is a lot of polling done in states that are consequential to the election process, and that bores out when looking at a bar graph represented towards the center of the notebook. 

**Data Dictionary:**
| Name of CSV File            | Description of CSV File                                                                      |
|-----------------------------|----------------------------------------------------------------------------------------------|
| president_primary_polls.csv | From 538, a list of Democratic Primary polls                                                 |
| president_polls.csv         | From 538, a list of presidential match-up polls                                              |
| electoral-college-votes.csv | A list of the amount of electoral votes up for grabs in each state                           |
| 2016_az.csv                 | A list of the breakdown county by county of votes in the 2016 Democratic Primary in Arizona  |
| 2016_fl.csv                 | A list of the breakdown county by county of votes in the 2016 Democratic Primary in Florida  |
| 2016_ill.csv                | A list of the breakdown county by county of votes in the 2016 Democratic Primary in Illinois |
| 2016_ohio.csv               | A list of the breakdown county by county of votes in the 2016 Democratic Primary in Ohio     |
| fl_demogr                   | From the U.S. Census Bureau a breakdown of the demographics in Florida                       |
| illi_demogr                 | From the U.S. Census Bureau a breakdown of the demographics in Illinois                      |
| ohio_demogr                 | From the U.S. Census Bureau a breakdown of the demographics in Ohio                          |
| az_demogr                   | From the U.S. Census Bureau a breakdown of the Demographics in Arizona                       |
