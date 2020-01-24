# Project_Proposal

## First Proposal

### High Level Description

Predict AirBnB revenue for a given homes in Austin.  Finding the right balance between supply and demand is quite difficult.  A night that goes without guests is lost revenue, the amount of tourist that come to Austin are quite substantial and if priced right the amounts of nights without guests will be low.  The models I intend to use will be Linear regression models, Logistic Regression (will it be occupied or not).  

### Approach:

The main approach to generate a good model will be to get AirBnB data for Austin.  Inspect average prices and locations.  Generate a model that takes into account length of stays, and possible seasonality, feature selection. EDA will take a large portion of my time.  I would like to look at common features provided by each host and potential impact to the pricing (wifi, washer/dryer, lakeside view).

### Model interaction:

I will create a flask app that will have a mongoDB or PostgresSQL database on the backend for people to interact with.  They can see given zipcode, size of home, or unique features (close to lake or downtown) what their expected revenue could be given a range of possible prices to post on the website. 

### Data sources:

The main data source I will use will be csv files from insideairbnb.  The data is not clean and will require EDA to be usable for ML models.  I will leverage the austintexas.org website to pull big event dates, such as, ACL, SXSW, and F1 to name a few.  Through EDA I will look for spikes in prices for the past years and see what drew more people and how did the market react. 

## Second Proposal

### High Level Description

This will build on the first proposal of predicting expected AirBnB revenue in Austin.  However, an added sentiment analysis will be incorporated to gain insight through comments left by past guest to see what features stand out to people, enough to get them to leave a comment (good or bad).  The models I intend to use will be Linear regression models, Logistic Regression (will it be occupied or not) and NLP.  

### Approach:

The main approach to generate a good model will be to get AirBnB data for Austin.  Inspect average prices and locations.  Generate a model that takes into account length of stays, and possible seasonality, feature selection. EDA will take a large portion of my time.  I would like to look at common features provided by each host and potential impact to the pricing (wifi, washer/dryer, lakeside view).

### Model interaction:

I will create a flask app that will have a mongoDB or PostgresSQL database on the backend for people to interact with.  They can see given zipcode, size of home, or unique features (close to lake or downtown) what their expected revenue could be given a range of possible prices to post on the website.  

### Data sources:

The main data source I will use will be csv files from insideairbnb.  The data is not clean and will require EDA to be usable for ML models.  I will leverage the austintexas.org website to pull big event dates, such as, ACL, SXSW, and F1 to name a few.  Through EDA I will look for spikes in prices for the past years and see what drew more people and how did the market react.


## Third Proposal

### High Level Description

I would like to get a sentiment analysis of 7 world wonders, utilizing data from TripAdvisor and Twitter.  What are the most common words people use to express their experiences? What is the most ‘loved’ world wonder.    

### Approach:

Scrape Twitter and TripAdvisor to get comments for each world wonder.  Load data to mongoDB.  Begin to filter out small filler words and focus on patterns. Incorporate other features, such as country, language, and how easy it is to get to the location.  Try to incorporate other data from popular travel sites.

### Model interaction:

I will create a flask app that will have a mongoDB or PostgresSQL database on the backend for people to interact with.  People can filter through the 7 wonders and see top findings and highlights of each.  

### Data sources:

Use web scraping to get data from several twitter, tripadvisor, and other specific world wonder websites.  
