# Fake News Detection using BERT

## Problem Statement
Fake news spreads rapidly through digital platforms and social media, making it difficult for readers to identify reliable information. The objective of this project is to build a machine learning model that can automatically classify news articles as **Fake** or **Real** using Natural Language Processing techniques.

---

## Dataset
The dataset used in this project contains approximately **20,000 news articles**. It includes several columns such as:

- Title
- Text
- Date
- Source
- Author
- Category
- Label

The **label column** indicates whether the news article is *Fake* or *Real*.  
The dataset is relatively balanced with nearly equal samples from both classes.

---

## Approach
The project follows a complete **Natural Language Processing pipeline**:

1. Dataset exploration and understanding
2. Text preprocessing and cleaning
3. Tokenization using a transformer tokenizer
4. Train-test data split
5. Fine-tuning a pretrained transformer model
6. Model evaluation using classification metrics
7. Error analysis
8. Model improvement
9. Deployment using an interactive interface

---

## Model Used
The model used in this project is **BERT (Bidirectional Encoder Representations from Transformers)** for sequence classification. BERT is a powerful transformer-based language model capable of understanding contextual relationships in text data.

An additional experiment was conducted using **DistilBERT**, a smaller and faster version of BERT, to compare performance and efficiency.

---

## Evaluation Metrics
The model performance was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

<img width="801" height="627" alt="confusion_matrix" src="https://github.com/user-attachments/assets/80878b00-76d7-4237-8a39-3de78fefb284" />

Final Model Accuracy:

**50.7%**

---

## Improvements
To explore possible improvements, the project compared the performance of **BERT** and **DistilBERT** models. DistilBERT provides similar performance while being more computationally efficient due to its smaller architecture.

---

## Key Learnings
Through this project, the following concepts were learned:

- Natural Language Processing workflows
- Transformer-based language models
- Tokenization and text representation
- Model fine-tuning techniques
- Evaluation metrics for classification models
- Error analysis in machine learning models
- Deployment of ML models using simple interfaces

---

## Deployment
A simple interactive interface was created where users can enter a **news headline or text**, and the trained model predicts whether the news is **Fake** or **Real**.

This demonstrates how a machine learning model can be integrated into a basic application for real-time predictions.

<img width="1917" height="1004" alt="deployment_demo" src="https://github.com/user-attachments/assets/4b7e9c40-53cd-4b8e-82eb-713a2105785f" />

