# Yelp's Reviews Classification Using NLP Text Analytics
Anallysis of Yelp's reviews using NLP Text Analytics to classify whether a review is positive or negative

In a bid to stay ahead, companies use data analytics to gauge their standing against competitors and gain leverage over them. Yelp is a business directory service and crowd-sourced review forum and collects data such as user ratings on a particular business, along with their locations, reviews (text), ratings, timings, likes, dislikes, etc.
A business has many choices when it comes to investing money. Should a restaurant get well-known chefs or excellent lighting? Should a salon invest in high tech appliances or comfortable seats? If many customers talk about “ambience” while giving a 5-star review, it would mean customers really care about great ambience and hence the business should focus on it. Our aim is to explore this mass of data and answer the following and come up with interesting questions and analyze how or what a business can use to plan their next step to position their product/brand.

## Table of contents
* [Description](#description)
* [Methodologies](#methodologies)
* [Results](#results)
* [Files](#files)
* [Technologies](#technologies)
* [Packages](#packages)
* [Setup](#setup)
* [Usage](#usage)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## Description
The objective of this project is to classify a review on Yelp as negative or positive based on key words, helping businesses in various industries identify areas of improvement and make strategic plans to gain leverage over competitors by improving those areas and revenues accordingly. The project will use Sentiment Analysis to answer the following questions:
* What factors lead to business success?
* What are the most important concerns for customers?

Sentiment Analysis will identify top 10 business relevant words in positive or negative reviews. This project will focus on what makes a good restaurant, what concerns customers, and make recommendations for future improvent. For customer needs, Review Text and Star Rating provide an excellent basis to identify their concerns. We will use Business Closure (is_open) as the determining factor of business success.

Data source: https://www.kaggle.com/yelp-dataset/yelp-dataset/version/6

## Methodologies
* Data exploration: perform EDA on all datasets to get a general understanding of the data
* Data modeling: classify business closure (is_open) is true or not by applying logistic regression, SMOTE algorithm, Near-Miss algorithm, classification models with SMOTE (decision tree, random forest, KNN)
* Sentiment Analysis: identify top key words related to restaurants

## Results
* **Model Result**: Most customers complain about delivery time of food and care about restaurants having "delicious" food or are "friendly"

## Files
* Data used in the project was downloaded from Kaggle including:
  - yelp_business.csv: businesses on Yelp (174,567 rows, 13 columns)
  - yelp_business_hours.csv: hours of operation (174,567 rows, 8 columns)
  - yelp_checkin.csv: check-in time (3,911,218 rows, 4 columns)
  - yelp_review.csv: review of the business on Yelp (5,261,668 rows, 9 columns)
  - yelp_user.csv: user of the review (1,326,100 rows, 22 columns)
  - yelp_business_attributes.csv: attributes of businesses (152,041 rows, 82 columns)
  - yelp_tip: tip for each business (1,098,324 rows, 5 columns)
* Group 5 - Code Part 1.ipynb: main code - exploratory data analysis and classification models
* Group 5 - Code Part 2.ipynb: main code - sentiment analysis
* Group-5_Buan6340.501_Project-Report.pdf: final report including project steps and results
* Group5.5_Yelp_Reviews.pptx: Power Point presentation summarizing the project
* requirements.txt: text file containing all Python libraries used in the project

## Technologies
Project is created with:
* MS Excel
* Anaconda
* Jupyter Notebook
* Python 3
* Windows

## Packages
* pandas
* nltk
* matplotlib
* seaborn
* string
* itertools
* requests
* Counter
* defaultdict
* nltk.text 
* Text
* nltk.probability 
* FreqDist
* nltk.tokenize 
* word_tokenize
* sent_tokenize
* regexp_tokenize
* nltk.corpus 
* stopwords
* nltk.stem 
* PorterStemmer
* WordNetLemmatizer
* gensim.corpora.dictionary 
* Dictionary
* gensim.models.tfidfmodel 
* TfidfModel
* sklearn.cluster 
* KMeans
* wordcloud 
* WordCloud

## Setup
* Download all data files from Kaggle
* Download both iPython notebooks
* Install the requirements using `pip install -r requirements.txt`.
  - Make sure you use Python 3

## Usage
* Run `Group 5 - Code Part 1.ipynb` and `Group 5 - Code Part 2.ipynb` to see all project steps

## Status
Project is finished.

## Inspiration
Project was created as the capstone assignment for Programming for Data Science course at UT Dallas.

## Contact
Created by:
* Mahesh Iyer
* Sujith Nair
* My Pham - [@mypham14](https://github.com/mypham14/) - feel free to contact me on my [LinkedIn](https://www.linkedin.com/in/mytrapham)!
