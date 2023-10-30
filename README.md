# Project 1 - Sentiment-Analysis-Of-Threads-App-Reviews

![0_Pxn2PsM6YHCEOlkC](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/55bbe598-1997-45b8-b525-4fa26b6f70ea)


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

 ### Most frequent words:

   ![download 4](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/7398414a-9858-4ccb-bef6-7ce50c1cc08f)
  
  ![download 2](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/a066e375-6459-4b31-9ed6-2d68d5b90504)

  ![download 3](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/c4f8db7d-b35e-4bd3-b086-1075620bc908)



  ![download 5](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/2201cec0-dbd3-424a-8f91-5c929d1e203b)


  ![download 6](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/0e7f13ee-a708-437d-a23b-22492c521bcb)

  ![download 7](https://github.com/Karanmanolaa/Sentiment-Analysis-Of-Threads-App-Reviews-/assets/144649975/12453dc4-d81c-4d77-b386-e49997b7f4ca)

  

  
