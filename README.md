### WeRateDogs Data Wrangling and Analysis Project - README

Welcome to the WeRateDogs Data Wrangling and Analysis Project! This project showcases the journey of gathering, assessing, cleaning, and analyzing data from the WeRateDogs Twitter account using Python and its libraries.

### Introduction

Real-world data is often messy. In this project, we demonstrate the process of data wrangling, where data from various sources is collected, assessed for quality and tidiness, and then cleaned for meaningful analysis. We present our findings through insightful analyses and visualizations using Python and SQL.

### Project Motivation

WeRateDogs, a Twitter account with over 4 million followers, rates dogs with humorous comments. Our goal is to wrangle and analyze their tweet archive to provide trustworthy insights and engaging visualizations. Although the Twitter archive provides basic information, additional gathering, assessment, and cleaning are needed for more compelling analyses.

## The Data

This project involves working with three datasets:

Enhanced Twitter Archive: Contains basic tweet data for over 5000 tweets. We enhance this archive by extracting ratings, dog names, and dog stages, among other information.

Tweet Image Predictions: This dataset includes image predictions for each tweet, as predicted by a neural network. We obtain this data programmatically using the Requests library.

Additional Data from the Twitter API: We gather retweet and favorite counts for each tweet using the Twitter API and the Tweepy library.

### Project Steps

Gathering Data: We collect data from different sources using various methods as detailed in the "Data Gathering" section of the wrangle_act.ipynb notebook.

Assessing Data: We conduct both visual and programmatic assessments to identify quality and tidiness issues in the datasets. We document at least eight quality issues and two tidiness issues.

Cleaning Data: The identified issues are addressed using Python to ensure the data is accurate and well-structured.

Storing Data: Cleaned data is stored in a CSV file named twitter_archive_master.csv for further analysis.

Analyzing and Visualizing Data: We analyze the cleaned data and create visualizations to uncover insights. We generate a minimum of three insights and one visualization.

Reporting: We document our findings and insights in the wrangle_report.pdf file.

### Insights

Retweets Over Time: The number of retweets shows a decreasing trend over the years.
Tweet Volume: WeRateDogs experienced a significant drop in the number of tweets from 2015 to 2016.

### Conclusion

The WeRateDogs Data Wrangling and Analysis Project demonstrates the process of transforming messy data into valuable insights. By following the steps of gathering, assessing, cleaning, and analyzing, we unveil intriguing trends and patterns within the WeRateDogs Twitter data. 

For more details, refer to the wrangle_act.ipynb notebook and wrangle_report.pdf.
