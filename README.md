# 🎵 Spotify Lyric Search – Machine Learning Project

## 📌 Project Overview
This project builds a **text identification system** that predicts the **song title and artist** when given a small snippet of song lyrics.  
It uses Natural Language Processing (NLP) techniques and similarity-based retrieval.

---

## 🎯 Objective
Given a short lyric snippet, identify:
- Song name
- Artist name

---

## 🧠 Approach
1. Clean and preprocess lyrics text
2. Convert lyrics into numerical vectors using **TF-IDF**
3. Convert input lyric snippet into a vector
4. Compute **cosine similarity**
5. Return the most similar song (Top-1 prediction)

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## 📁 Project Files – Purpose

- data/spotify_lyrics.csv

  => Contains the lyrics dataset (artist, song, text).

- src/preprocess.py

  => Cleans and normalizes lyrics text.

- src/vectorizer.py

  => Converts lyrics into TF-IDF vectors.

- src/search.py

  => Finds the best-matching song using cosine similarity.

- notebook/lyric_search.ipynb

  => Runs the full pipeline and evaluates accuracy.

  
  ## ▶️ How to Run
  Open: ```notebook/lyric_search.ipynb ```
  #### Run all cells sequentially.
  

