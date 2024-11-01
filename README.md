# BardBrainAI

BardBrain AI: Next Word Prediction System
Project Overview
BardBrain AI is a deep learning system that predicts the next word in a sequence using Shakespeare's Hamlet as training data. It uses LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural networks to understand and generate text patterns in Shakespearean style.
Technical Architecture
1. Data Processing Pipeline

Input Data Source: Shakespeare's Hamlet from NLTK Gutenberg corpus
Text Preprocessing:

Converts text to lowercase
Tokenization of words
Sequence generation for training
Padding sequences for uniform length



2. Machine Learning Models

Two Model Variants:

LSTM Network:

Embedding Layer (100 dimensions)
LSTM Layers (150 & 100 units)
Dropout (0.2) for regularization


GRU Network:

Embedding Layer (100 dimensions)
GRU Layers (150 & 100 units)
Dropout (0.2) for regularization





3. Training Features

Early stopping to prevent overfitting
Categorical crossentropy loss
Adam optimizer
Accuracy metrics tracking

4. Deployment

Streamlit web interface
Real-time prediction capability
Model and tokenizer serialization

Key Features

Next word prediction based on input sequence
Shakespearean language understanding
Interactive web interface
Support for variable-length input sequences
Real-time processing and prediction

Technical Components Used

Python
TensorFlow/Keras
NLTK
Streamlit
NumPy
Pickle

Usage Examples
pythonCopyInput: "To be or not to"
Output: "be"

Input: "Last night of all,When yond same"
Output: [predicted next word]
Applications

Creative Writing Assistance
Language Learning Tools
Shakespeare Study Aids
Interactive Literature Tools
