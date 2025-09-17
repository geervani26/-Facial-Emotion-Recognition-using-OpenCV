# -Facial-Emotion-Recognition-using-OpenCV
This project demonstrates real-time facial emotion recognition using Python, OpenCV, and the facial_emotion_recognition library. The system captures live video from your webcam, detects faces, and classifies emotions such as happy, sad, angry, surprised, neutral, and more.
# Features
* Uses the facial_emotion_recognition library for emotion detection.
* Captures real-time video from the webcam.
* Detects human faces and overlays predicted emotions on the video feed.
* Runs on CPU by default (can be configured for GPU if supported).
* Press ESC (27) to exit the application.
# Requirements
* Python 3.x
# Install dependencies:
* pip install opencv-python facial-emotion-recognition
# Usage
* Clone the repository and navigate to the project folder.
# Run the script:
* python emotion_recognition.py

* The webcam will open, and detected faces will be annotated with their emotions.
* Press ESC (27) to quit the program.
# Output Preview
* Opens webcam feed.
* Displays bounding boxes with emotion labels above faces in real-time.
# Example Emotions Detected
* Happy
* Sad
* Angry
* Surprised
* Neutral
* Fearful / Disgust (depending on model support)
