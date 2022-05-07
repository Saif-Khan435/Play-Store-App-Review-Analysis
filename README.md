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
In this step I explored the previously loaded datasets and tried to find some insights from the data. I found that Play Store Data had 1 column with float datatype and 12 columns with object datatype and User Reviews had 2 columns with float datatype and 3 columns with object datatype. Pandas has functions like head(), tail(), info(), describe(), etc. that help us to explore the data and understand the data.

## Data Cleaning
In this step I looked for null and missing values by using isnull() and sum() functions on the Play store data and user reviews dataset. I found that Play store data had about 1473 null values in Ratings column, 1 null in Type and Content_Rating columns each and 3 null values in Android_Ver column and User reviews had about 26868 null values in Translated_Review column and 26863 null values in Sentiment, Sentiment_Polarity and Sentiment_Subjectivity columns each. I handled these null by either replacing them or removing the rows that consisted these null values.

## Data Preparation
Here I checked if all the columns have appropriate datatypes and handled unnecessary duplicate values in columns as they would cause redundancy in the data.
