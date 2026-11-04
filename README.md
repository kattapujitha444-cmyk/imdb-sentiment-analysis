# IMDb Movie Review Sentiment Analysis

A machine learning project that classifies IMDb movie reviews as **positive** or **negative** using Natural Language Processing (NLP).

## Overview
This project cleans raw review text, converts it into numerical features using TF-IDF, and compares three classification models to find the best performer.

## Dataset
- IMDb Dataset of 50K Movie Reviews: [Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- 50,000 reviews, labelled positive or negative

## Workflow
1. Data loading and exploration
2. Text preprocessing (lowercasing, removing HTML tags and punctuation, stopword removal, **[stemming/lemmatization]**)
3. Feature extraction using TF-IDF
4. Model training: Naive Bayes, Logistic Regression, SVM
5. Evaluation using accuracy, precision, recall and F1-score

## Results
| Model | Accuracy |
|---|---|
| Naive Bayes | [X]% |
| Logistic Regression | [X]% |
| SVM | [X]% |

**Best model:** [model name] with [X]% accuracy.

## Tech Stack
Python, Pandas, NumPy, NLTK, scikit-learn, Matplotlib, Seaborn

## How to Run
1. Clone the repository
   ```
   git clone https://github.com/kattapujitha444-cmyk/imdb-sentiment-analysis.git
   ```
2. Install the libraries
   ```
   pip install -r requirements.txt
   ```
3. Download the dataset from the Kaggle link above and place it in the project folder
4. Open the notebook in Jupyter and run all cells

## Future Improvements
- Try deep learning models (LSTM, BERT)
- Build a simple web app to predict sentiment of any review

## Author
**Pujitha** | [GitHub](https://github.com/kattapujitha444-cmyk)
