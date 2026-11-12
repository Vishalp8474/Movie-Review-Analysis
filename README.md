# Movie-Review-Analysis
This project is a Python-based application that collects movie reviews from different websites and analyzes people's opinions about a particular movie.
Project Title: Movie Review Analysis Using Sentiment Analysis in Python

This project is a Python-based application that collects movie reviews from different websites and analyzes people's opinions about a particular movie.

The application asks the user to enter a movie name and uses the DuckDuckGo Search (DDGS) library to find relevant user reviews online. It then extracts webpage content using the urllib and BeautifulSoup libraries.

After collecting the text, the application cleans the data by removing unnecessary characters, numbers, hashtags, URLs, and other unwanted elements.

The project uses the AFINN Sentiment Analysis Library to analyze the reviews and classify them into three categories:

Positive Reviews: Reviews expressing a positive opinion about the movie.

Negative Reviews: Reviews expressing a negative opinion about the movie.

Neutral Reviews: Reviews that have no positive or negative sentiment according to the scoring system.

Finally, the application displays the positive, negative, and neutral reviews along with their total counts.

2. Main Features
Movie Name Input: Allows users to enter the name of any movie.

Review Searching: Uses DuckDuckGo to find movie reviews online.

Web Scraping: Extracts text content from webpages using BeautifulSoup.

Sentence Extraction: Divides webpage content into individual sentences.

Text Cleaning: Removes unwanted symbols, numbers, hashtags, URLs, and extra characters.

Sentiment Analysis: Uses the AFINN library to calculate sentiment scores.

Review Classification: Categorizes reviews as positive, negative, or neutral.

Review Statistics: Displays the total number of reviews in each category.
