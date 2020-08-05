### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The only necessary libraries to run the code here beyond the Anaconda distribution of Python are Tweepy and json.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

The goal of this project was to practice data wrangling, which includes gathering, assessing, and cleaning data. I gathered the data from 2 outside sources: the Udacity servers and Twitter.

In this analysis, I wanted to find interesting insights from tweets by WeRateDogs, which is a popular Twitter page that playfully rates dogs on a 10-point scale, with the rating commonly being above 10/10. I combined the page's Twitter 2015-2017 archive with Udacity's associated breed image predictions, as well as tweet metadata such as retweet and favorite counts to show the following:

1. A distribution of dog ratings over time
2. The correlation betweet retweet count and favorite count and dog rating
3. The most popular breeds
4. The most popular dog names

## File Descriptions <a name="files"></a>

There is one notebook in the repository, wrange_act.ipynb, that goes through the data analysis process for analyzing this dataset and answering the above questions. Also included is the one .csv file that was downloaded from the Udacity classroom workspace, twitter_archive_enhanced.csv. This is the tweet archive that Twitter provided to Udacity.

The results are published in the report act_report.pdf. A wrangle_report.pdf is also included, which details the wrangling steps of the project.

Note that one of the datasets was obtained using the Tweepy library to query the Twitter API. To do this, an app through a Twitter Developer's account must be created. 

## Results<a name="results"></a>

The main findings of the project can be found in act_report.pdf.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Twitter and Udacity for the data. This project was part of Udacity's Data Analyst Nanodegree program.
