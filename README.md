# Car-Detecting-Project
# YOLOv8 Car Detection with GUI

## Overview
This project is a simple application that uses the YOLOv8 object detection model to detect cars in video files. The user selects a video, and the system displays the video with real-time car detection. The app includes a graphical user interface (GUI) built using Tkinter.

## Features
- Detect cars in video files using the YOLOv8 model.
- Visual feedback with bounding boxes and confidence scores.
- User-friendly GUI for video selection and viewing.

## System Requirements
To run the project, you need:

- Python 3.8 or later  
- Basic internet connection (for first-time model loading)
- Works on Windows, macOS, and Linux

## Required Libraries
This project uses the following Python libraries:

- `ultralytics`
- `opencv-python`
- `Pillow`
- `tkinter`
🔧 How It Works
This application uses artificial intelligence to automatically detect cars in a video. It provides a simple graphical interface that anyone can use, even without programming knowledge.

When you open the program, a window appears with a button.

You click the “Browse Video” button to choose a video file from your device.

The program then plays the video and draws green boxes around any cars it finds.

It’s fast, fully automatic, and easy to use.

🖼 Visual Documentation
1. Graphical User Interface (GUI)
The interface includes:

A title at the top of the window

A short instruction telling you what to do

A green button that opens a file picker to choose your video


2. Car Detection Preview
A sample frame from a video will show how the application highlights detected cars by drawing labeled green rectangles around them.
