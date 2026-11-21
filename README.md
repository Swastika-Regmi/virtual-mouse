# AI Virtual Mouse Using Python

## Overview

AI Virtual Mouse is a computer vision-based project that explores controlling a computer mouse through hand gestures using a webcam.

The project uses Python, OpenCV, and hand tracking techniques to demonstrate an alternative approach to human-computer interaction.

## Features

- Real-time hand tracking.
- Hand landmark detection.
- Gesture-based mouse movement.
- Mouse clicking using hand gestures.
- Webcam-based interaction.
- Simple graphical user interface.

## Technologies Used

- **Python** – Core programming language.
- **OpenCV** – Image processing and webcam access.
- **MediaPipe** – Hand landmark detection.
- **NumPy** – Numerical operations.
- **AutoPy** – Mouse control.
- **Tkinter** – Graphical user interface.

## Project Structure

```text
virtual-mouse/
│
├── AiVirtualMouseProject.py
├── HandTrackingModule.py
├── gui.py
└── README.md
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Swastika-Regmi/virtual-mouse.git
```

### 2. Navigate to the Project Directory

```bash
cd virtual-mouse
```

### 3. Create a Virtual Environment

```bash
python3 -m venv .venv
```

### 4. Activate the Virtual Environment

```bash
source .venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install opencv-python mediapipe numpy autopy
```

## How to Run

To launch the graphical user interface:

```bash
python3 gui.py
```

You can also run the main application directly:

```bash
python3 AiVirtualMouseProject.py
```

Make sure your webcam is connected and accessible.

 Project Objectives

- Explore computer vision and hand tracking.
- Understand gesture-based computer interaction.
- Develop practical Python programming skills.
- Explore alternative human-computer interaction methods.

 Future Improvements

- Improve hand tracking accuracy.
- Add additional gesture controls.
- Improve cursor movement and sensitivity.
- Enhance the graphical user interface.
- Improve error handling and performance.

 Author

Swastika Regmi

GitHub: [Swastika-Regmi](https://github.com/Swastika-Regmi)

Project Status

Currently under development. New features, improvements, and documentation will be added as the project progresses.

 Licensing and Source Notice

This repository is based on an existing implementation. Original-source licensing and redistribution permissions must be verified before further public distribution. Any applicable attribution and licence requirements will be respected.

