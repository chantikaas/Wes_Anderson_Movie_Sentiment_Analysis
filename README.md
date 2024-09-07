# Wes_Anderson_Movie_Sentiment_Analysis

## Project Overview
This project aims to analyze the sentiment of IMDb user reviews for Wes Anderson's seven highest-grossing films. The analysis involves web scraping review data from IMDb and performing sentiment analysis to categorize the reviews as positive, neutral, or negative. An interactive dashboard was created in Tableau to visualize the results and provide insights.

## Data Collection
The IMDb user reviews for the top 7 highest-grossing Wes Anderson movies were scraped using Python libraries like Selenium and BeautifulSoup. The scraped data includes:

- Review Title
- Review Text
- Review Rating

## Sentiment Analysis
The sentiment analysis was performed on the review text to categorize them into three categories:

- Positive
- Neutral
- Negative

This analysis was implemented using RoBERTa pre-trained model, which is designed for sentiment classification of text data.

# Data Visualization
An interactive Tableau dashboard was built to display key insights from the sentiment analysis. The following visualizations were included:

- Distribution of Reviewers' Sentiment: Shows the proportion of positive, neutral, and negative reviews for each movie.
- Reviewers' Emotion Distribution for the Movies: Visualizes the emotional tone of reviews for each movie, such as joy, anger, sadness, etc.
- Percentage of Movie Ratings: Displays the percentage breakdown of IMDb ratings for each movie.
- Gross Ranking vs Sentiment Score: Compares each movie’s gross ranking with the average sentiment score of its reviews.
- Most Used Words in Reviews: Highlights the most frequently used words by reviewers, offering insights into common themes or opinions about the movies.

You can find the dashboard [here](https://public.tableau.com/views/WesAndersonMoviesSentimentAnalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
