# Project: Investigate The TMBD Dataset
This Repo is part of Udacity Data Analysis Nano Degree - Project 2

Please don't just copy past the code.


## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

## Introduction

### Dataset Description 

**This is a TMBD movie data set and I am going to Analyiz it to undertsand**
1. The effect of internet avilability on the Movie industry
  1.1 Does the internet avilability affected people votes
  1.2 When people tends to votes & does it have a releation with how good is the movie?
3. The impact of economical recession on the Movie industry
4. 

**References**
1. https://github.com/palewire/cpi
2. https://github.com/celiao/tmdbsimple/
3. https://www.kaggle.com/tmdb/tmdb-movie-metadata/discussion/58203
4. https://www.kaggle.com/tmdb/tmdb-movie-metadata/discussion/271794
5. https://towardsdatascience.com/the-easiest-way-to-adjust-your-data-for-inflation-in-python-365490c03969

## Note:
1. the TMBD data set is not included in this repository. you can get if from Kaggle.
2. You will need to get your own TMBD token to be able to update the data set through TMDB APIs


## Steps
1. Load data from the csv file
2. Remove raws that has TMBD values equal null/Zero
3. Remove duplicates
4. Call TMBD APIs to update the data 
5. Adjust the budget & revnue values to 2010 to unify the caluclation
6. Removes Raws with Nulls & Zeros
7. Calulate the profit: Profite = Revenue_Adj - Budget_Adj
10. Do your Analysis & answer the questions, plot the graphs

## Data Limitations
- The data is not up to date till today. it will be interesting to compare between the great recession 2007 -2009, & the COVID-19 recession 2020-2021 as their is a significant life style change.
- On line TV producers are not really included. Amazon has only 2 movies, Netflix has only 8 movies included. That can be due to those two companies joined the producers club late. it will be interesting to investigate the difference between the movies they produce and the other industry producers.

## what is next
1. Update the TMDB API calls to be in parralel instead of the current sequential process
2. Use the IMBD API as a second source of data then merge the results with the TMBDs APIs to do the study 
