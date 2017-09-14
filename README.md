# Data Cleaning and Munging
Cleaned, munged, repurposed and transformed data collected from Kaggle and Pew Research Center to interpret and visualize survey results.


GOALS:
Major goals of the Lab 2 are:

1. Convert data in various format into a form that is convenient for in-memory operations. Transform from external storage formats such as xml, sqllite into a common external format, comma separated value (.csv) convenient for exploratory data analysis using R. This allows for easy reading of data into the memory as data frames.

2. Extract (data munging) useful data from raw data collected by real survey instruments. You will use the actual survey document in interpreting the survey results.

3. Repurpose data from a popular domain (such as sports) for consumption by different genre of applications.

4. Transform data using operations such as grouping, categorization and binning to stage them for in-memory analysis. (R is optimized to work well with in-memory data.)

5. Document data cleaning steps using Markdown, a text-based HTML authoring format. This is an essential step in “reproducible research” and is offered within Jupyter platform.

6. Learn and understand the scientific data collection process, surveys, and nature of raw data and the need and motivation for cleaning and munging the data.

This project is divided into three activities.

### Activity 1: Transform XML to data frame to CSV

Use the xml package in R to generate data from the xml file. We will use a simple data set from Washington University to carry out this operation. 

- Input: WU data file in xml: 
- Output: exactly equivalent file in CSV. 
- Process: R and xml package.

### Activity 2: Extract and Repurpose Data

We will use one of the data sets posted European Soccer Data for several years stored in normalized sqlite tables. The data contains mostly lot of technical details about the players and the teams. We want to extract one or two simple csv files with observations that are of interest to common public. One could be about players (player.csv) and the other could be about the teams (team.csv). Think about what you want to “interrogate”, “learn” or “query” about European Soccer. These should drive your meta-data (observations) of data filtered out from the many tables of the original data. Think of this problem as “staging” the data for Q&A (Question and Answer) system such Amazon Alexa. This activity is like creating views from a relational database only that we will be performing that using R and R packages.

- Input: Kagge Sqlite European Soccer Database 
- Output: R data frames persisted in csv files to facilitate easy Q&A
- Process: sqllite to R data frames to csv.

### Activity 3: Convert and Transform Raw Data

Pew Research Center has been collecting data for a long time about social issues using survey approach. We are especially interested in look at the data PRC collected about Gaming, Jobs and Broadband. Clean and munge this data using  methods described in dplyr. Rename observations, rename data categories, remove unwanted observations, null rows, etc. Your guiding principle in these operations is the set of questions you are trying to answer using this data. What do you want to learn from this data? You will have document every change/transformation you make to the data for provenance purposes. 


###### *Note: Further details are mentioned in the inidivual Jupyter notebooks for the activities.*
