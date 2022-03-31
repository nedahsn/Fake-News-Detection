# Fake-News-Detection
In this project we work with Fake and Real News datasets to detect fake news.
We first preprocess the news (text) using nltk.
We then use word embedding in SpaCy to vectorize the news, and then apply different ML models (Logistic Regression, Linear SVC, Random Forest) to classify the news to fake and real.
We further use count vectorizer to to vectorize the news, and then apply the above-mantioned ML models.
We found for word embedding, Linear SVC works the best with F1-score of 96%, and for the count vectorizer, Random Forest works the best with F1-score of 99%.  

See the dataset in https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?datasetId=572515&sortBy=dateRun&tab=profile
