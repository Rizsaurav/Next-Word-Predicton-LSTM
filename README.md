# Next Word Prediction Using LSTM

## Project Overview

This project implements a Next Word Prediction model using a Long Short-Term Memory (LSTM) neural network. The model is trained on text data and is capable of predicting the next word in a given sequence of words. The project also includes a front-end application built using Streamlit, which allows users to input a sequence of words and receive the predicted next word in real-time.

## Features

- **LSTM Model**: A deep learning model trained on text data to predict the next word in a sequence.
- **Early Stopping**: Implemented to prevent overfitting during training.
- **Streamlit Front-End**: A simple, interactive UI to input text and view predictions.
- **Tokenizer**: Utilizes a tokenizer to convert text into sequences for the model.

## Project Structure

- `next_word_lstm.h5`: The trained LSTM model.
- `tokenizer.pickle`: The tokenizer used to preprocess the text data.
- `app.py`: The Streamlit application file.
- `requirements.txt`: List of Python packages required to run the project.
- `README.md`: Project documentation.

## Installation

To run this project locally, follow these steps:

## Clone the Repository

   ```bash
   git clone [https://github.com/Rizsaurav/Next-Word-Predicton-LSTM.git]
   cd Next-Word-Predicton-LSTM
