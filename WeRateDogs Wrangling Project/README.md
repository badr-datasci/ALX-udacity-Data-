# @WeRateDogs Twitter Data Wrangling
## by Badreddine Mouttaqui


## Dataset

> The main purpose of this project is to use real world data to wrangle (gather, assess, clean) and then apply analysis with visualizations

The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog with a denominator of 10 and the numerator is usually higher than 10 to show how lovely the dog is.

There are three pieces of data that will be gathered, cleaned, and then merged into a final DataFrame stored in order to analyze.


## Steps :

Data Wrangling these three datasets followed the progression below :

> ##### 1. Gathering data :

The data was gathered from the three following sources:

1. the Twitter Archive file stored in the (twitter_archive_enhanced.csv)
2. the tweet image prediction (image_predictions.tsv) using the Requests library to download
3. the JSON tweets archived from WeRateDogs Twitter API, I tried to use the twitter API developer, but i kept getting a non approved Twitter developer account application every 2 days. So, after a lot of attempts, I used the tweet-json file provided in the Session.

##### 2. Assessing Data :

After gathering data from the above mentioned sources, two types of assessment were used the datasets :

-  Visual assessment : each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. 

- Programmatic assessment : pandas' functions and/or methods are used to assess the data (info, describe, duplicated ...etc).


##### 3. Cleaning data : 

The data quality and tidiness problems were cleaned using the three steps :

Define - Code - Test.

Below, a summary of processes used:

1. Creating a dog_breed column from the image_prediction to use in the analysis
2. Merging the clean versions of twitter_archive, image_prediction, and json_tweets dataframes 
3. Creating one column for the various dog types: doggo, floofer, pupper, puppo 
4. Deleting the retweets
5. Droping duplicates from image_prediction
6. Removing columns no longer needed in the analysis section
7. Changing tweet_id from an integer to a string
8. Changing the timestamp to correct datetime format
9. Correcting dog naming issues
10. Standardizing dog ratings




