# Movie Rating Prediction

The Movie Rating Prediction project involves analyzing a dataset containing information about Indian movies. The dataset includes details like movie name, year, duration, genre, rating, votes, director, and three main actors. The data will be used to build a predictive model for movie ratings and extract valuable insights from the movie industry.

## Table of Contents
- [Business Understanding](#business-understanding)
- [Objectives](#objectives)
- [Data Understanding](#data-understanding)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Next Steps](#next-steps)

## Business Understanding
The film industry relies on understanding the factors that influence movie success. Accurately predicting movie ratings can aid in decision-making, such as choosing the right actors, directors, and genres, as well as determining marketing strategies.

## Objectives
- **Develop a predictive model:** Create a machine learning model to predict movie ratings.
- **Identify influential factors:** Determine which aspects impact movie ratings most.
- **Provide actionable insights:** Help stakeholders make informed production and marketing decisions.

## Data Understanding
The dataset includes the following features:
- **Name:** Movie name
- **Year:** Release year
- **Duration:** Movie duration
- **Genre:** Movie genre
- **Rating:** IMDb rating
- **Votes:** Number of votes received
- **Director:** Movie director
- **Actor 1, Actor 2, Actor 3:** Main actors

## Exploratory Data Analysis (EDA)
EDA includes:
- Rating analysis
- Top 10 directors with most movies
- Top 10 actors with most movie appearances
- Top 10 highest-rated movie genres
- Duration vs. rating correlation

## Modeling
The following models were tested:
- Baseline Model: Linear Regression
- Random Forest Model
- Gradient Boosting Regressor
- Hyperparameter tuning of Random Forest

The tuned Random Forest model was chosen due to its balanced performance.

## Recommendations
- Stay updated with industry trends.
- Encourage audience reviews.
- Optimize movie duration based on audience preferences.
- Invest in highly-rated genres like History and Romance.

## Conclusion
This project offers insights into movie rating prediction. The most influential factors identified are the year of release, number of votes, and movie duration.

## Next Steps
- Improve the model with advanced techniques.
- Enhance feature engineering.
- Analyze user reviews and sentiment.
- Implement real-time data updates.
