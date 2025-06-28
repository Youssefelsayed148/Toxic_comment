# Toxic_comment_classification
A deep learning project to classify toxic comments using various neural network architectures including Dense, LSTM, GRU, BiLSTM, and Conv1D.

## 🚀 Features

- Text preprocessing (contractions, lemmatization, emoji handling)
- Embedding and vectorization
- Training multiple deep learning models
- Performance comparison across models

## 🧾 Dataset

The dataset used is **[Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)**.

Columns:
- `comment_text`: The text of the comment
- `toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, `identity_hate`: Binary labels

## 🧪 Models Used

1. Simple Dense Neural Network
2. LSTM (RNN)
3. GRU
4. Bidirectional LSTM
5. Conv1D

## 📈 Evaluation

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 🧼 Preprocessing

- Remove stopwords
- Expand contractions
- Lemmatization using `WordNetLemmatizer`
- Handle emojis using the `emoji` package

