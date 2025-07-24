# Reddit Rule Violation Detection

This project aims to detect rule violations in Reddit comments by analyzing text data from specific subreddits. The goal is to build a machine learning model that can automatically identify whether a comment violates subreddit rules such as "No legal advice" or "No advertising."

## Project Overview

- **Dataset:** Reddit comments labeled with rules and whether they violate those rules.
- **Problem:** Binary classification — predict if a comment violates a given rule.
- **Approach:** 
  - Exploratory Data Analysis (EDA) to understand text patterns and class distributions.
  - Text preprocessing and feature engineering.
  - Model building and evaluation.

## Current Progress

- Completed thorough **Exploratory Data Analysis (EDA)**:
  - Analyzed class distributions and rule violation rates.
  - Extracted basic text statistics (lengths, punctuation, capitalization).
  - Identified important text features correlated with rule violations.

## What’s Left to Do

The project is currently ongoing and EDA has been completed. Planned next steps include:

1. **Text Preprocessing and Cleaning**
   - Lowercasing, removing URLs, mentions, punctuation.
   - Stopword removal and lemmatization.
   - Cleaning raw text to improve model input quality.

2. **Feature Extraction**
   - Convert cleaned text into numerical features using techniques like:
     - TF-IDF vectors.
     - Word embeddings (e.g., Word2Vec, GloVe, or transformers).

3. **Modeling**
   - Train classification models such as Logistic Regression, Random Forest, or neural networks.
   - Perform hyperparameter tuning and cross-validation.
   - Evaluate models using appropriate metrics (accuracy, F1-score, ROC-AUC).

4. **Error Analysis and Iteration**
   - Analyze model errors to identify weaknesses.
   - Experiment with rule-specific models or data augmentation.
   - Iterate on preprocessing and feature engineering.

5. **Deployment (Optional)**
   - Package the model into an API or web app for real-time violation detection.

---

## Project Structure

├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── src/ # Source code for preprocessing, modeling, etc.
├── README.md # Project overview and instructions
└── requirements.txt # Python dependencies
