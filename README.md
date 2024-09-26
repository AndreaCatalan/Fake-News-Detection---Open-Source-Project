## Fake News Detection

## Introduction

This project aims to identify fake news articles using machine learning techniques. By analyzing text data from various sources, we can classify news as either fake or real. The model can be tested manually with custom input for quick verification.

## Motivation

I created this project to improve my machine learning and Python skills. Throughout the development process, I utilized various YouTube tutorials to guide my understanding and implementation of the techniques used.

## Datasets

The project utilizes three datasets:

Fake.csv: Contains fake news articles.
True.csv: Contains real news articles.
manual_testing.csv: A dataset for testing custom news articles. You can paste any news text to determine its classification.
Requirements

To run the project, you will need the following libraries:

pandas
numpy
seaborn
matplotlib
sklearn
re
string
Install any missing libraries using pip.

## Data Preparation

Load Datasets: Import the fake and true news datasets.
Labeling: Add a class column to categorize the datasets:
0 for fake news
1 for real news
Manual Testing Set: Remove the last 10 rows from each dataset for manual testing.
Data Processing

Merge Datasets: Combine fake and true news data for analysis.
Data Cleaning: Drop unnecessary columns and preprocess the text by:
Converting to lowercase
Removing special characters, URLs, and extra spaces
Model Training

The project employs various classification models to detect fake news, including:

Logistic Regression
Decision Tree Classifier
Gradient Boosting Classifier
Random Forest Classifier
Each model's performance is evaluated based on accuracy, precision, and recall.

## Manual Testing

You can test custom news articles using the manual_testing function, which provides predictions from all trained models. Simply input the news text, and the models will classify it as either "Fake News" or "Not A Fake News".

## Usage

Clone the repository.
Install required libraries.
Load the datasets and preprocess the data.
Train the models.
Use the manual testing feature to evaluate custom news articles.
Conclusion

This Fake News Detection project demonstrates the potential of machine learning in combating misinformation. By providing tools to analyze news articles, I aim to promote media literacy and awareness.
