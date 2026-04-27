# Sentiment-analysis-transformers
Fine-tuning a pre-trained transformer model for sentiment analysis on movie reviews.

This project implements a **sentiment polarity classifier** using a pre-trained transformer model, as part of an NLP assignment.

## 📌 Overview
The goal of this project is to explore how **pre-trained language models** (e.g., BERT) can be applied to a sentiment classification task.

Instead of building a model from scratch, this project leverages **Hugging Face Transformers** to load a pre-trained model and fine-tune it for binary sentiment classification.

## 🧠 Model Architecture
The model consists of:

- A pre-trained transformer encoder (e.g., BERT / DistilBERT)
- A custom classification head (fully connected layer)
- Softmax output for sentiment prediction (positive / negative)

## 📊 Dataset
- **Large Movie Review Dataset (IMDB)**
- 50,000 movie reviews
- Predefined training and test splits

## ⚙️ Implementation Details
- Framework: PyTorch
- Library: Hugging Face Transformers
- Training: Fine-tuning (partial or frozen transformer)

## 📈 Results
The model is evaluated using:
- Accuracy
- Loss curves during training

A **random baseline** is included for comparison.

> Note: The focus of this project is on applying transformer models, not achieving state-of-the-art performance.

## 📉 Example Outputs
- Training loss curve
- Accuracy over epochs

## 💡 Reflections
### Challenges
- Managing GPU memory when loading transformer models
- Understanding tokenization and input formatting

### What I Learned
- How transformer models are used in practice
- Fine-tuning pre-trained models for classification
- Using Hugging Face with PyTorch
