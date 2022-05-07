# PPOL 670 | Data Science Final Project

## Predicting Voter Turnout in the 2020 Presidential Election

URL of the repository: https://github.com/tg484/Data-Science-Final-Project

Project Website: https://tg484.github.io/Data-Science-Final-Project/

**Authors:**<br/>
Priyasha Chawla<br/>
Tanya Grover<br/>
Deepika Nagesh<br/>
Payal Soneja<br/>

## Overview

#### About the Project
Using Harvard’s Cooperative Congressional Election Study (CCES), we conducted analysis to predict voter turnout. We use ggplot to understand the sample structure and conduct exploratory data analysis. We also perform geospatial analysis to see how voting behavior changes with respect to different geographies. We then constructed three machine learning models to predict voter turnout using different demographic and profile questions. We compared the predictive accuracy of the three models to select the best model. This model was then implemented on our testing data to predict voting behavior.

#### Data Description and Sources 

We use [Harvard’s Cooperative Congressional Election Study (CCES)](https://cces.gov.harvard.edu/) to predict voter turnout. The CCES is a national stratified sample survey that validates respondents’ voter behavior by matching voter files to their survey data. The CCES is a nationally representative stratified survey administered every two election years.
The CES Common Content has five parts - sample identifiers, profile questions, pre-election questions, post-election questions, and contextual data. We use variables from the following modules - profile questions, sample identifiers, pre and post-election questionnaires. Between September and October, 61,000 American adults were recruited for the pre-election survey; more than 50,000 of these respondents also completed the post-election survey in November. The post-election questionnaire collects information about whether a respondent voted in the 2020 election - we use this as our predictor variable to create a binary classification model.

#### Technology Used
* R Programming [ R Script and R Markdown]

## Description of files:
A  brief description of the files/directories in the repository    
* The README.md file provides a brief overview of the objective of the project and a brief description of the files/directories in the repository
* The index.Rmd file contains seperated code chunks to perform data cleaning and analysis
* The index.html file contains the knitted output of the proect
* The gitignore file contains all the data that was used for the project

## Instructions to replicate analysis: 

1. Install the required packages as listed below:
	* tidyverse
	* lubridate
	* ggiraph 
	* tigris   
	* sf
	* leaflet
	* patchwork
	* tidymodels
	* themis
	* rpart.plot
	* vip
	* parsnip
	* dials
	* ranger

2. Download the `voting_data.csv` from the Harvard Cooperative Election Study in the `data` folder. 

3. The extraction code automatically downloads the data in the `data` folder which is provided as an empty directory in the Data-Science-Final-Project repository. 