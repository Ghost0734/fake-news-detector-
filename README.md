# Fake News Detector

Built a machine learning model that classifies news articles as fake or real, 
hitting 98.86% accuracy on a dataset of ~45,000 articles.

## Dataset
Pulled from Kaggle — [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- 23,481 fake articles
- 21,417 real articles

## What I did
- Cleaned and preprocessed the text (lowercasing, removing punctuation, stopwords)
- Used TF-IDF to convert articles into numerical features
- Trained a Logistic Regression classifier on 80% of the data
- Tested on the remaining 20%

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 98.86% |
| Precision | 99% |
| Recall | 99% |
| F1-Score | 99% |

## Tech used
Python, Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn, Google Colab

## Files
- `fake_news_detector.ipynb` — the full notebook
- `fake_news_model.pkl` — saved model
- `tfidf_vectorizer.pkl` — saved TF-IDF vectorizer

## Author
Abhishek Sharma — [GitHub](https://github.com/Ghost0734)
