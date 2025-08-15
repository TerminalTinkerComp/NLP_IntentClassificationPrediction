# NLP_IntentClassificationPrediction
This Python code trains a machine learning model to classify sentences into different intents. It uses a TF-IDF vectorizer to convert text into numerical features and a Multinomial Naive Bayes classifier to predict whether a sentence is a question, statement, or advice.

<img width="780" height="211" alt="image" src="https://github.com/user-attachments/assets/1eda2618-2f67-404d-890a-e51f63c87008" />

\n
Purpose: Learns to understand the purpose of different sentences. A list of sentences is already labeled as a question, statement, or advice. The code first "studies" these examples. It breaks down each sentence into its most important words and phrases using a technique called TF-IDF, which helps it figure out which words are most important for each category. For instance, words like "what," "where," and "how" are important for the question category. After learning from the train data, the code can take a brand-new sentence it has never seen before and predict what its purpose is—whether it's a question, a statement, or a piece of advice. The code essentially builds a "mental map" of word patterns for each purpose, allowing it to make educated guesses on new text.
