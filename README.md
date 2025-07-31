# Book Review Sentiment Classifier

The model predicts whether a book review is positive or negative using natural language processing and logistic regression.

# ☆ Overview

This project applies the full machine learning lifecycle to solve a binary classification problem.
Using the Book Reviews dataset, the goal was to train a model that performs sentiment analysis on user-submitted reviews.

# ✮ Objectives

- Build a binary classification model using TF-IDF and logistic regression
- Apply NLP techniques for feature engineering and data preparation
- Evaluate performance using classification metrics and visualizations
- Reflect on model improvement using n-gram tuning and preprocessing strategies

# ⊹ Tools & Technologies

- Python, NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn (LogisticRegression, TF-IDF, train_test_split, metrics)
- Jupyter Notebooks

# ˖ Model Performance

Achieved **88% accuracy** with balanced precision and recall:
- Preprocessing included lowercasing, punctuation removal, and TF-IDF vectorization with trigrams
- Hyperparameters tuned using 'min_df=4' and 'ngram_range=(1,3)'
- Evaluated using accuracy, precision, recall, F1 score, and a confusion matrix heatmap

# ⊹ File Structure

| File                          | Purpose
|-------------------------------|---------------------------------------------------------|
| DefineAndSolveMLProblem.ipynb | Jupyter notebook with full code, output, and commentary |
| DefineAndSolveMLProblem.ipynb | Printable version with all markdown and plots           |
| bookReviewsData.csv           | training dataset used for model development             |

# ✮ Key Takeaways

This project demonstrates how simple processing steps and thoughtful feature engineering can create effective models when paired with strong data understanding.

# ☆ Future Work

- Explore deep learning approaches
- Deploy as a web app to classify user-submitted reviews in real-time
- Expand the dataset for a more robust evaluation

# ˖ Program Info

This project was completed as a part of the **Break Through Tech AI Program** (Summer 2025).
