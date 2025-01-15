
# Bank FAQ Chatbot

This project implements a simple chatbot using a Support Vector Machine (SVM) to answer frequently asked questions (FAQs) about banking.  It utilizes a dataset of bank-related questions and their corresponding answers to provide relevant information to user queries.

## Features

* **Natural Language Processing (NLP):** The chatbot preprocesses user input using techniques like tokenization, stop word removal, and punctuation handling to improve accuracy.
* **TF-IDF Vectorization:** Converts text data into numerical vectors using Term Frequency-Inverse Document Frequency (TF-IDF), enabling the SVM to process the input effectively.
* **Support Vector Machine (SVM):** Employs an SVM classifier to categorize user questions into predefined classes based on the FAQ dataset.
* **Cosine Similarity:** Calculates cosine similarity between the user's input and questions within the predicted class to identify the most relevant answer.
* **Gradio Interface:** Provides a user-friendly web interface for interacting with the chatbot.

## Requirements

* Python 3.9+
* pandas
* scikit-learn
* nltk
* gradio

Install necessary libraries using pip:
