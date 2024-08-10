# Content-Based Movie Recommender System

This repository features a content-based movie recommender system built using the TMDb dataset. The system recommends movies by analyzing and comparing their descriptions and titles.

## Overview

The recommender system is implemented with the following steps:

1. **Data Loading**: The TMDb dataset is loaded into a Pandas DataFrame.
2. **Data Preprocessing**: The dataset is preprocessed for feature extraction.
3. **Feature Extraction**:
   - **Vectorization**: Converts movie descriptions into numerical vectors.
   - **Stemming**: Normalizes words to their root forms using NLTK.
4. **Similarity Calculation**: Computes cosine similarity between movies based on their vectorized descriptions.
5. **Recommendation**: Provides recommendations for movies based on content similarity.

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- nltk

## Dataset

The TMDb dataset is used, containing movie titles and descriptions essential for generating recommendations.

## Acknowledgements

- The TMDb dataset is provided by TMDb.
- Techniques and methods are inspired by standard practices in content-based recommendation systems.
