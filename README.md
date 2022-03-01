# Startup-Funding-Machine-Learning

OVERVIEW

AUTHOR
David Guix Sánchez

GITHUB REP:
https://github.com/DavidGuix/Startup-Funding-Machine-Learning/ 

DATASETS:
investments_VC.csv -> From Crunchbase database with companies up to 2015. Source: Kaggle

dragons_den_dataset.xlsx -> Scraped from the internet with companies from the British TV show ‘Dragon’s Den’ since 2005. Source: Wikipedia 

Shark Tank Companies.csv -> Dataset with companies from the US TV show ‘Shark Tank’ first 4 seasons. Source: Data World

Shark Tank Companies S05_to_S11.xlsx-> Dataset with companies from the US TV show ‘Shark Tank’ from 5th to 11th season. Source: Kaggle

This project analyzes the needs of Next Level, a startup accelerator that is seeking to leverage a machine learning model that will precisely classify companies that will be funded by Venture Capital (VC). In an effort to model this problem, I have collected a dataset of startups around the world, founded from 1980. In addition, I have created a secondary dataset for predictions, based on data from the TV shows ‘Dragons Den’ and ‘Shark Tank’.


BUSINESS PROBLEM

Next Level is a small fictional startup accelerator that is low on capital, currently they have 100k USD to invest in interesting startups. Because of their limited funds, they are looking for a way to better filter companies in the hopes of making the most of their investments. They are aware of the following statistics: 75% of venture-backed startups fail. Under 50% of businesses make it to their fifth year. 33% of startups make it to the 10-year mark. Only 40% of startups actually turn a profit. Given this knowledge, Next Level is targeting startups that they believe have the best opportunity at receiving funding from VC, a sure-fire way for investment profits. For this purpose, they have hired me to create a model classify whether or not a startup will be funded by a VC.


APPROACH 

EDA
I have done a data cleaning process on both sets of data. Please see my repository on EDA for further details.
https://github.com/DavidGuix/Startup-Funding-EDA/

PROJECT ASSUMPTIONS
Based on my knowledge on the topic and the goal of the project (predict the future success of getting VC funding of startups), I focus on predicting the ‘venture’ column as my target.

SHARKS AND DRAGONS
I believe the addition of this data is relevant to this project. At the end of the day these 2 TV shows represent exactly the problem I would like to solve: will a startup get a deal when they face a group of investors???
