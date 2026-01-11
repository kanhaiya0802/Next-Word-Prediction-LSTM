# Next-Word-Prediction-LSTM-RNN

This project implements a Next Word Prediction system using a Long Short-Term Memory (LSTM) Recurrent Neural Network.  
The model is trained on text data to predict the most likely next word for a given input sequence.

An interactive Streamlit web application is included to test the trained model.

---

## Project Overview

Next word prediction is a fundamental Natural Language Processing (NLP) task used in applications such as text autocompletion, chatbots, and language modeling.  
This project uses an LSTM-based neural network to learn word sequences and predict the next word based on previous context.

---

## Technologies Used

- Python 3.11  
- TensorFlow / Keras  
- NumPy  
- Streamlit  
- Pickle  

---

## Project Structure

Next-Word-Prediction-LSTM/
  ├── app.py # Streamlit application
  ├── experiments.ipynb # Model training and experiments
  ├── description.ipynb # Project explanation and notes
  ├── next_word_lstm.keras # Trained LSTM model
  ├── tokenizer.pickle # Saved tokenizer
  ├── requirements.txt # Project dependencies
  └── README.md


---

## How the Model Works

1. Text data is tokenized and converted into sequences.
2. Input sequences of length (n-1) are used to predict the nth word.
3. An Embedding layer converts words into dense vectors.
4. Stacked LSTM layers learn sequential patterns in the text.
5. A Softmax output layer predicts the probability of the next word.

Early stopping is used during training to prevent overfitting.

---

Author

Kanhaiya Jee
B.Tech IT Student
