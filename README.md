# Twitter_sentiment_analysis
Understanding and interpreting human sentiments on social media platforms

This project utilizes the Sentiment140 dataset, which contains 1.6 million tweets extracted via the Twitter API. Each tweet is labeled with sentiment (0 = negative, 4 = positive), making it ideal for sentiment detection tasks. The dataset includes fields such as the sentiment (target), tweet ID (ids), date, query (flag), user handle, and tweet text.

## Dataset Fields
* **target**: Sentiment polarity (0 = negative, 2 = neutral, 4 = positive)
* **ids**: Unique tweet identifier
* **date**: Date and time of the tweet
* **flag**: Query used to extract the tweet (or NO_QUERY)
* **user**: The Twitter handle of the user
* **text**: The tweet content

## Libraries and tools used.
* **NumPy**: For numerical computations and efficient array operations.
* **Pandas**: To manipulate and analyze the dataset, allowing for easy data cleaning and exploration.
* **Regular Expressions**: For text cleaning and pattern matching, helping to remove unwanted characters, links, and hashtags.
* **NLTK (Natural Language Toolkit)**: Provides tools for natural language processing, including text tokenization and stopwords removal.
* **Stopwords**: Common words (like "and", "the") that are often removed to focus on meaningful words in a sentence.
* **Porter Stemmer**: An algorithm that reduces words to their base or root form (e.g., "running" becomes "run"), helping with consistency in text analysis.
* **TfidfVectorizer**: Converts the text data into numerical form by measuring the importance of words in the dataset, which is essential for model training.
* **Logistic Regression**: A machine learning algorithm used for binary classification to predict the sentiment of tweets (positive or negative).
* **Accuracy Score**: A metric used to evaluate the performance of the sentiment classifier, providing the percentage of correct predictions.

This repository covers the entire process, from text preprocessing to sentiment classification, using powerful NLP techniques and machine learning algorithms to gain insights from Twitter data.
