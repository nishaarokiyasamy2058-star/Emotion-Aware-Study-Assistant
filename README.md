# Emotion-Aware Study Assistant

## Overview
This project detects the user's emotion from text and provides personalized study recommendations using **Machine Learning (Naive Bayes + TF-IDF)**.  
It is designed for **students and learners** to help improve focus and study efficiency based on their current emotional state.

---

## Features
- Detects 6 emotions: **joy, sadness, anger, fear, love, surprise**  
- Text preprocessing using **TF-IDF vectorization**  
- **Naive Bayes classifier** for emotion prediction  
- Provides **study recommendations** based on detected emotion  
- Optionally saves trained model and vectorizer for reuse  

---

## Dataset
- **Source:** [Emotions Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)  
- **Format:** Text file with `text;emotion` per line  
- Files included:
  - `train.txt`  
  - `test.txt`  
  - `val.txt`  

**Note:** Dataset is downloaded via Kaggle API in the notebook. Do **not upload Kaggle API keys** to GitHub.

---

## How to Run
1. Clone the repository:

```bash
git clone https://github.com/YourUsername/Emotion-Aware-Study-Assistant.git

