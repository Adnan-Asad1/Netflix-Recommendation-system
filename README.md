
# **Building And Deploying A Netflix Recommendation System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site and performed sentiment analysis on those reviews.


## Create Virtual Environment

To create virtual environment, run the following command

```bash
  python -m venv <env_name>
```
## Install Requirements

To install all the requirements, run the following command

```bash
  pip install -r requirements.txt
```

## Running Flask Tests

To run a Flask deployment tests, run the following command

```bash
  python main.py
```


## Running Deployment Tests

To run a deployment tests, click on the following link:

[Netflix Recommender System App](https://hamzameer007.pythonanywhere.com/)


## Deployment

### Steps To Deploy The App:

Prepare your dataset:

        1. Data Extraction
        2. Exploratory Data Analysis(EDA)
        3. Feature Engineering
        4. Model Building and Tuning
        5. Building Flask API
        6. Pushing code to Github
        7. Connecting to your Pythonanywhere account 
        8. Deploy App


## Demo

[Click HERE To View App](https://hamzameer007.pythonanywhere.com/)





![logo](https://github.com/MrBriit/Netflix-Recommender-System-and-Deployment/blob/main/net%20screenshot.png?raw=true)

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

