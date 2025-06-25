# SIBI Hand Gesture Classifier

This project aims to recognize and classify SIBI (Indonesian Sign Language) hand gestures in real time using a Deep Neural Network and MediaPipe.
The model was trained using ~12,800 hand gesture images, providing more than 510 labeled samples for each alphabet letter to ensure high accuracy.

## Project Goals
This project aims to recognize Indonesian Sign Language (SIBI) hand gestures in real-time using a webcam and classify them into alphabet letters to support inclusive communication.

## Project Structure
```
├── assets/            # Demo image/GIF files
├── Drive.txt          # Notes
    ├── requirements.txt   # Dependencies
    ├── app.py             # Main program
└── README.md          # Project documentation
```

## Features
- Real-time hand gesture detection
- Alphabet classification (A-Z)
- Uses webcam input
- Built using MediaPipe and Deep Neural Network (DNN)

## How to run
1. Install requirements: `pip install -r requirements.txt`
2. Run the app: `python app.py`

## Demo Klasifikasi SIBI
![Demo Klasifikasi SIBI](assets/demo.gif)
