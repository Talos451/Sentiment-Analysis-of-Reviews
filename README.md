Data Collection: Reviews were collected using the Yelp API for restaurants in Morris, Bergen, Passaic, and Union Counties.
Data Cleaning: Stopwords were removed, and reviews were cleaned for analysis.

Sentiment Analysis:
Default TextBlob: Showed predominantly positive sentiment with some neutral and minimal negative reviews.
NaiveBayesAnalyzer: Classified reviews strictly as positive or negative, with roughly equal counts but no neutral sentiment. Took ~15 minutes for 288 reviews.

Visualization:
Donut Charts: Displayed sentiment distributions for both analyzers.
WordCloud: Highlighted the most frequent words in reviews, such as food, Indian, and chicken.

Key Insights
Positive Sentiment dominated the reviews across both analyzers.
Top Words reflect customer focus on food quality, service, and authenticity.
NaiveBayesAnalyzer provided stricter classifications but required more time.
