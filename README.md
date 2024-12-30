# British-Airways-reviews--Virtual-Internship

This project focuses on scraping, cleaning, and analyzing airline customer reviews using Natural Language Processing (NLP). It evaluates sentiments (positive, negative, or neutral) using NLTK's VADER sentiment scoring.

### Table of Contents
1. Overview
2. Features
3. Technologies Used
4. Necessary libraries
5. Results
6. Visualizations
7. Future Enhancements

### Overview
The goal of this project is to:

1. Scrape airline reviews.
2. Clean and preprocess the text data.
3. Perform sentiment analysis using NLTK's SentimentIntensityAnalyzer.
4. Visualize the distribution of sentiments and analyze the results.
5. 
### Features
- Web scraping of airline reviews from multiple pages.
-Text preprocessing including:
    - Removal of stopwords, special characters, and URLs.
    - Tokenization, lemmatization, and POS tagging.
- Sentiment scoring with positive, negative, neutral, and compound scores.
- Sentiment classification as Positive, Negative, or Neutral.
- Data visualization to analyze sentiment trends.

###  Technologies Used
Python for data processing and analysis.
Libraries:
- requests, BeautifulSoup: Web scraping.
- pandas, nltk, regex: Data cleaning and NLP.
- matplotlib, seaborn: Data visualization.

### Necessary libraries

-  nltk
- nltk.download('punkt')
- nltk.download('stopwords')
- nltk.download('vader_lexicon')
- nltk.download('averaged_perceptron_tagger')

### Results
The reviews are categorized into:
Positive: 453 reviews
Negative: 435 reviews
Neutral: 112 reviews 

### Visualizations
Key insights are visualized through scatter plots:

1. Positive Scores vs Compound Scores
2. Negative Scores vs Compound Scores
3. Neutral Scores vs Compound Scores

### Future Enhancements
- Implement a deep learning model for sentiment analysis.
- Analyze reviews for specific topics using topic modeling.
- Expand data collection to include reviews from multiple airlines.
