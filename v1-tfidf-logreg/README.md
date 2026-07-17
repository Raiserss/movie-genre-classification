# Movie Genre Classification - V1

## Objective

Build a baseline NLP model to classify movie genres based on movie overviews.

## Dataset

- TMDB 5000 Movies

## Preprocessing

- Lowercase
- Remove punctuation
- Remove ordinal numbers
- Remove numbers
- Remove extra spaces

## Feature Extraction

- TF-IDF
- max_features = 5000
- unigram

## Model

- Logistic Regression

## Evaluation

- Accuracy: 39.34%

## Limitations

- Single-label classification
- Imbalanced classes
- No stopword removal
- No hyperparameter tuning
- No n-grams
