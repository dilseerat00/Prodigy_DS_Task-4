# Sentiment Analysis of Social Media Data

## Overview
This project involves analyzing and visualizing sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

## Dataset
The dataset a CSV file (`twitter_training.csv` and `twitter_validation.csv`) is used. Ensure the dataset is in the correct format before running the code.

## Project Workflow

### 1. Data Preprocessing
- Cleaning the text data by removing URLs, special characters, and converting the text to lowercase.
- Applying sentiment analysis using `TextBlob` (or VADER).

### 2. Sentiment Analysis
- Sentiments are classified as **Positive**, **Negative**, **Irrelevent** or **Neutral** based on text polarity.

### 3. Data Visualization
- Visualizing the distribution of sentiments using bar plots.
- Tracking sentiment changes over time using line plots.
- Generating word clouds to represent frequently used words in different sentiment categories.
