🧠 Duplicate Question Pair Predictor

Duplicate Question Pair Predictor is an NLP-based machine learning application that classifies whether two questions convey the same meaning. By leveraging similarity-based features, vectorization techniques (Bag-of-Words + TF-IDF), and fuzzy matching, the model identifies redundant queries in Q&A systems.

🚀 Features

Natural Language Processing pipeline using tokenization, stopword removal, and text normalization

Multi-feature engineering including token overlap, length-based metrics, and fuzzy string similarity

Vectorization using Bag-of-Words and TF-IDF for capturing semantic and lexical patterns

Machine learning model for binary classification (duplicate vs non-duplicate)

Optional web interface via Streamlit/Flask for real-time prediction

🧩 Skills Demonstrated

NLP Text Preprocessing & Feature Engineering

TF-IDF + Bag-of-Words Vectorization

Machine Learning (Classification)

Fuzzy Matching for Approximate Similarity

Deployment Ready (Flask/Streamlit)

🧰 Tech Stack

Python

Pandas & NumPy

Scikit-learn

NLTK / spaCy

FuzzyWuzzy

Streamlit

📦 How It Works

The model analyzes both questions through:

✔ Text Cleaning (lowercasing, punctuation removal, tokenization)
✔ Feature Extraction (fuzzy ratios, word overlap, length diff)
✔ Vectorization (BoW + TF-IDF)
✔ Classification (duplicate or not)

This combination helps capture semantic similarity without heavy deep learning models.

🎯 Use-Cases

Q&A Platforms (Quora, StackOverflow)

Chatbots & Support Systems

FAQ Organization

Content De-duplication

If you want, I can also add:

🔗 Live Demo link - (https://duplicate-question-pair-predictor-kishlay.onrender.com/)
