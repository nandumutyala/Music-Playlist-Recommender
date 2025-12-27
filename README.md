# 🎵 Music Playlist Recommendation System using Machine Learning

## 📌 Overview
This project implements a music playlist recommendation system that suggests songs to users based on learned patterns from historical data.  
It uses **machine learning techniques** to identify similarities between songs and generate personalized recommendations.

---

## 🎯 Problem Statement
With the vast number of songs available on music platforms, users often struggle to discover relevant music.  
This project aims to build a recommendation system that can **automatically suggest songs** based on similarity and user preferences.

---

## 🚀 Features
- Data preprocessing and analysis of music dataset
- Similarity-based music recommendation
- Playlist generation based on learned patterns
- End-to-end implementation in a Jupyter Notebook

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **ML Approach:** Collaborative Filtering / Content-Based Filtering  
- **Similarity Metric:** Cosine Similarity  
- **Environment:** Jupyter Notebook  

---

## 🧠 How It Works
1. Load the music dataset (`dataset.csv`).
2. Clean and preprocess the data.
3. Convert song features into numerical representations.
4. Compute similarity between songs using cosine similarity.
5. Recommend songs similar to a given input song or playlist.
6. Generate a playlist based on similarity scores.

---

## 📂 Project Structure
music-playlist-recommendation/
├──README.md
├── dataset.csv
├── Music recommendation system code.ipynb


📌 Dataset Description
File: dataset.csv
Contains song-related attributes used for recommendation.
Used to compute similarity and generate recommendations.


📊 Output
The system recommends a list of songs similar to the input song.
Output is displayed directly in the notebook as a generated playlist.

Sample Output:
Input Song: "Shape of You"
Recommended Songs:
- Perfect
- Thinking Out Loud
- Castle on the Hill
