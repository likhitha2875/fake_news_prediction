# fake_news_prediction

 Overview
This project builds an efficient Fake News Detection System using:

TF-IDF vectorization with n-grams

Passive-Aggressive Classifier (faster, scalable alternative to traditional logistic regression)

NLP preprocessing (stemming, stopword removal)

The system predicts whether a news article is real or fake with high accuracy, making it suitable for deployments in news verification systems, journalism, and social media monitoring.

 Features
✅ High-accuracy (~98-99%) fake news classification
✅ Uses Passive-Aggressive online learning for faster training on large datasets
✅ Colab-compatible and GPU-friendly
✅ Clean pipeline structure for easy understanding and extension
✅ Preprocessing using NLTK for noise reduction
✅ Scalable for real-time detection pipelines

🗂️ Dataset
Uses train.csv containing:

id: Article ID

title: Article title

author: Article author

text: Full/partial article text

label: 0 (Real) or 1 (Fake)

⚙️ Dependencies
Run in Google Colab with:

bash
Copy
Edit
pip install nltk scikit-learn pandas
