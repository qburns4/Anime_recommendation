# Anime recommendation

## Overview

This project is an Anime Recommendation System that generates n recommendations given the name of an anime. It uses Natural Language Processing(NLP) techniques to build meaningful similarity scores between anime descriptions, enabling content-based recommendations.

## Skills Demonstrated

The system is designed as a portfolio project to demonstrate skills in:
* Data Science: **Natural Language Processing**, **similarity metrics**.

* Machine Learning Engineering: **Building scalable recommendation pipelines**.

* Software Engineering: **Clean, reproducible code with documentation**.

## How it works

### Data Collection
Dataset sourced from https://www.kaggle.com/code/hasibalmuzdadid/anime-ratings-analysis-recommender-system Contains anime metadata such as titles, genres, synopsis, and ratings.

### Feature Engineering
* **Text preprocessing** (tokenization, stopword removal, lemmatization).
* **TF-IDF vectorization** to numerically represent anime descriptions.
* **Cosine similarity** calculation to measure closeness between anime.

### Recommendation Engine
1. User inputs an anime name.
2. The system finds the closest matching title.
3. It retrieves the top-n most similar anime based on content features.
