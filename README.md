# Hand Gesture-to-Speech Conversion System
This project detects hand gestures using a webcam and converts them into speech. It is useful for applications like sign language interpretation, interactive systems, and accessibility tools.

## Features

Detects hand gestures in real-time.

Recognizes gestures like: okay, thank you, Yes, No, call me, stop, Love you, live long, fist, end.

Converts recognized gestures into spoken words.

Shows the live video feed with hand landmarks and gesture names.

Stops automatically when the "stop" gesture is shown.

Cleans up temporary audio files automatically.

## How It Works

The webcam captures video frames.

MediaPipe detects hand landmarks (21 points on the hand).

A trained model predicts the gesture based on these landmarks.

The gesture is converted to speech using Google Text-to-Speech (gTTS).

## Requirements

Python 3

OpenCV

MediaPipe

TensorFlow/Keras

NumPy

gTTS

Pygame (optional for audio playback)

## How to Use

Open the project folder.

Make sure the temp folder exists for audio files.

Run the main script (main.py).

Show gestures in front of the webcam.

The program will display the gesture name and generate audio.

Show the "stop" gesture or press q to exit.
The gesture name is displayed on the video feed.

Showing the "stop" gesture ends the program.
