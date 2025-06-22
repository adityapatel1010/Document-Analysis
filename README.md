# Document Analysis: Summarization, Next-Word Prediction, and Text Correction

This project is a comprehensive document analysis system that brings together three powerful natural language processing (NLP) tools: **text summarization**, **next-word prediction**, and **auto-correction**. These features are implemented using deep learning techniques and made accessible through a simple Flask-based web application.

---

## Features

### 1. **Text Summarization**
- Built using a **Transformer model** to capture long-range dependencies and generate concise summaries.
- Helps condense lengthy input text into key information without losing context.

### 2. **Next-Word Prediction**
- Implemented using an **LSTM (Long Short-Term Memory)** network trained on custom text corpora.
- Predicts the most probable word to follow a given input sequence, aiding in smart text composition.

### 3. **Auto-Text Correction**
- Uses **Levenshtein Distance** (edit distance) to detect and correct spelling errors.
- Compares user input against a reference dictionary and suggests corrections with minimal character edits.

---

## Technologies Used

| Feature              | Technology                  |
|----------------------|-----------------------------|
| Text Summarization   | Transformer (TensorFlow)    |
| Next-Word Prediction | LSTM Neural Network         |
| Text Correction      | Levenshtein Distance        |
| Web App              | Flask (Python)              |
| Deep Learning        | TensorFlow, Keras           |

---

## Web Interface

The entire system is integrated into a lightweight web application built using **Flask**, providing a simple UI where users can:
- Paste or upload text
- View instant summaries
- Get suggestions for next words
- Auto-correct errors in real time

---

## Skills Demonstrated

- Sequence Modeling with LSTM and Transformers
- Edit Distance Algorithms
- Flask App Deployment
- Natural Language Processing (NLP)
- TensorFlow/Keras-based model integration

---

## Future Enhancements

- Fine-tune Transformer model with domain-specific corpora
- Add support for multi-language input
