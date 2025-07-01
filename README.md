# TypeMind – The Emotion-Aware Typing Assistant

TypeMind is a real-time emotion detection system that analyzes both your typed text and typing behavior to predict your emotional state (like Stress, Anxiety, Calm, or Happiness). It then suggests music, motivational quotes, or break tips accordingly.

> Built solo in 1 month using Python + ML + Streamlit – designed as a resume-boosting project.

---

## Features

- Text-based emotion classification using ML (TF-IDF + Logistic Regression)
- Typing behavior analysis: speed, pauses, backspaces
- Combined decision logic for accurate emotional insights
- Real-time suggestions: music links, quotes, break tips
- Streamlit-based interactive UI

---

## Project Structure
TypeMind/
├── app/
│ ├── main.py # Streamlit UI
│ └── emotion_model.py # Text emotion classifier
├── data/
│ └── emotion_dataset.csv # Training data
├── models/
│ └── emotion_clf.pkl # Saved model
├── utils/
│ └── typing_tracker.py # Typing behavior tracker
├── resources/
│ └── music_links.json # Suggestions database
├── README.md
├── requirements.txt
└── demo.gif

Author

Jayadeep Kothapalli
University of Kentucky – B.S. Computer Science
