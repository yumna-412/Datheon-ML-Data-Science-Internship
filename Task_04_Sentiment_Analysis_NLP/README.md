# Task 04 – Sentiment Analysis using NLP

## Project Overview
This project implements a Natural Language Processing (NLP) pipeline to classify customer product reviews into positive, negative, and neutral sentiments using machine learning algorithms.

## Dataset
- File: `sentiment_reviews.csv`
- Total Records: 10
- Features: Review ID, Review Text, Sentiment
- Target Variable: Sentiment

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF Vectorizer
- Jupyter Notebook

## Project Workflow
1. Load the sentiment reviews dataset.
2. Clean and preprocess review text.
3. Convert text into lowercase.
4. Remove HTML tags and punctuation.
5. Perform tokenization and stopword removal.
6. Apply lemmatization.
7. Convert text into numerical features using TF-IDF.
8. Train Multinomial Naive Bayes and Logistic Regression models.
9. Evaluate models using accuracy, classification reports, and confusion matrices.
10. Create an interactive sentiment prediction function.

## Machine Learning Models
- Multinomial Naive Bayes
- Logistic Regression

## Interactive Prediction
The `predict_sentiment()` function accepts custom review text and returns predictions from both trained models.

## Project Files
- `Sentiment_Analysis.ipynb` – Complete NLP classification pipeline.
- `sentiment_reviews.csv` – Dataset containing customer reviews.
- `README.md` – Project documentation.

## Limitations
The supplied dataset contains only 10 records. Therefore, model accuracy and predictions are intended for demonstration purposes and should not be considered reliable real-world performance.

A larger and more balanced dataset is required to improve model performance and generalization.

## Conclusion
This project demonstrates an end-to-end NLP sentiment classification workflow, including text preprocessing, TF-IDF feature extraction, machine learning model training, evaluation, and interactive sentiment prediction.