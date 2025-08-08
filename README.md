# Capstone-Project--Shabdub
Stockton University
Inspired by NYT Wordle, this project was developed as part of a graduate capstone in Data Science & Strategic Analytics. Special thanks to professors and peers for feedback and support.
# ShabDub🧠

*ShabDub* is a multilingual, Wordle-inspired web app that helps adult learners and heritage speakers of Hindi, Gujarati, and English strengthen vocabulary and connect with their language and culture through daily gameplay. It was designed as both a game-based learning tool and a family bonding activity, with AI-driven adaptive difficulty and real-time feedback.

## What does "ShabDub" mean?

The name "ShabDub" is a playful blend of the Hindi word **"Shabd"** (शब्द), meaning "word", and **"Dub"**, echoing both the English idea of "dubbing" (language substitution) and a fun, catchy game title.

---

## Features

- 🌐 **Multilingual Support**: Play in **English**, **Hindi**, or **Gujarati**
- 🧠 **Adaptive Difficulty**: AI adjusts word difficulty based on performance
- 🗣️ **Real-Time Chatbot**: Encouragement and hints in your chosen language
- 🎯 **Grapheme-Based Word Levels**:
  - Beginner: 3–5 letters
  - Intermediate: 6–7 letters
  - Hard: 8–9 letters
  - Guru: 10+ letters
- ⏱️ **Timer + Performance Tracking**: Gamified experience to encourage focus
- 📈 **ML Integration**: Decision Tree & KMeans clustering for user analysis
- 📊 **User Feedback Loop**: Difficulty auto-adjusts after poor or strong performance

---

## Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io)
- **Backend**: Python (Jupyter Notebook)
- **ML Models**: 
  - `DecisionTreeClassifier` (from `sklearn.tree`)
  - `KMeans` (from `sklearn.cluster`)
- **Data Handling**: Pandas
- **Grapheme Counting**: `grapheme` Python package

---

## Development Highlights

- Used Kaggle datasets for Hindi, Gujarati, and English words.
- Cleaned and categorized words using grapheme counts.
- Implemented logic to dynamically assign difficulty levels using:
  ```python

