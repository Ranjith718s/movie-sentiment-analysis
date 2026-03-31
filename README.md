## Dataset
[IMDB 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) — Download from Kaggle and place `IMDB Dataset.csv` in the root folder before running.

# Movie Sentiment Analysis (NLP)

Classifying IMDB movie reviews as Positive or Negative using NLP and Machine Learning.

## Overview
Built a binary sentiment classifier on 50,000 IMDB reviews using text
preprocessing and TF-IDF vectorisation.

## Dataset
[IMDB 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Results
| Model | Accuracy |
|---|---|
| Naive Bayes | ~85% |
| **Logistic Regression** | **~88%** |

## Key Steps
- Removed HTML tags, special characters and stopwords
- Applied TF-IDF vectorisation with bigrams (10,000 features)
- Evaluated using accuracy, precision, recall and F1-score

## Tech Stack
Python, NLTK, Scikit-learn, Matplotlib, Seaborn, Google Colab

## How to Run
1. Open `movie_sentiment_analysis.ipynb` in Google Colab
2. Upload `IMDB Dataset.csv` when prompted
3. Run all cells — last cell lets you test your own reviews!
