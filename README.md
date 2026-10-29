# Repository for final project

## Emotion Detection Application using Watson NLP

An AI-based web application that detects emotions in a piece of text. It uses the
**Watson NLP Emotion Predict** service and is deployed with **Flask**.

For any text, the application returns scores for **anger, disgust, fear, joy and sadness**,
along with the **dominant emotion**.

## Project Structure

```
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
└── test_emotion_detection.py
```

## Running the application

```bash
python3.11 server.py
```

Open `http://localhost:5000` and enter the text to analyze.

## Running the unit tests

```bash
python3.11 test_emotion_detection.py
```
