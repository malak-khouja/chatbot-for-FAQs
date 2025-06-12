# Chatbot for FAQs - CodeAlpha Internship Project

This is a simple chatbot that responds to frequently asked questions (FAQs) using Natural Language Processing (NLP). The chatbot preprocesses a dataset of FAQs, computes similarities between user queries and existing questions, and returns the most relevant answer.

## 🚀 Features

- Preprocessing with NLTK (lowercasing, punctuation/special character removal, tokenization, stopword removal, lemmatization)
- TF-IDF vectorization
- Cosine similarity for intent matching
- Command-line chatbot interface
- Mental health FAQs dataset

## 🧠 Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn (TF-IDF)
- Cosine similarity
- (Optional) TensorFlow Keras Tokenizer

## 📁 Dataset

The chatbot uses a CSV file (`Mental_Health_FAQ.csv`) containing:
- **Questions**
- **Answers**

## 💡 How It Works

1. The questions and answers are cleaned and preprocessed using NLP techniques.
2. A TF-IDF vectorizer is applied to represent the questions.
3. When a user inputs a query, the chatbot compares it with all FAQ questions using cosine similarity.
4. The most similar question is identified, and its answer is returned.

## 🎮 Demo

```text
You: what causes mental illness?
Bot: Mental illness can affect anyone regardless of age, income, or background...
