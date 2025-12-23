# LSTM Sentiment Analysis

**Role:** ML | **Context:** Applied Deep Learning (APS360)

## Project Overview
Developed a Deep Learning model to classify sentiment in news articles (Positive/Negative). Moved beyond baseline logistic regression by implementing a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) cells to capture temporal dependencies in text.

## Tech Stack
* **Framework:** PyTorch
* **Architecture:** LSTM, Word Embeddings (GloVe)
* **Tools:** Python, NumPy, Matplotlib

## Model Architecture
```mermaid
graph TD
    Input[Input Text] --> Embed[Embedding Layer]
    Embed --> LSTM1[LSTM Layer 1]
    LSTM1 --> LSTM2[LSTM Layer 2]
    LSTM2 --> Dense[Fully Connected Layer]
    Dense --> Softmax[Softmax Output]
    Softmax --> Class[Sentiment Prediction]
```

## Illustration of the overall pipeline
Inputs, preprocessing, 3 layer RNN, output and applications.

<img width="1338" height="772" alt="Screenshot 2025-12-23 at 5 09 22 PM" src="https://github.com/user-attachments/assets/017bdf96-e168-4246-9eec-5a2f400d4ea1" />
