# LSTM-Based Next Word Predictor Using Human Conversational Data

This repository contains code and resources for building a **Next Word Prediction** model using **LSTM (Long Short-Term Memory)** neural networks trained on **human conversational data**.

---

## 📌 **Project Overview**

The aim of this project is to train an **LSTM-based Recurrent Neural Network** to predict the next word in a sentence based on conversational data. This can be useful in applications like **chatbots**, **smart keyboards**, or **autocomplete systems**.

---

##Model Architecture
##  Model Architecture

- **Embedding Layer**  
  Converts input words into dense vectors.

- **LSTM Layer (100 units)**  
  Processes sequences and captures context.

- **Dense Layer**  
  Outputs a probability distribution over the vocabulary.

- **Activation Function:**  
  `softmax` — used for multi-class classification to predict the next word.
