# Disaster Tweet Classification (Week 4 NLP Project - 5511)

This repository contains the files and deliverables for the Week 4 mini-project from the "Natural Language Processing" module (DTSA 5511) in the MSDS program at CU Boulder. The project involved building a model to classify tweets as related to real disasters or not.

## 🔍 Problem Description
The goal was to apply natural language processing techniques to classify tweets as disaster-related (label `1`) or not (label `0`). The challenge was based on a real Kaggle competition: [NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started).

## 📁 Repository Contents

| File Name             | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `week4-nlp.ipynb`     | The full Jupyter Notebook with data cleaning, EDA, model development, results, and analysis. |
| `week4-nlp.pdf`       | Exported PDF version of the notebook for submission.                        |
| `submission (1).csv`  | Final CSV file submitted to Kaggle containing predictions on the test set.  |
| `5511-week4.png`      | Screenshot of the Kaggle leaderboard showing the public score and rank.     |

## 📊 Techniques Used
- Text preprocessing (lowercasing, punctuation removal, stopword filtering)
- Tokenization and padding
- Trainable word embeddings (Keras `Embedding` layer)
- Bidirectional LSTM architecture
- Model tuning with early stopping and validation loss monitoring
- Evaluation using Kaggle leaderboard (public score: **0.74256**)

## ✅ Deliverables
- ✔️ Code notebook and report
- ✔️ Kaggle submission
- ✔️ Leaderboard screenshot
- ✔️ GitHub repo with all files

## 📌 Author
Chitralekha Gopalaiah  
MSDS @ University of Colorado Boulder

