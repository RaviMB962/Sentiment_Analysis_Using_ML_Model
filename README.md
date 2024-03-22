# Sentiment_Analysis_Using_ML_Model
Trained ML (Logistic Regression Model) on tweets to know whether tweet sentiment is positive or negetive

Used Data set from kaggale: https://www.kaggle.com/datasets/kazanova/sentiment140

# Steps Performed

*   Install Kaggle Library
*   Uplodai kaggle.json
*   Copy API commaond - it load the data from kaggle to collab
*   imported dependencies
*   load the data, updated column names, checked shape and null values
*   Performed stemming for each text data to consider root word which are exclude from stopwords
*   Created new column stemming_conntent for above
*   Split the data into train test
*   Apply the Vectorizer(TF-IDF) to convert text into machine learnable vectors on stemmed text data
*   Train the model usng LogisticRegression
*   Calculated train model accuracy
*   Saved the model using pickle file for future use
*   Load the pickle model to perform on unseen data

