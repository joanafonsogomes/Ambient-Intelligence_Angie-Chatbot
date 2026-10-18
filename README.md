# Angie — NLP & Sentiment Analysis Chatbot

**An interactive chatbot combining Natural Language Processing, intent classification, and sentiment analysis.**

Academic project developed at the University of Minho as part of the *Ambient Intelligence* course.

## Overview

Angie is a desktop chatbot designed to provide conversational interactions while identifying the emotional tone of user messages.

The application combines a neural network-based intent classification model with natural language processing techniques to generate responses and classify messages into three sentiment categories: **Positive, Neutral, and Negative**.

The project also explores user interaction tracking, data visualization, and customizable conversational responses.

## Tech Stack

| Area | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Keras, TensorFlow, NumPy |
| Natural Language Processing | NLTK, spaCy |
| User Interface | PyQt5 |
| Data Processing | Pandas |
| Data Visualization | Matplotlib |
| Communication | TCP Sockets |

## Key Features

- **Intent Recognition** — Neural network-based classification of user messages to identify conversational intents and select appropriate responses.
- **Sentiment Analysis** — Classification of messages as positive, negative, or neutral using NLP preprocessing and sentiment lexicons.
- **Interactive Chat Interface** — Desktop interface supporting real-time conversations.
- **Customizable Responses** — Users can add conversational patterns and corresponding responses.
- **Conversation Personalization** — A configurable set of predefined responses to common questions.
- **Interaction Analytics** — Logging and visualization of sentiment trends and interaction statistics.

## Machine Learning & NLP

The chatbot uses a feedforward neural network built with Keras to classify user intents.

The training pipeline includes:

1. Text tokenization and lemmatization using NLTK.
2. Bag-of-words feature extraction.
3. Intent classification using a neural network with two hidden layers and dropout regularization.
4. Response selection based on the predicted intent.

Sentiment analysis is implemented separately using spaCy preprocessing and positive/negative word lexicons.

## Architecture

The application follows a client-server approach, separating the graphical interface from the chatbot's response-processing service.

## Documentation

For a more detailed explanation of the implementation and project methodology, see the [project report](Angie_report.pdf).

## Project Context

Developed as a group assignment at the University of Minho.

The repository preserves the original academic implementation and its historical dependencies.

###### By [@joanafonsogomes](https://github.com/joanafonsogomes), [@DxMonteiro](https://github.com/DxMonteiro), [@mariajbp](https://github.com/mariajbp) & [@SusanaMarques](https://github.com/SusanaMarques)
