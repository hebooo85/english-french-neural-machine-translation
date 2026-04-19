# 🔤 English-to-French Neural Machine Translation

> 📚 INFO-6153: Natural Language Processing | Fanshawe College

## Overview
English-to-French neural machine translation comparing a custom 
LSTM Seq2Seq model vs Helsinki-NLP pretrained MarianMT Transformer.

## 📊 Results

| Model | BLEU Score |
|-------|-----------|
| LSTM Seq2Seq (from scratch) | 1.08 |
| Helsinki-NLP/opus-mt-en-fr | **16.09** |

## 🔬 Models
- **LSTM Seq2Seq** — Custom Encoder-Decoder built from scratch
- **Helsinki-NLP MarianMT** — Pretrained Transformer (zero-shot)

## 📦 Dataset
- opus_books (Hugging Face) — 127,085 English-French pairs
- Training: 40,000 pairs | Val: 5,000 | Test: 5,000

## 🛠️ Tech Stack
Python • TensorFlow/Keras • HuggingFace Transformers • SacreBLEU • Google Colab (T4 GPU)

## 🚀 Getting Started
Open notebook in Google Colab and switch to T4 GPU:
`Runtime → Change runtime type → T4 GPU`
