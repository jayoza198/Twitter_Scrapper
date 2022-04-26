# Twitter_Scrapper
This is the part 1 of Twitter Sentimental Analysis

1.	Gathering/Fetching the data
-	Using twitter’s developer platform API’s to fetch the tweets using tweepy.
-	Then using pandas and performing basic operations on gathered data
-	The data gathered was around 5000 tweets.
-	It was then processed by deleting the ‘Retweets’ and ‘\n’.
-	This final data was converted in an Excel file having around 3600 tweets.

2.	Analyzing the tweets from the fetched data
-	The data fetched was first cleaned by deleting the hyperlinks, any special characters, numbers, etc.
-	Each tweets was given a ‘Subjectivity’ and ‘Polarity’
-	Plotting a word-Cloud helped to understand most number of keywords in the dataset
-	Creating a function to compute the sentimental analysis for the tweets
-	This was broadly classified into ‘Positive’, ‘Neutral’, and ‘Negative’ tweets
-	Further, we plotted the Sentimental analysis graph Subjectivity VS Polarity
-	Also plotted the Sentimental count tweets which were classified into Positive, Neutral and Negative tweets.
