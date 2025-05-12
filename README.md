# Twitter Sentiment Analysis with Logistic Regression

This repository contains a simple yet effective sentiment analysis project using the [Twitter Sentiment Analysis Dataset]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)). The goal is to classify tweet sentiments toward specific entities as **Positive**, **Negative**, **Neutral**, or **Irrelevant**.

## Methodology

### Text Preprocessing
- Tokenization
- Stopwords removal
- Regular expression cleaning
- Lowercasing

### Tools & Libraries
- **NLP**: `NLTK` for preprocessing
- **Text Cleaning**: `re` for regex
- **ML Framework**: Scikit-learn
- **Data Handling**: Pandas

### Model
- Logistic Regression (Baseline)

## Evaluation Results

Performance on `twitter_validation.csv`:

| Class      | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|---------|
| Irrelevant | 0.80      | 0.90   | 0.84     | 172     |
| Negative   | 0.84      | 0.83   | 0.84     | 266     |
| Neutral    | 0.86      | 0.82   | 0.84     | 285     |
| Positive   | 0.86      | 0.84   | 0.85     | 277     |

**Overall Metrics**:
- Accuracy: 84%
- Macro Avg F1: 84%
- Weighted Avg F1: 84%
