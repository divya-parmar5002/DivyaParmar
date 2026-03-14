# DivyaParmar
![MasterHead](https://user-images.githubusercontent.com/90236635/232446433-d5540fa2-fe28-4bb8-b929-cdb51fe61336.gif)
<h1 align="center">Hi 👋,I'm Divya Parmar</h1>
<h3 align="center">A passionate Data Scientist from India</h3>
<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/236119160-976a0405-caa7-470c-9356-16d43402ea0a.gif"
- 🔭 I’m currently working on **video conferencing app**

- 🌱 I’m currently learning **Basic to Advanced concept of Machine learning and Data science **

- 📫 How to reach me **divyaparmar8046@gmail.com**

  AI-Powered Emotion Detection and Task Optimization System
Overview

This project implements an AI-powered system for detecting human emotions from textual data. It uses Natural Language Processing (NLP) techniques and machine learning to classify emotions such as anger, fear, joy, love, sadness, and surprise. The system also lays the foundation for task optimization based on emotional states, making it useful for productivity enhancement and emotional well-being monitoring.

Features

Preprocesses raw text (cleaning, lowercasing, stopword removal)

Converts text into numerical features using TF-IDF vectorization

Supports multiple machine learning models:

Logistic Regression

Multinomial Naive Bayes

Support Vector Machine (SVM)

Evaluates models using accuracy, precision, recall, F1-score, and confusion matrix

Compares models to select the best-performing one

Predicts emotions for new text input

Saves trained models, TF-IDF vectorizer, and label encoder for deployment

Dataset

The project uses the Emotion Dataset for NLP, which contains labeled short text samples for six emotions:

anger

fear

joy

love

sadness

surprise

The dataset is provided in three files: train.txt, test.txt, val.txt. Each record has the format:

text ; emotion

Example:

i feel very angry today ; anger
i am extremely happy ; joy
i didnt feel humiliated ; sadness
Project Structure
AI-Emotion-Detection/
│
├─ train.txt               # Training dataset
├─ test.txt                # Test dataset
├─ val.txt                 # Validation dataset
├─ emotion_merged.csv      # Merged dataset
├─ main.ipynb              # Complete Jupyter/Colab notebook
├─ emotion_model.pkl       # Saved trained model
├─ tfidf_vectorizer.pkl    # Saved TF-IDF vectorizer
├─ label_encoder.pkl       # Saved label encoder
└─ README.md               # Project description
Installation

Clone the repository:

git clone https://github.com/yourusername/AI-Emotion-Detection.git
cd AI-Emotion-Detection

Install required Python packages:

pip install pandas numpy scikit-learn seaborn matplotlib joblib

Ensure train.txt, test.txt, and val.txt are present in the project folder.

Usage

Open main.ipynb in Jupyter Notebook or Google Colab.

Run all cells sequentially to:

Load and preprocess the dataset

Train models

Evaluate and compare models

Predict emotions for new text input

Use the predict_emotion function for custom text:

sample_text = "I am so excited for today!"
predicted_emotion = predict_emotion(sample_text)
print(predicted_emotion)  # Example Output: joy

The trained model, TF-IDF vectorizer, and label encoder are saved for deployment:

joblib.load('emotion_model.pkl')
joblib.load('tfidf_vectorizer.pkl')
joblib.load('label_encoder.pkl')
Evaluation

The project evaluates models using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Sample model comparison:

Model	Accuracy
Logistic Regression	0.86
Multinomial NB	0.84
SVM	0.85

Accuracy may vary depending on dataset preprocessing and train-test split.

Future Scope

Real-time emotion detection in chat or messaging apps

Use Deep Learning models (LSTM, BERT) for improved accuracy

Integrate task recommendation system based on detected emotions

Deploy as a web or mobile application for productivity tools

References

Emotion Dataset for NLP – Kaggle

Scikit-learn Documentation – TF-IDF, Label Encoding, Classifiers

Python Regular Expressions – re module

License

This project is open-source and free to use for educational purposes.


