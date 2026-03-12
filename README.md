# Fake News Detection using BERT

## Problem Statement
Fake news spreads rapidly through digital platforms and social media, making it difficult for users to identify reliable information. The goal of this project is to build a machine learning model that can classify news articles as Fake or Real.

## Approach
The project follows a Natural Language Processing pipeline:
- Data exploration
- Text preprocessing
- Tokenization using BERT tokenizer
- Train-test split
- Model training
- Model evaluation
- Error analysis
- Model improvement
- Deployment

## Model Used
The project uses BERT for sequence classification.  
An experiment was also conducted using DistilBERT for comparison.

## Metrics
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Final Accuracy: **50.7%**

## Improvements
DistilBERT was tested as an alternative model to compare performance and efficiency.

## Key Learnings
- Understanding NLP pipelines
- Transformer models
- Tokenization
- Model evaluation
- Error analysis
- Model deployment

## Deployment
A simple interface was created where users can input a news headline and the model predicts whether it is Fake or Real.
