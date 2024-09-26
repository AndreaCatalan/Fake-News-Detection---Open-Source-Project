## Introduction

This project aims to identify fake news articles using machine learning techniques. By analyzing text data from various sources, we can classify news as either fake or real. The model can be tested manually with custom input for quick verification.<br>

## Motivation

I created this project to improve my machine learning and Python skills. Throughout the development process, I utilized various YouTube tutorials to guide my understanding and implementation of the techniques used.<br>

## Datasets

The project utilizes three datasets:<br>

Fake.csv - Contains fake news articles. <br>
True.csv - Contains real news articles. <br>
manual_testing.csv - A dataset for testing custom news articles. You can paste any news text to determine its classification.<br>

## Requirements

To run the project, you will need the following libraries:<br>

pandas<br>
numpy<br>
seaborn<br>
matplotlib<br>
sklearn<br>
re<br>
string<br>
Install any missing libraries using pip.<br>

## Data Preparation

Load Datasets: Import the fake and true news datasets.<br>
Labeling: Add a class column to categorize the datasets:<br>
0 for fake news<br>
1 for real news<br>
Manual Testing Set: Remove the last 10 rows from each dataset for manual testing.<br>
Data Processing

Merge Datasets: Combine fake and true news data for analysis.<br>
Data Cleaning: Drop unnecessary columns and preprocess the text by:<br>
Converting to lowercase<br>
Removing special characters, URLs, and extra spaces<br>
Model Training

The project employs various classification models to detect fake news, including:<br>

Logistic Regression<br>
Decision Tree Classifier<br>
Gradient Boosting Classifier<br>
Random Forest Classifier<br>
Each model's performance is evaluated based on accuracy, precision, and recall.<br>

## Manual Testing

You can test custom news articles using the manual_testing function, which provides predictions from all trained models. Simply input the news text, and the models will classify it as either "Fake News" or "Not A Fake News".<br>

## Usage

Clone the repository.<br>
Install required libraries.<br>
Load the datasets and preprocess the data.<br>
Train the models.<br>
Use the manual testing feature to evaluate custom news articles.<br>
Conclusion

This Fake News Detection project demonstrates the potential of machine learning in combating misinformation. By providing tools to analyze news articles, I aim to promote media literacy and awareness.<br>
