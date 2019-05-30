# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Project Introduction
This was the first project for the General Assembly Data Science Immersion Program. The assignement was to analyze the provided SAT and ACT datasets, augment the analysis with outside researchm, and create a recommendation regarding how to increase participation rates in future years.

### Problem Statement
Given changes in the SAT test itself, as well as the standardized testing landscape in general, how might College Board work to increase the participation rate?


### Overview of the Data 
Test Participation Rates and Scores
-  2017 SAT and ACT Datasets provided by College Board
-  2018 SAT and ACT Datasets prepared by General Assembly Data Immersion Students from 
-  Collected Classroom Cohort 6
Standardized Test Landscape
-  Trends for various state-wide requirements
-  Supplementary data publicly available - See references

## Data Dictionary

The following table describes the features of the combined SAT/ACT dataset

|Feature|Type|Dataset|Description|
|---|---|---|---| 
|state|Object|Both|State Name|
|sat_participation_2017|int64|SAT|Percent class of 2017 who took the SAT|
|sat_language_2017|int64|SAT|Average SAT language score 2017|
|sat_math_2017|int64|SAT|Average SAT math score 2017|
|sat_total_2017|int64|SAT|Average SAT total score 2017|
|act_participation_2017|int64|ACT|Percent class of 2017 who took the ACT|
|act_english_2017|float64|ACT|Average ACT english score 2017|
|act_math_2017|float64|ACT|Average ACT math score 2017|
|act_reading_2017|float64|ACT|Average ACT reading score 2017|
|act_science_2017|float64|ACT|Average ACT scienc score 2017|
|act_composite_2017|float64|ACT|Average ACT Composite score 2017|


### This Project Contains the Following Directory Structure
```
\code - Two jupyter notebooks
1. Importing and Cleaning 
This notebook reads both the SAT and ACT data and performs a variety of functions to examine, and where necessary, clean the data.
2. Analysis and Conclusion
This notebook performs the analysis, summarizes the outside research, and outlines specific recommendations to College Board based on this study.

\data - interim cleaned datafiles  

\images - chart used for presentation
```

### Project Summary

Problem Statement - Given changes in the SAT test itself, as well as the standardized testing landscape in general, how might College Board work to increase the participation rate?

To augment our understanding of the data we were encouraged to look at external sources. Through this research I learned that the standardized testing landscape has a big impact on which students take which tests. The federal government has implemented a 'common core' testing program, and states are required to implement standardized tests. The states have authority to set their own policies. Some use the SAT to meet the requirement. Other use the ACT, tests of their own design, or other purchased test material. Many states change their policy from year to year and this seems to have a major impact on the participation rate for SAT test takers.

It is worth noting that average scores tend to go down when participation goes up, especially if the increase is due to graduation requirements. It would make sense that students who are not college bound aren't as prepared for the test as college-bound students, and therefore wouldn't perform as well. 

The recommendation of this report is that the SAT board pay close attention to how states respond to common core and to build strong relationships with the states. If SAT can help states meet their goals they will be more likely to require, or at least incent, their students to take the SAT.