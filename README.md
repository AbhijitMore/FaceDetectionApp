# Face Detection Web App 🕵️‍♂️📹

## Overview

This Flask-based web application performs real-time face detection using OpenCV. The app captures video from your webcam, processes each frame to detect faces, and streams the video feed to the web interface. The face detection utilizes a Haar Cascade classifier for identifying faces within the video stream.

## Features ✨

- **Real-time Face Detection:** Detect faces in real-time using Haar Cascades.
- **Live Video Streaming:** Stream the video feed to the web browser with Flask.
- **Web Interface:** Simple and intuitive web interface to display the video feed.

## Directory Structure 🗂️

```plaintext
.
├── __pycache__/
├── static/
│   └── styles/
│       └── mainpage.css
├── templates/
│   └── index.html
├── app.py
├── camera.py
└── haarcascade_frontalface_default.xml
```

## Contributing 🤝

Feel free to submit issues or pull requests. Your contributions are welcome!

