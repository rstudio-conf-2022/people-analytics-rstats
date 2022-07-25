R for People Analytics
================

### rstudio::conf 2022

by Keith McNulty + Alex LoPilato + Liz Romero

-----

:spiral_calendar: July 25 and 26, 2022  
:alarm_clock:     09:00 - 17:00  
:hotel:           Chesapeake E  
:writing_hand:    [rstd.io/peopleanalytics](http://rstd.io/peopleanalytics)

-----

## Overview

The course will cover some of the most commonly used methods of analysis and inference when working with data related to people, such as performance data and organizational network data. Among other things, you will learn about:
* Typical explanatory analyses conducted on people data
* Common people-related data types 
* Common hypothesis testing methods
* Common explanatory modeling methods
* How to use graphs to model network relationships 
* How to analyze and draw inferences about people networks

You will learn by working through code and data examples with instructors and faculty, including final data projects where you will have a chance to put all your learning into practice.

## Learning objectives

To be able to:
* Understand basic principles of statistical inference and know how to conduct tests of difference in populations based on samples
* Understand how to conduct and interpret a suite of explanatory modeling techniques which are used to analyze common outcome types in people analytics (continuous, binary, ordinal, time-dependent)
* Understand how to construct, visualize and analyze organizational or people networks 
* Use integrated data science documents to execute analyses and explain methods and results based on all the above.

## Is this course for me?

This course will be valuable to you if: 
 
- You currently work or intend to work in a people-related discipline. 

- You have a basic working knowledge of R and RStudio. 

- You are interested in learning applied statistical methods that are commonly used to understand and draw conclusions about the skills, behaviors and attitudes of people and groups.  
 
The course is ideal for someone who is likely to study quantitative social science disciplines to an advanced level, as well as those working in quantitative Human Resources roles in organizations.

## Prework

* **Essential:**  Register for an RStudio Cloud account at https://rstudio.cloud
* *Optional:* Obtain a github account at https://github.com to participate in Github discussions


## Schedule

### Day 1

| Time          | Activity         | Led by       |
| :------------ | :--------------- | :----------  |
| 09:00 - 10:30 | [Preliminaries](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/1-preliminaries.html#1)      | Keith McNulty |
|               | - Welcome and intros   | |
|               | - Review of R fundamentals ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/01-R_fundamentals---SOLUTIONS.html))  | |
| 10:30 - 11:00 | *Coffee break*   | |
| 11:00 - 12:30 | [Explanatory Methods I](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/2-inference_and_linear_regression.html#1) | Keith McNulty |
|               | - Statistical inference and hypothesis testing ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/02A-Statistical_Inference---SOLUTIONS.html))   | |
|               | - Linear regression ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/02B-Linear_regression---SOLUTIONS.html)) | |
| 12:30 - 13:30 | *Lunch break*    | |
| 13:30 - 15:00 | [Explanatory Methods II](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/3-binomial_and_ordinal_regression.html) | Jordan Sparks |
|               | - Binomial logistic regression ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/03A-Binomial_regression---SOLUTIONS.html)) | |
|               | - Ordinal regression ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/03B-Ordinal_regression---SOLUTIONS.html)) | |
| 15:00 - 15:30 | *Coffee break*   | |
| 15:30 - 17:00 | [Advanced Explanatory Methods](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/4-advanced_explanatory_methods.html) | Alex LoPilato |
|               | - Survival analysis ([Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/04-survival_analysis-SOLUTIONS.html))                    | |
|               | - Important methods we couldn't cover              | |

### Day 2

| Time          | Activity         | Led by |
| :------------ | :--------------- | :----- |
| 09:00 - 10:30 | [Network Analysis I](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/5-working_with_and_visualizing_graphs.html#1)       | Keith McNulty |
|               | - Basic graph theory | |
|               | - Working with graphs in R  | |
|               | - Visualizing graphs in R | |
|               | - [Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/05-Creating_and_visualizing_graphs---SOLUTIONS.html) | |
| 10:30 - 11:00 | *Coffee break*   | |
| 11:00 - 12:30 | [Network Analysis II](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/6-graph_metrics.html)       | Rachel Ramsay |
|               | - Paths and distance  | |
|               | - Vertex importance and centrality | |
|               | - Community detection  | |
|               | - Assortativity and Similarity | |
|               | - [Assignment Solutions](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/module-exercises/06-Graph_metrics---SOLUTIONS.html) | |
| 12:30 - 13:30 | *Lunch break*    | |
| 13:30 - 15:00 | Hands-on Project I | Jiena McLellan |
|               | - Option A - [US Grocery Chain Procurement Staff Network](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/7A-Project_US_Grocery_Purchasing_Network.html#1) | |
|               | - Option B - [US Senate Twitter Interaction Network](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/7B-Project_US_Senate_Twitter_Network.html#1) | |
| 15:00 - 15:30 | *Coffee break*   | |
| 15:30 - 16:45 | Hands-on Project II - [Grocery Performance Evaluations](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/8-Project_Grocery_Evaluations.html#1)        | Jiena McLellan |
| 16:45 - 17:00 | [Wrap-up](https://rstudio-conf-2022.github.io/people-analytics-rstats/materials/talks/9-Wrapping_up.html) | Keith McNulty |

## Instructors

Your instructors will be practitioners and R experts from the People Analytics and Measurement (PAM) Team at McKinsey & Company, as well as other support faculty.  The program is designed and led by:

- Keith McNulty, who is an applied mathematician and a leading technical expert and author in the field of people analytics  
- Alex LoPilato, who is a quantitative psychologist with extensive experience in the measurement and analysis of surveys and other psychometric data
- Liz Romero, who is an applied statistician with extensive experience in the engineering and modeling of people-related data

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
