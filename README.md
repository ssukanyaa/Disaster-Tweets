# 🌪️ Disaster Tweet Classifier using DeBERTa

This project fine-tunes [Microsoft's DeBERTa-v3-small](https://huggingface.co/microsoft/deberta-v3-small) transformer model to classify whether a tweet is about a real disaster or not.

## 📌 Project Overview

- ✅ Binary classification: disaster (`1`) or not (`0`)
- ✅ Hugging Face Transformers + Datasets + PyTorch
- ✅ Preprocessing with `text + keyword` combination
- ✅ Clean Text to reduce Noise.
- ✅ Supports class weighting to handle label imbalance

## 📁 Dataset
- Origin: [Kaggle NLP - Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/data)

## 📊 Results
- Achieved F1 score ~82.3% on the test set. 
