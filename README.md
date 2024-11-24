# Movie Recommendation System

## Description
This project implements a content-based movie recommendation system. It leverages the TMDB API for movie data and natural language processing techniques for recommendation generation.

## How it Works
1. **Data Collection:** The system gathers movie data, including overviews, cast, and genre information, from the TMDB API.
2. **Data Preprocessing:** The collected data is cleaned and processed by removing spaces and applying stemming.
3. **Feature Extraction:** Using NLP, the system extracts relevant features from the movie data, creating a unique representation for each movie.
4. **Similarity Calculation:** The system utilizes cosine similarity to determine the similarity between movies based on their features.
5. **Recommendation:** When given a movie title, it retrieves the most similar movies based on the calculated similarity scores.

## Libraries Used
* pandas
* numpy
* requests
* tmdbv3api
* nltk
* sklearn

## Usage
1. Ensure that you have the necessary libraries installed (`pip install -r requirements.txt`).
2. Replace `'8265bd1679663a7ea12ac168da84d2e8'` in the code with your actual TMDB API key.
3. Run the code to build the recommendation model.
4. Use the `recommend()` function to get movie recommendations. For example:

