# Spam Email Classification with Machine Learning

## Overview

This project focuses on the classification of spam emails using machine learning models. The primary objective is to develop a system capable of accurately distinguishing between spam and non-spam (ham) emails.

## Dataset

The dataset used in this project consists of labeled emails, where each email is categorized as either spam or ham.

## Methodology

1. **Data Preprocessing**: The dataset is preprocessed to extract relevant features from the text, such as word frequencies or presence of certain keywords. Common preprocessing steps include tokenization, removing stop words, and vectorization.
2. **Model Selection**:
   - **Multinomial Naive Bayes (MultinomialNB)**: Based on Bayes' theorem, this model is particularly suitable for text classification tasks like spam detection.
   - **Linear Support Vector Classifier (LinearSVC)**: Linear SVC is a powerful algorithm for classification tasks, especially for high-dimensional data like text.
3. **Training and Evaluation**: The models are trained on a portion of the labeled dataset and evaluated using a separate test set to assess their performance. Performance metrics such as confusion matrix and accuracy score are calculated to measure the effectiveness of each model in correctly classifying spam and ham emails.

## Results

The final output of the project includes the confusion matrix and accuracy score for both models. These metrics provide insights into the models' performance, allowing stakeholders to make informed decisions about deploying the spam detection system.

## Usage

1. Clone the repository: `git clone https://github.com/hiroonwijekoon/spam-email-classifier.git`
2. Install the required dependencies.
3. Run the provided scripts to preprocess the data, train the models, and evaluate their performance.
