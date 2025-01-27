# Collaborative Filtering Recommendation Engine with Apache Spark ML

This project builds a collaborative filtering recommendation engine using Apache Spark's MLlib. It is designed to recommend items to users based on their previous interactions.


## Project Overview
This engine uses the **Alternating Least Squares (ALS)** algorithm from Apache Spark MLlib to recommend items to users. The model is trained on a dataset of user-item interactions and predicts ratings for items that users haven't interacted with yet.

## Dataset
The dataset used in this project is the **MovieLens** dataset, which contains ratings of movies by users. The dataset includes columns for `userId`, `movieId`, and `rating`.

## Installation

### Prerequisites
- Python 3.6 or higher
- Apache Spark (with PySpark)
- Other dependencies listed in `requirements.txt`



