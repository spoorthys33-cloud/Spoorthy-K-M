 Facial Recognition System

 What it Does
This is a Python application that uses a camera to recognize people. It detects a human face, analyzes its unique features, and matches it against a database to verify a user's identity.

Tech Stack
* *Language:* Python
* *Computer Vision:* OpenCV
* *Face Matching:* face_recognition library
* *Database:* MySQL / SQLite

How it Works
1. *Camera Input:* The system opens your webcam or reads an image.
2. *Face Detection:* It finds where the face is located in the frame.
3. *Feature Mapping:* It measures the distances between facial features like eyes, nose, and jaw.
4. *Matching:* It compares those measurements with the database to find a match.
