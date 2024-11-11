# Squid-Game-Netflix-Twitter-Data
Data analysis of Twitter conversations surrounding Netflix's Squid Game, utilizing R for data cleaning, sentiment analysis, and visualization. Data sourced from Kaggle's Squid Game Twitter Dataset.
# Squid Game Twitter Analysis in R

## Project Overview
This project provides a comprehensive analysis of Twitter conversations surrounding Netflix's "Squid Game." Using R, we explore sentiment trends, top tweets, geographic distribution, and other key insights. The project aims to understand how audiences discussed and reacted to the show across various sentiments, as well as identify commonly used words and retweeted posts.

## Objectives
- To analyze and visualize Twitter data related to "Squid Game."
- To identify the most common sentiments and frequently used words.
- To compare sentiment across three lexicons for nuanced analysis.
- To uncover trends in tweeting locations and highlight top retweeted tweets.

## Data Source
The dataset used for this analysis was sourced from [Kaggle's Squid Game Twitter Dataset](https://www.kaggle.com/datasets/deepcontractor/squid-game-netflix-twitter-data), initially containing over 80,000 tweets. After a rigorous data cleaning process, the dataset was reduced to a final form of 225,187 observations with 13 variables, stored in an object named `cleaned_tweets`.

## Data Cleaning and Processing
The data cleaning process involved removing duplicates, non-English tweets, and special characters, as well as normalizing text to lowercase for consistent analysis. The resulting dataset enables us to focus on meaningful patterns in the data without noise.

## Analysis Overview
This analysis covers the following key topics:
1. **Frequency of Tweets**: Visualizing the distribution of tweets over time.
2. **Top Retweeted Tweets**: Identifying and showcasing the top 20 most retweeted tweets.
3. **Tweeting Locations**: Examining geographic distribution and presenting the top 10 locations.
4. **Sentiment Analysis**: Using three sentiment lexicons to analyze and compare positive and negative word contributions.
5. **Word Cloud Visualizations**: Generating word clouds for positive, negative, and overall sentiment words.

## Sentiment Lexicons Comparison
To gain a balanced view, this analysis compares sentiment results across three sentiment lexicons, providing insights into how word associations with "Squid Game" may vary between each lexicon.

## Visualizations
A range of visualizations were created, including:
- Bar charts showing the frequency of tweets
- Word clouds for common positive and negative words
- Location-based maps of tweet origins
- Comparison charts across different sentiment lexicons

## Results and Insights
This analysis reveals key trends in how viewers engaged with "Squid Game" on Twitter, showcasing the distribution of sentiments and identifying standout moments based on retweet counts and location data.

---

This project was completed using R and leverages various data wrangling and visualization techniques. The insights derived offer a deeper understanding of Twitter's response to the global phenomenon of "Squid Game."
