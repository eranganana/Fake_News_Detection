# Fake News Detection using Machine Learning for Data minning course work

## Project Overview
This project uses KMeans clustering and TF-IDF vectorization to classify news articles as either "Fake" or "True".

## Dataset
- `Fake.csv`: Contains sample of fake news articles
- `True.csv`: Contains sample of legitimate news articles
- Both datasets include article text, titles, and subjects

## How It Works
1. Text preprocessing (lowercase, remove punctuation, URLs, special characters)
2. TF-IDF feature extraction from article text, title, and subject
3. KMeans clustering (2 clusters - Fake vs True)
4. Prediction function for new articles

## Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib
- scipy

## Usage
Run the Jupyter notebook and follow the prompts to enter:
- News article text
- Article title
- Article subject

The model will predict whether the news is Fake or True.

## Results
The model achieves a silhouette score of 0.09, indicating good separation between clusters.

## Author
Achini Eranga Nanayakkara
