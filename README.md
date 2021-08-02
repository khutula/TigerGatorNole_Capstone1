# College Football: The Decline of Defense
### Is college football defense going the way of the dinosaur?
### Team TigerGatorNole: Karina Hutula, Michelle Davis, Darryl Connelly

## Table of Contents
1. [Introduction](#introduction)
2. [Research Questions to Answer](#objectives)
3. [Hypothesis](#hypothesis)
4. [Dataset Used](#dataset)
5. [Limitations](#limitations)
6. [Technologies](#technologies)
7. [Files](#files)
8. [Analysis](#analysis)
9. [Implications and Future Steps](#implications)

<a name="introduction"></a>
### Introduction
The NCAA is interested in how college football games are changing over time to determine if changes are needed to increase its popularity. The NCAA wants to start by determining the direction of defense in college football and its effect on the game. We have been contracted to analyze the last 17 years of college football data to determine if the value of defense is diminishing.

<a name="objectives"></a>
### Research Questions to Answer
* Have average points per game increased over time?
* Have the number of turnovers per game decreased over time?
* Have the total yards per game increased over time?
* Has 3rd down efficiency per game increased over time?
* Has the margin of victory changed over time?
* Are there more explosive plays?
* Are there less punts per game?

<a name="hypothesis"></a>
### Hypothesis
Defensive value may be decreasing as the years progress and may be less important to the success of a team.

<a name="dataset"></a>
### Dataset Used
[College Football Data API](https://api.collegefootballdata.com)

<a name="limitations"></a>
### Limitations
* Prior to 2004, some statistics are not available in this API.
* We did not account for points scored by offense versus defense.
* The dataset does not include bowl games and playoff games.

<a name="technologies"></a>
### Technologies
This project uses: 
* Python Version 3.6.13
* Jupyter Notebook Version 6.1.4
* College Football Data API Key: stored in a variable named api_key in a file named config.py in the directory

<a name="files"></a>
### Files
* [Project_Proposal.docx](Project_Proposal.docx): word document containing the project proposal
* [api_calls.ipynb](api_calls.ipynb): Jupyter Notebook file that performs all API pulls and exports data to csvs
* [data_plots.ipynb](data_plots.ipynb): Jupyter Notebook file reads csvs and performs basic data analysis including plots and linear regressions
* [ttest_analysis.ipynb](ttest_analysis.ipynb): Jupyter Notebook file that performs ttesting on average points per game
* [avg_points_by_season.csv](Output/avg_points_by_season.csv): output of average points scored per game by season for 1970 to 2020
* [metrics_by_season.csv](Output/metrics_by_season.csv): output of all calculated metrics by season for 2004 to 2020
* [teams_points_against.csv](Output/teams_points_against.csv): output of all calculated metrics by season
* [2004_ttest_data.csv](Output/2004_ttest_data.csv): output of all datapoints for 2004 total points scored for ttest to be completed
* [2020_ttest_data.csv](Output/2020_ttest_data.csv): output of all datapoints for 2020 total points scored for ttest to be completed

<a name="analysis"></a>
### Analysis

![Average Points Extended](Output/Average_Points_Extended.png)

![Average Points Scored](Output/Average_Points_Scored.png)

![Average Explosive Plays](Output/Average_Explosive_Plays.png)

![Average Loss of Yard Plays](Output/Average_Loss_of_Yard_Plays.png)

![Average Margin of Victory](Output/Average_Margin_of_Victory.png)

![Average Number of Punts](Output/Average_Number_of_Punts.png)

![Average Standard Gain Plays](Output/Average_Standard_Gain_Plays.png)

![Average Third Down Efficiency](Output/Average_Third_Down_Efficiency.png)

![Average Total Yards](Output/Average_Total_Yards.png)

![Average Turnovers](Output/Average_Turnovers.png)

![Play Type Bar Chart](Output/Play_Type_Bar.png)

<a name="implications"></a>
### Implications and Future Steps
