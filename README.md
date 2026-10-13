# Video Emotion Recognition UI 🎭

A responsive web application for video-based emotion recognition using deep learning.

## Features
- Upload and preview video files (`.mp4`, `.webm`)
- Display video metadata
- Check backend connectivity
- Predict emotions when the model is connected
- Display seven emotion classes
- Responsive user interface

## Technologies
- React.js
- CSS
- Lucide React
- FastAPI
- CNN-BiLSTM with Attention
- MELD Dataset

## Installation

```bash
git clone https://github.com/SRIMATHI-T/Video_emotion_UI.git
cd Video_emotion_UI
npm install
npm start
```

## Workflow

Video Input → Frame Extraction → Face Detection → CNN → BiLSTM + Attention → Emotion Prediction

## Backend

Configure `REACT_APP_BACKEND_URL` with your backend URL to enable emotion analysis.

## Repository

https://github.com/SRIMATHI-T/Video_emotion_UI
