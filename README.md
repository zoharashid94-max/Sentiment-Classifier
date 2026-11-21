# Sentiment Analysis Using Machine Learning

## Project Overview

This project focuses on classifying text into three sentiment categories: **Negative, Neutral, and Positive**. It was developed as part of my AI internship to practice text preprocessing, feature extraction, and machine learning model evaluation.

The project uses TF-IDF to convert text into numerical features and compares Logistic Regression and Linear Support Vector Machine (SVM) models to identify a suitable model for sentiment classification.

## Objectives

- Prepare and clean text data for analysis.
- Convert text into numerical features using TF-IDF.
- Compare different machine learning model configurations.
- Evaluate model performance using classification metrics.
- Test the model on example sentences.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorization
- Logistic Regression
- Linear Support Vector Machine (SVM)
- Matplotlib
- Google Colab

## Dataset

The project uses the **TweetEval sentiment dataset** from Cardiff NLP. The dataset contains text samples labelled as negative, neutral, or positive.

## Methodology

1. Load and explore the sentiment dataset.
2. Preprocess the text by cleaning and normalizing sentences.
3. Extract text features using TF-IDF.
4. Train and compare Logistic Regression and Linear SVM models with different parameter settings.
5. Select a model based on validation Macro F1.
6. Evaluate the selected model using accuracy, Macro F1, weighted F1, a classification report, and a confusion matrix.
7. Test the model on example sentences.

## Results

The model configurations were compared using validation performance. Logistic Regression with `C=2.0` achieved the highest validation Macro F1 score of **0.6456**, while Linear SVM with `C=0.5` achieved the highest validation accuracy of **0.6670** among the configurations tested.

The final test results and confusion matrix are available in the notebook.

