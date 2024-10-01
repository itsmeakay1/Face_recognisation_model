# Face Recognition Project

This repository contains a face recognition project implemented using Python, OpenCV, and machine learning techniques. The project includes training a face recognizer using the LBPH (Local Binary Patterns Histograms) algorithm and detecting faces in real-time from a video stream.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [File Structure](#file-structure)
- [License](#license)

## Project Overview

The project performs real-time face detection and recognition using OpenCV. It collects face samples, trains a classifier, and uses the trained model to recognize faces in a video stream.

The system uses:
- **Haar Cascade Classifiers** for face detection.
- **LBPH** (Local Binary Patterns Histograms) for face recognition.
- A dataset of face images collected from the webcam, stored in a directory and labeled with IDs.
- The system matches detected faces with the trained dataset and displays the name or ID of the recognized person.

## Features

1. **Face Detection**: Detects faces using Haar cascades.
2. **Face Recognition**: Recognizes faces based on trained LBPH model.
3. **Sample Collection**: Captures 100 face samples per person from the webcam for training.
4. **Real-time Video Processing**: Continuously processes video input from the webcam and displays the recognized faces.

## Installation

To run this project, you'll need Python and the required dependencies installed. You can install the dependencies using `pip`.

### Steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/username/face-recognition.git
   cd face-recognition

### Explanation:
1. **Installation**: Guides users through cloning the repo, installing dependencies, and downloading the necessary Haar Cascade XML file.
2. **Usage**: Walks through collecting face samples, training the classifier, and running real-time face recognition.
3. **Dependencies**: Lists required libraries, such as OpenCV, NumPy, and Pillow.
4. **File Structure**: Explains the purpose of each file in the project.
  
You can create `requirements.txt` by listing the dependencies, like this:

### `requirements.txt`:
```txt
opencv-python
opencv-contrib-python
numpy
pillow
