# Emotion-Aware Study Assistant
## Overview
This project detects the user's emotion from text and provides personalized study recommendations using **Machine Learning (Naive Bayes + TF-IDF)**.  
It is designed for **students and learners** to help improve focus and study efficiency based on their current emotional state.

## Features
- Detects 6 emotions: **joy, sadness, anger, fear, love, surprise**  
- Text preprocessing using **TF-IDF vectorization**  
- **Naive Bayes classifier** for emotion prediction  
- Provides **study recommendations** based on detected emotion  
- Optionally saves trained model and vectorizer for reuse  

## Dataset
- **Source:** [Emotions Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)  
- **Format:** Text file with `text;emotion` per line  
- Files included:
  - `train.txt`  
  - `test.txt`  
  - `val.txt`  

**Note:** Dataset is downloaded via Kaggle API in the notebook. Do **not upload Kaggle API keys** to GitHub.

## How to Run
1. Clone the repository:

```bash
git clone https://github.com/nishaarokiyasamy2058-star/Emotion-Aware-Study-Assistant.git
2. Open the notebook Emotion_Aware_Study_Assistant.ipynb in Google Colab.
3.If dataset is not present, the notebook will download it from Kaggle automatically.
4.Run all cells sequentially:
   *Download dataset
   *Load and preprocess data
   *Train model
*Test emotion detection and study recommendation
5.(Optional) Save the model and vectorizer for future use

**Example**
Input: "I am feeling very stressed about exams"
Detected Emotion: sadness
Study Advice: "Take a short break, then revise easy topics."

**Dependencies**

*Python 3.x
*Pandas
*Scikit-learn
*NumPy
*Pickle (optional, for saving model)

**Install missing packages in Colab:**
!pip install pandas scikit-learn numpy

**License**
Dataset License: **CC-BY-SA-4.0**
Project Code:** MIT License** (or choose your preferred open source license)

**Author**
NISHANTHINI A
CSE (AI & ML) Student

✅ **Instructions:**
1. Open your project folder  
2. Create a file `README.md`  
3. Paste this content  
4. Save and upload to GitHub 
