

# Basic AI Chatbot - Data Science Assistant

This is a simple AI chatbot developed in Python, trained on a custom text file that contains information about Data Science. The chatbot utilizes text preprocessing, TF-IDF vectorization, and cosine similarity to respond to user queries.

## Features
- Responds to basic user queries about Data Science.
- Greets users and engages in basic conversation.
- Implements simple text preprocessing and response generation using Natural Language Processing (NLP) techniques.

## Technologies Used
- **Python**
- **Numpy**
- **NLTK** (Natural Language Toolkit)
- **TF-IDF Vectorizer**, **Cosine Similarity** (Scikit-learn)

## Project Overview

### 1. Importing and Reading the Corpus
The chatbot is trained using a text file (`corpus.txt`) that contains Data Science-related content. This file is read and processed to form the basis of the chatbot’s responses.

### 2. Text Preprocessing
The chatbot preprocesses the text by performing tokenization and lemmatization. This helps normalize the text, making it easier for the chatbot to understand and match user input.

### 3. Greeting Function
A basic greeting function allows the chatbot to recognize common greetings from the user and respond appropriately.

### 4. Response Generation
The chatbot uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization and cosine similarity to generate responses. This technique allows it to match user queries with the most relevant content from the text file.

### 5. Defining Conversations: Start/End Protocol
The chatbot is programmed to engage in conversations until the user signals the end by typing a predefined exit command (e.g., "bye"), at which point the chatbot ends the conversation politely.

## How to Use
1. Clone this repository to your local machine.
2. Install the necessary dependencies.
3. Run the chatbot script, and start interacting by asking Data Science-related questions.
4. Type `bye` to end the conversation.

## Future Improvements
- Expand the training corpus to include more topics.
- Implement more advanced NLP techniques for better response generation.
- Enhance the chatbot’s conversational abilities for more natural interactions.


