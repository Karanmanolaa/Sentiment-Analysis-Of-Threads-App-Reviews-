# Project 1 - Sentiment-Analysis-Of-Threads-App-Reviews

# Table of Content
- Overview
- Problem Statement and Motivation
- Technical Aspects
- Challenges Faced and Solutions
- Visualizations

# 1- Overview :
The aim of this project is to perform sentiment analysis on user reviews of the Threads app, a social media platform. Using Natural Language Processing (NLP) and machine learning techniques, we aim to determine the sentiments expressed in these reviews. The dataset, consisting of approximately 30,000 reviews, includes user ratings ranging from 1 to 5. The dataset was sourced from Kaggle and serves as the foundation for training our sentiment analysis model.

# 2- Problem Statement and Motivation :
User reviews offer valuable feedback for any application. However chechking and analyzing these reviews manually is impractical due to their volume. Hence, an automated sentiment analysis model can be highly benificial, as it can efficiently assess user sentiments expressed in these reviews.
This model has the potential to enhance the user experience by addressing issues and facilitating data-driven decision-making.

# 3- Technical Aspects :
In this project i have used python programming language and its libraries - NLTK,scikit-learn,pandas, numpy,re,matplotlib,seaborn
for different purpose like
- Performed Explolatory data analysis using matplotlib and seaborn.
- Figure out if reviews were positive, negative, or neutral using a pretrained model called VADER(Valence Aware Dictionary and sEntiment Reasoner) .
- Created new features (feature engineering) like sentiment	,text_length,	sentiment_numerical.
- Changed the words in the reviews into numbers using TF-IDF.
- I tried several models like Naive Bayes, Random Forest,XGBoost.
  Random Forest model did the best with and accuracy of 0.8243.

 # 4- Challenges Faced and Solutions:
 Challenges - 
 - One significant challenge we encountered was the class imbalance in the dataset. Most of the reviews had positive sentiments, making it difficult to train a model 
  effectively due to the skewed distribution of classes.

 Solutions -
 - To address the class imbalance issue, we applied the Synthetic Minority Over-sampling Technique (SMOTE). SMOTE is a powerful method that helped us balance the dataset by 
  generating synthetic samples for the minority class. This improved the model's performance and the accuracy of sentiment analysis.

 
 # 5- Visualizations:
  ![](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/blob/main/images/download%202.png)
  

  
