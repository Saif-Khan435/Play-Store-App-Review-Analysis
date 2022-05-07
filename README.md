# Play-Store-App-Review-Analysis
EDA Capstone Project

## Introduction
Play Store is a platform from where a user can download apps and rate those apps. In this project I look into the play store app data and the review data and try to **find the important features that would help us improve the customer engagement for that app**.

This Project is segregated into many sections and they are :
* Loading Libraries and Dataset
* Data Exploration
* Data Cleaning
* Data Preparation
* Data Visualization
* Analysis Summary

## Loading Libraries and Dataset
I loaded the necessary libraries for the analysis, in which we used Libraries like **Numpy for numerical operations and for n-dimensional arrays**, **Pandas for Data Manipulation and Analysis** and **Matplotlib and Seaborn for Data Visualization**.

I loaded two dataset i.e. Play Store Data and User Review. Play Store Data consisted of columns that were related to the apps like **app size**, **number of installs**, **app category**, **app name**, etc. and User Review consisted of columns like **app name**, **translated review**, ***sentiment*, etc. I loaded the data using the read_csv function of the Pandas library.

## Data Exploration
In this step I explored the previously loaded datasets and tried to find some insights from the data as well as look for null and replaceable values. 
