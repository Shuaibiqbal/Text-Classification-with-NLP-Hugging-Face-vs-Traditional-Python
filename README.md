# Text-Classification-with-NLP-Hugging-Face-vs-Traditional-Python
A beginner-friendly repository demonstrating text classification using Hugging Face transformers (manual and pipeline methods) alongside a traditional machine learning approach (TF-IDF + Logistic Regression). Includes clean, well-commented Python code and real-world applications like sentiment analysis and news categorization.

This repository demonstrates how to perform text classification using:

- **Hugging Face Transformers** (manual model loading + pipeline API)
- **Traditional Machine Learning** (TF-IDF + Logistic Regression)

The goal is to classify text data into categories with simple, clean Python code, explained step-by-step.

## Dataset
We use the 20 Newsgroups dataset (subset of categories) for the traditional method,
and the SST-2 sentiment analysis model for Hugging Face examples.

## Why Hugging Face?
Hugging Face transformers provide state-of-the-art NLP models with pretrained weights,
making it easy to leverage deep learning for text tasks without training from scratch.

## Why Traditional ML?
Traditional methods like TF-IDF + Logistic Regression are lightweight, fast, and good baselines.

---

## How to run

1. Install dependencies:

```bash
pip install transformers datasets scikit-learn
