# SIBI Hand Gesture Classifier

This project classifies Indonesian sign language (SIBI) hand gestures using DNN and MediaPipe.

## Project Goals
This project aims to recognize Indonesian Sign Language (SIBI) hand gestures in real-time using a webcam and classify them into alphabet letters to support inclusive communication.

## Project Structure
├── assets/             # Demo image/GIF files
├── Drive.txt           # Notes
    ├── requirements.txt    # Dependencies
    ├── app.py              # Main program
└── README.md           # Project documentation

## Features
- Real-time hand gesture detection
- Alphabet classification (A-Z)
- Uses webcam input
- Built using MediaPipe and Deep Neural Network (DNN)

## How to run
1. Install requirements: `pip install -r requirements.txt`
2. Run the app: `python app.py`

This model was created using approximately 12,800 hand image datasets, with more than 510 for each letter.
![Demo Klasifikasi SIBI](assets/demo.gif)
