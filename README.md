# Movie-Recommendation-System

        

# Content-Based Movie Recommendations from TMDB 5000 Movie Dataset
This repository provides a content-based movie recommendation system based on the TMDB 5000 Movie Dataset from Kaggle. The system is built using Python and various data analysis and machine learning libraries. Additionally, it is deployed on Heroku, allowing for easy access to the recommendation system online.

# Features
The movie recommendation system in this repository has the following features:

Uses the TMDB 5000 Movie Dataset to provide accurate recommendations
Provides recommendations based on movie features such as genre, cast, and crew
Supports real-time user input for personalized recommendations
Uses machine learning algorithms such as cosine similarity for recommendation
Deployed on Heroku, allowing for easy access to the recommendation system online

# Requirements
To use the content-based movie recommendation system in this repository, you need to have the following software installed on your system:

Python 3
Pandas
Numpy
Scikit-learn

# Installation
To install the content-based movie recommendation system, follow these steps:

Clone the repository to your local system using the following command:
git clone https://github.com/asu2304/Movie-Recommendation-System.git


Download the TMDB 5000 Movie Dataset from Kaggle and place the movies_metadata.csv and credits.csv files in the data directory of the repository.

Install the required Python libraries using pip:
pip install pandas numpy scikit-learn


Create a Heroku account if you do not have one already.

Create a new Heroku app from the Heroku dashboard.

Install the Heroku CLI tool on your local system.

Login to your Heroku account using the CLI tool:
heroku login

Navigate to the cloned repository on your local system and create a new Git repository:
git init

Connect the Git repository to your Heroku app using the following command:
heroku git:remote -a your-app-name
git add .
git commit -am "initial commit"
git push heroku master


# Usage
To use the content-based movie recommendation system, simply navigate to the URL of your Heroku app in a web browser. You can enter your own movie preferences such as genre, cast, and crew to get personalized movie recommendations.
License
This repository is licensed under the MIT License. See the LICENSE file for more information.

# Acknowledgements
This movie recommendation system is based on the TMDB 5000 Movie Dataset, which was originally published by The Movie Database (TMDb). The dataset can be found at https://www.kaggle.com/tmdb/tmdb-movie-metadata.
Deploy the app to Heroku using Git:
