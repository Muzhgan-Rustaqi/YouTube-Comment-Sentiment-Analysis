# YouTube-Comment-Sentiment-Analysis
This project analyzes the sentiment expressed by users in YouTube comments using Python and various data analysis libraries. The goal is to understand the overall sentiment distribution and common themes in user feedback.
# Overview
YouTube comments provide valuable insights into viewer sentiments towards videos. This project utilizes the YouTube Data API to fetch comments from specific videos or a pre-existing dataset. The data is then processed using pandas and numpy for data manipulation and cleaning. Sentiment analysis is performed using TextBlob, which allows for the classification of comments into positive, negative, or neutral sentiments based on the polarity of the text.

# Project Structure
ETL Pipeline

Extract: Fetch YouTube comments using the YouTube Data API.
Transform: Clean and preprocess comments to remove noise and standardize text.
Load: Store cleaned data in a CSV format for further analysis.

 Exploratory Data Analysis (EDA)
 
Visualize sentiment distribution using histograms and box plots.
Generate word clouds to identify common themes in positive and negative comments.
Conclusion

Summarize findings regarding the sentiment expressed by YouTube users.
Discuss trends, patterns, and insights discovered through the analysis.
# Tools Used
Python Libraries: pandas, numpy, matplotlib, seaborn, TextBlob
Visualization: Matplotlib, Seaborn, WordCloud
