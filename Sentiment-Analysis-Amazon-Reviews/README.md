# Amazon Sentiment Analysis

This project analyzes sentiment in Amazon product reviews using Natural Language Processing (NLP) techniques and machine learning models. It provides insights into customer sentiment (Positive, Neutral, Negative) based on their review text, leveraging Python libraries such as `scikit-learn`, `pandas`, `nltk`, and `matplotlib`.

---

## Project Overview

The main goal of this project is to classify Amazon product reviews into three categories: **Positive**, **Neutral**, and **Negative**. The project follows these steps:

1. **Data Collection**:
   - The dataset was sourced from Kaggle (Amazon product reviews dataset).
   - Approximately 10,000 reviews were used for this analysis.

2. **Data Preprocessing**:
   - Cleaning text data: Removing punctuation, stopwords, and lemmatization.
   - Label encoding: Converting sentiment labels into numerical format for machine learning models.

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing the distribution of sentiments in the dataset.

4. **Feature Engineering**:
   - Creating a bag-of-words representation using `TfidfVectorizer`.

5. **Model Building**:
   - Training a Logistic Regression model to classify sentiment.
   - Fine-tuning the model using `GridSearchCV`.

6. **Evaluation**:
   - Evaluating model performance with accuracy, precision, recall, F1-score, and a confusion matrix.

---

## Key Results

- **Baseline Model Accuracy**: 77%.
- **Fine-Tuned Model Accuracy**: 79%.
- The model performed well for positive sentiment but struggled to accurately classify neutral sentiment due to class imbalance.

---

## Files and Folders

- **`Amazon-Sentiment-Analysis.ipynb`**: The main Jupyter Notebook containing all code and outputs for this project.
- **`README.md`**: This file explaining the project.
- **`requirements.txt`**: List of required Python libraries to run the project.
- **`data/`**: Folder containing the dataset used in this project (or a reference to its source).
- **`images/`**: Visualizations such as confusion matrix and distribution plots generated during the analysis.

---

## Installation and Setup

To replicate this project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Key-Projects.git
   cd Key-Projects/Amazon-Sentiment-Analysis

