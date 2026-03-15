# IMDB Sentiment Analysis using RNN

This project implements a **Sentiment Analysis model** on the **IMDB Movie Reviews dataset** using a **Recurrent Neural Network (RNN)**.  
The model classifies movie reviews as **positive or negative** based on their textual content.

The project demonstrates the application of **Natural Language Processing (NLP)** and **Deep Learning** techniques for text classification.

---

## 📊 Dataset

Dataset used: **IMDB Movie Reviews Dataset**

- 50,000 movie reviews
- Binary sentiment classification
- Labels: **Positive / Negative**

Each review is preprocessed before being fed into the neural network.

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- NLP preprocessing techniques

---

## 🧹 Text Preprocessing

The following preprocessing steps were applied:

- Lowercasing text
- Removing HTML tags
- Removing punctuation
- Tokenization
- Removing stopwords
- Stemming
- Encoding
- Vectorization

These steps help convert raw text into numerical representations suitable for deep learning models.

---

## 🧠 Model Architecture

The model is built using a **Recurrent Neural Network (RNN)**.

Architecture:

Input Layer  
Embedding Layer  
Recurrent Neural Network (RNN) Layer  
Fully Connected Layer  
Sigmoid Activation (Binary Classification)

---

## 🚀 Training

The dataset was split into:

- **Training Set**
- **Test Set**

The model was trained to minimize **binary classification loss** and evaluated on the test dataset.

---

## 📈 Results

The model successfully learns to classify movie reviews based on sentiment.

Evaluation metrics include:

- Accuracy
- Loss

---

## 📂 Project Structure

IMDB-Sentiment-RNN
│
├── data
│
├── notebook
│ └── sentiment_analysis.ipynb
│
├── model
│ └── rnn_model.py
│
├── README.md
│
└── requirements.txt

---

## 🖼️ Example Prediction

Review:**This movie was absolutely fantastic with great performances.**
Prediction:**Positive Sentiment**

---

## 💡 Future Improvements

- Use **LSTM or GRU** for better long-term dependency learning
- Implement **attention mechanisms**
- Use **pretrained embeddings like GloVe or Word2Vec**

---

## 👩‍💻 Author

**Bidisha Das**

AI & Machine Learning Enthusiast  
Interested in Deep Learning, NLP and AI Applications.



---
