# Project 4 - IMDB Movie Review Sentiment Analysis

## Overview

This project was completed as part of my Decode Lab Data Science Internship.

The objective of this project was to build a Sentiment Analysis model capable of classifying IMDB movie reviews as either Positive or Negative using Natural Language Processing (NLP) and Machine Learning techniques.

The project covers the complete workflow from text preprocessing and feature extraction to model training, evaluation, and prediction on custom reviews.

---

## Dataset Information

The dataset consists of IMDB movie reviews along with their corresponding sentiment labels.

### Features

- Review – Movie review text
- Sentiment – Positive or Negative sentiment label

### Dataset Size

- Total Records: **46,679**
- Total Features: **2**

---

## Project Workflow

1. Importing Required Libraries
2. Loading the Dataset
3. Understanding the Dataset
4. Text Data Preprocessing
5. Feature Extraction using TF-IDF
6. Building and Training the Sentiment Classification Model
7. Testing the Model on Custom Reviews
8. Conclusion

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-Learn
- Jupyter Notebook

---

## Text Preprocessing

The following preprocessing techniques were applied to the review text:

- Conversion to lowercase
- Removal of HTML tags
- Removal of URLs
- Removal of special characters and punctuation
- Stopword removal
- Word stemming using Porter Stemmer

The cleaned reviews were then used for feature extraction.

---

## Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) Vectorization was used to convert textual reviews into numerical feature vectors.

- Maximum Features Used: **5000**
- Output Feature Matrix Shape: **(46679, 5000)**

---

## Machine Learning Model

The sentiment classification model was built using:

### Multinomial Naive Bayes

The dataset was divided into:

- Training Set: 80%
- Testing Set: 20%

using `train_test_split()` from Scikit-Learn.

---

## Model Performance

### Accuracy Score

**85.13%**

### Classification Metrics

| Metric | Score |
|----------|----------|
| Precision | 0.85 |
| Recall | 0.85 |
| F1-Score | 0.85 |

The confusion matrix was also generated to evaluate prediction performance on unseen data.

---

## Custom Review Prediction

The trained model was tested on custom movie reviews and successfully predicted whether a review expressed a positive or negative sentiment.

This demonstrates the practical application of the model for real-world text classification tasks.

---

## Key Learnings

- Text preprocessing using NLP techniques
- Feature extraction with TF-IDF
- Sentiment classification using Naive Bayes
- Model evaluation using Accuracy, Precision, Recall, and F1-Score
- Working with real-world textual datasets
- Building end-to-end Machine Learning pipelines

---

## How to Run

1. Clone the repository.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Run all notebook cells sequentially.
5. Train the model and test custom movie reviews.

---

## Author

**Gunjan Ahuja**

Decode Lab Data Science Internship
