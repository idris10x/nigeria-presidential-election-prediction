# Nigeria Presidential Election Prediction
 
### Overview

This repository contains a sentiment analysis model that aims to predict the outcome of the Nigeria Presidential Election. The model uses tweets scraped from Twitter using Twint and the sentiment polarity of the tweets to make predictions. The model was built using scikit-learn.

### Data Collection

The tweets were collected using Twint, an open-source Twitter scraping tool. The scraped tweets were preprocessed and the sentiment polarity was extracted using TextBlob.

### Modeling

The sentiment polarity was used as the independent feature for building the model. The target variable was each candidate's tendency to win per tweet. The final model was tested using scikit-learn's MLPClassifier.

### Results

Unfortunately, the model accuracy score was low (35.2%). This could be due to a number of reasons, such as the limited number of observations and the use of only one independent feature (polarity).

### Future Work

This repository provides a starting point for anyone interested in using sentiment analysis for predicting the outcome of elections. There is a lot of room for improvement and anyone is welcome to contribute. Some suggestions for improving the model include:

* Collecting more data to increase the number of observations
* Adding additional independent features, such as word frequency, word bigrams, and n-grams
* Using feature selection techniques to determine the most important features

### Conclusion

Predicting the outcome of an election using sentiment analysis is a challenging task, but this repository provides a starting point for anyone interested in exploring this problem further. With more data, improved features, and different machine learning algorithms, it is possible to build a more accurate model.
