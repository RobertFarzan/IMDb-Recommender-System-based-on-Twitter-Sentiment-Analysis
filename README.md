# Movie Recommender System + Twitter Sentiment Analysis

![](https://www.kdnuggets.com/wp-content/uploads/ambalina-sentiment-analysis-header.jpg)

## :newspaper: Description 

This project focuses on __NLP and Machine Learning techniques__ to make a highly accurate Sentiment Analysis model, which will help us make predictions upon Twitter users opinion of a movie to recommend them similar movies (with Content Based Filtering).

## :nerd_face: Datasets 

This project required **two datasets** in the development phase, which you can encounter in this [repository 'datasets' directory](https://github.com/RobertFarzan/IMDb-Recommender-System-based-on-Twitter-Sentiment-Analysis/tree/main/datasets). Both of them are retrieved from **Kaggle**, the first one ['movie_reviews.tsv'](https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data?select=train.tsv.zip) used to train the Sentiment Analysis model, and the second one ['movies_metadata.csv'](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv) used to make the recommendations based on movie genre.

## :notebook_with_decorative_cover: How to use the notebooks 

The notebook [Sentiment_Analysis.ipynb](https://github.com/RobertFarzan/IMDb-Recommender-System-based-on-Twitter-Sentiment-Analysis/tree/main/Sentiment_Analysis.ipynb) is only for learning purposes, you don't have to do anything. You can go step-by-step on the process of training and evaluating different ML models for NLP and text preprocessing.

If you'd like to try it by your own or test it to getrecommendations for your Twitter account, follow these steps. Before diving into the [Recommender_System.ipynb](https://github.com/RobertFarzan/IMDb-Recommender-System-based-on-Twitter-Sentiment-Analysis/tree/main/Recommender_System.ipynb) you need to get the Twitter API credentials. In order to get access to use the Twitter API you have to apply for access on the [Twitter Developer portal](https://developer.twitter.com/en/apply-for-access). If you get lost in the process, you can follow [this tutorial](https://towardsdatascience.com/how-to-access-twitters-api-using-tweepy-5a13a206683b).

Now that we've got the credentials to use _tweepy_, we just have to follow these simple steps:

#### 1. Open the [Recommender_System.ipynb](https://github.com/RobertFarzan/IMDb-Recommender-System-based-on-Twitter-Sentiment-Analysis/tree/main/Recommender_System.ipynb) notebook on your preferred environment (e.g. _Jupyter Notebook, Google Colab..._)
  > :rotating_light: **Before making any changes you may have to run each cell in the notebook, otherwise you'll get a ton of errors. To do this, just press** <kbd>Shift</kbd>+<kbd>Enter</kbd> **on each cell before the one you are going to change. When you make the changes, follow the same advice.**
#### 2. Substitute the authentication keys with your credentials. Change the sample strings _consumer_key, consumer_secret, access_token and access_token_secret_ shown in the image with the keys you just got (and then run the cell).

  ![step2](https://user-images.githubusercontent.com/44211717/125357437-f1a21500-e367-11eb-9845-ea5c08355da3.png)
#### 3. Having done that, you just have to change the user ID (in the variable _username_) with the Twitter user ID (the name after the @) you want your recommendations to come from, as shown in the image:

  ![step3](https://user-images.githubusercontent.com/44211717/125357897-860c7780-e368-11eb-9285-12aea73494da.png)
  
Finally, if you run all the cells after these steps, you'll get your recommendations at the end of the notebook. Congratulations, you've done it! :fireworks:
