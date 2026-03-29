# AI-Powered CCTV Attendance & Analytics System

## Overview
This project is an automated identity-logging system that identifies individuals from live video feeds (Webcam/CCTV) and logs their presence into a structured database. It features real-time face encoding, voice confirmations, and duplicate entry prevention.

## Key Features
- **Real-Time Detection:** Uses HOG-based face detection and 128-d face encodings for high-accuracy matching.
- **Voice Feedback:** Integrated `pyttsx3` for instant audio confirmation of recognized users.
- **Data Logging:** Automatically exports name and timestamps to a CSV file for record-keeping.
- **Future Integration:** Scaling to YOLOv8 for improved performance in low-light CCTV environments.

## Tech Stack
- Python, OpenCV, Face-Recognition Library, Scikit-learn, Pandas.
