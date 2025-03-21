<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Movie Rating Prediction</h1>
    <h2>Project Overview</h2>
    <p>The Movie Rating Prediction project involves analyzing a dataset containing information about Indian movies. The dataset includes details like movie name, year, duration, genre, rating, votes, director, and three main actors. The data will be used to build a predictive model for movie ratings and extract valuable insights from the movie industry.</p>
    
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#business-understanding">Business Understanding</a></li>
        <li><a href="#objectives">Objectives</a></li>
        <li><a href="#data-understanding">Data Understanding</a></li>
        <li><a href="#eda">Exploratory Data Analysis (EDA)</a></li>
        <li><a href="#modeling">Modeling</a></li>
        <li><a href="#recommendations">Recommendations</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
        <li><a href="#next-steps">Next Steps</a></li>
    </ul>
    
    <h2 id="business-understanding">Business Understanding</h2>
    <p>The film industry relies on understanding the factors that influence movie success. Accurately predicting movie ratings can aid in decision-making, such as choosing the right actors, directors, and genres, as well as determining marketing strategies.</p>
    
    <h2 id="objectives">Objectives</h2>
    <ul>
        <li><strong>Develop a predictive model:</strong> Create a machine learning model to predict movie ratings.</li>
        <li><strong>Identify influential factors:</strong> Determine which aspects impact movie ratings most.</li>
        <li><strong>Provide actionable insights:</strong> Help stakeholders make informed production and marketing decisions.</li>
    </ul>
    
    <h2 id="data-understanding">Data Understanding</h2>
    <p>The dataset includes the following features:</p>
    <ul>
        <li><strong>Name:</strong> Movie name</li>
        <li><strong>Year:</strong> Release year</li>
        <li><strong>Duration:</strong> Movie duration</li>
        <li><strong>Genre:</strong> Movie genre</li>
        <li><strong>Rating:</strong> IMDb rating</li>
        <li><strong>Votes:</strong> Number of votes received</li>
        <li><strong>Director:</strong> Movie director</li>
        <li><strong>Actor 1, Actor 2, Actor 3:</strong> Main actors</li>
    </ul>
    
    <h2 id="eda">Exploratory Data Analysis (EDA)</h2>
    <p>EDA includes:</p>
    <ul>
        <li>Rating analysis</li>
        <li>Top 10 directors with most movies</li>
        <li>Top 10 actors with most movie appearances</li>
        <li>Top 10 highest-rated movie genres</li>
        <li>Duration vs. rating correlation</li>
    </ul>
    
    <h2 id="modeling">Modeling</h2>
    <p>The following models were tested:</p>
    <ul>
        <li>Baseline Model: Linear Regression</li>
        <li>Random Forest Model</li>
        <li>Gradient Boosting Regressor</li>
        <li>Hyperparameter tuning of Random Forest</li>
    </ul>
    <p>The tuned Random Forest model was chosen due to its balanced performance.</p>
    
    <h2 id="recommendations">Recommendations</h2>
    <ul>
        <li>Stay updated with industry trends.</li>
        <li>Encourage audience reviews.</li>
        <li>Optimize movie duration based on audience preferences.</li>
        <li>Invest in highly-rated genres like History and Romance.</li>
    </ul>
    
    <h2 id="conclusion">Conclusion</h2>
    <p>This project offers insights into movie rating prediction. The most influential factors identified are the year of release, number of votes, and movie duration.</p>
    
    <h2 id="next-steps">Next Steps</h2>
    <ul>
        <li>Improve the model with advanced techniques.</li>
        <li>Enhance feature engineering.</li>
        <li>Analyze user reviews and sentiment.</li>
        <li>Implement real-time data updates.</li>
    </ul>
</body>
</html>
