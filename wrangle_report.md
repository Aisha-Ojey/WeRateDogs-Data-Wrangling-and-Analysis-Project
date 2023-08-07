# Data Wrangling Report: WeRateDogs Twitter Data
### Introduction
This report details the comprehensive data wrangling process undertaken for the WeRateDogs Twitter page. The wrangling process encompassed three distinct datasets, involving the stages of Data Gathering, Data Assessment, and Data Cleaning. The primary objective was to transform raw data into a refined and structured format suitable for subsequent analysis.

### Data Gathering
Three datasets were collected to initiate the data wrangling process:

Enhanced Twitter Archive: This dataset, named enchanced_twitter_archive.csv, was provided within the Udacity classroom. It includes essential information such as tweet_id, dog name, and dog type.

Image Predictions: Acquired programmatically through the Requests library, the image_prediction.tsv dataset was fetched from the Udacity Server using the URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv. This dataset comprises predictions of dog breeds based on images in the tweets.

Twitter API Data: The third dataset, in JSON format, was extracted from the Twitter API using appropriate API keys. The data was read line by line and converted into a structured dataframe.

### Data Assessment
During the assessment phase, both visual and programmatic techniques were employed to identify data quality and tidiness issues. A total of eight data quality issues and three tidiness issues were identified. Noteworthy data quality issues encompassed incorrect datatypes, empty observations represented as "None," as well as invalid entries within the datasets. Tidiness concerns included the consolidation of dog-related columns into a single column and the absence of retweet count and favorite count data within the df_archive dataset.

### Data Cleaning
Data cleaning commenced by creating backup copies of each dataset to ensure data integrity throughout the process. Using the Define-Code-Test framework, each identified quality and tidiness issue was methodically addressed, with a clear documentation of the steps taken. Subsequent to resolving these issues, additional necessary cleaning procedures were executed. The refined datasets were then consolidated into a master dataframe and stored as a CSV file, setting the stage for subsequent analysis.

### Analysis and Visualization
The master dataframe was subjected to analysis and visualization to extract insights from the data. Notable findings include:

A discernible decrease in retweet counts over the years.
A diminishing number of tweets on the WeRateDogs Twitter page, with a pronounced drop between 2015 and 2016.
Conclusion
The data wrangling process yielded a more structured and refined dataset, poised for deeper analysis. Null values and invalid observations were systematically removed, ensuring the quality and reliability of the data. Through meticulous cleaning and organization, the data is now primed for comprehensive exploration and insights into the captivating world of WeRateDogs Twitter activity.


```python

```
