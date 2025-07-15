# Book Recommendation Engine using K-Nearest Neighbors (KNN)

## Overview

This project implements a book recommendation system based on the Book-Crossings dataset using the K-Nearest Neighbors (KNN) algorithm. The engine recommends books similar to a given book title by analyzing patterns in user ratings.

## Dataset

The Book-Crossings dataset contains over 1 million ratings from about 90,000 users on 270,000 books. The data was filtered to include only active users (with at least 50 ratings) and popular books (with at least 30 ratings) to ensure reliable recommendations.

## Features

- Data preprocessing and filtering to enhance recommendation quality
- Creation of a user-book ratings pivot matrix
- Use of cosine similarity and KNN for collaborative filtering
- A function `get_recommends()` that takes a book title and returns 5 similar book recommendations with similarity scores
- Robust handling of missing or unmatched book titles
- Validation through a test function to ensure the recommendation quality

## Usage

1. Clone or download the repository.
2. Run the Jupyter Notebook `book_recommendation_knn.ipynb`.
3. Use the `get_recommends()` function to get book recommendations.

Example:

```python
get_recommends("The Queen of the Damned (Vampire Chronicles (Paperback))")
