# Overview
The Movie KNN Classifier is a machine learning tool designed to classify movies into genres of comedy or thriller based on the frequency of certain words in the movie's screenplay. This project demonstrates the construction and testing of a k-nearest-neighbors classification model. By leveraging the patterns found in screenplay vocabulary, the classifier achieves an impressive accuracy rate, providing insights into how words correlate with movie genres.

## Project Features
* K-Nearest-Neighbors Classifier: Built using Python, this classifier determines a movie's genre by examining the frequency of selected words in its screenplay.
* Data Preprocessing: The Python datascience library was used for cleaning the dataset which included normalizing text to lowercase, removing irrelevant columns, punctuation, and handling missing values.
* Feature Extraction: A thorough analysis of 5000 common words from various screenplays was conducted. Word stemming was employed to narrow down the dataset, and a linear regression analysis helped understand the connection between word usage and genre classification, isolating 20 significant words as primary features.
* Model Training: The dataset was split into a training set and a test set. The k-NN algorithm was applied using Euclidean distance as the metric for identifying similarities in word frequencies, with nearest neighbors used to categorize each movie in the test set.

## Usage
To use the Movie KNN Classifier:
* Ensure you have Python installed along with the necessary libraries (datascience, numpy, etc.).
* Clone this repository to your local machine.
* Run the classifier script with your input dataset in a compatible format (refer to the 'Data Format' section below).
* Review the output for the movie genre classifications.

## Data Format
Your dataset should be in a CSV format with the following columns:
* Title: The title of the movie.
* Screenplay: The full text of the movie's screenplay.
* (Optionally) Genre: The actual genre of the movie if you're using the dataset for testing.

## Acknowledgment
This project is based on Project 3 of UC Berkeley's Foundations of Data Science course.

