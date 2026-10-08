# Movie Genre Classification

## Intern Name
Reshma

## Internship
CODETECH Internship

## Project Title
Movie Genre Classification Using Machine Learning

## Project Overview
This project predicts the genre of a movie based on its
description using Natural Language Processing (NLP) and
Machine Learning techniques.

## Objectives
- Process movie descriptions.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression classification model.
- Predict movie genres from descriptions.
- Evaluate model performance.

## Technologies Used
- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- TF-IDF Vectorization
- Logistic Regression
- Joblib

## Project Workflow
1. Load the movie dataset.
2. Prepare the movie descriptions and genre labels.
3. Split the dataset into training and testing sets.
4. Apply TF-IDF vectorization.
5. Train the Logistic Regression model.
6. Predict genres for test descriptions.
7. Evaluate the model using accuracy and a classification report.
8. Save the trained model and vectorizer.

## Model Details
Algorithm: Logistic Regression
Feature Extraction: TF-IDF
Number of Training Samples: 190604
Number of Testing Samples: 47652

## Results
Test Accuracy: 33.93%

## Sample Prediction
Movie Description:
A brave detective investigates a mysterious murder
and searches for clues to catch a dangerous criminal.

Predicted Genre:
Crime

## Limitations
The model may confuse similar movie genres.
Its prediction accuracy can be improved through further
data cleaning, feature engineering, and model tuning.

## Future Improvements
- Experiment with other machine learning algorithms.
- Improve text preprocessing.
- Tune model parameters.
- Explore more advanced NLP methods.

## Conclusion
This project demonstrates how NLP and machine learning
can be used to classify movie genres from text descriptions.