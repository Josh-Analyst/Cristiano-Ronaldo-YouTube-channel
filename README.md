## **Cristiano Ronaldo YouTube channel: Analysis of Viewer's Perception**

## **Introduction**
This project objectives is to analyze the perception of the Cristiano Ronaldo Youtube channel. The analysis includes data gathering, data assessment and cleaning, data preprocessing, sentiment analysis, and data visualization.

## **Data Gathering**
On the 16th of August, I scraped 57 videos YouTube data and 225, 901 comments from YouTube using the Python library YouTube's API. The timeframe for this comment was between 14th of October 2024 to 16th of October 2024.I collected the video data seperately and comment data seperatrly.

## **Data Assessment and Cleaning**
During the Assessment and cleaning face, i check for duplicates, missing columns and uncessary column. i filled the missing columns and clean the neccessary columns

## **Data Preprocessing**
This proceess is based manly on the comment column, where extract emojis, uncessary symbols. The comments are standardized, removing repeating characters, stop words, punctuation, and emojis. The remaining words are lemmatized for further analysis.

## **Sentiment Analysis**

For this step, I used the sentiment.polarity method of TextBlob class to get the polarity of tweet between -1 to 1. I classified the polarity according to the polarity scores giving to each comment by defining a Negative comment as having a Polarity score of < 0, a Neutral comment as having a polarity score of 0 and a Positive comment as having a polarity score > 0

## **Data Visualization**

The Dataset was analysed and visuals was displayed based on comment sentiments, top videos with comments, comment time activity, most weekday with comment

## **Conclusion**

The Data was analysed based on Viewers perceptions about Cristiano Youtube channel. The following process was used Data Gathering
Data Assessment and Cleaning, Data Preprocessing, Sentiment Analysis, Data Visualization, Communications and Insights. The insights was done based on his youtube channel.
