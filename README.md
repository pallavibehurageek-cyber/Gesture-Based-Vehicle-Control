# Gesture-Based Smart Car 🚗✋

A gesture-controlled robotic car that uses computer vision and embedded systems to control vehicle movement through hand gestures. The system detects hand movements using a webcam, processes them using Python, OpenCV, and MediaPipe, and sends control commands to an ESP32.

## 📌 Project Overview

This project demonstrates a contactless method of controlling a robotic vehicle using hand gestures.

A webcam captures the user's hand movements in real time. OpenCV processes the video stream, while MediaPipe detects hand landmarks and helps identify the intended gesture. The corresponding command is then sent to the ESP32, which controls the motors through an L298N motor driver.

## ✨ Features

- Real-time hand gesture detection
- Wireless control of a robotic car
- Computer-vision-based gesture recognition
- ESP32-based motor control
- Forward, backward, left, right, and stop movements
- Contactless vehicle operation
- Simple and intuitive human-machine interaction

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- ESP32
- Arduino IDE
- L298N Motor Driver
- Wireless communication

## 🔧 Hardware Components

- ESP32 Development Board
- L298N Motor Driver Module
- BO Motors
- Robot Car Chassis
- Wheels
- Battery Pack
- Jumper Wires
- Other basic assembly components

## 💻 Software Requirements

- Python 3.8 or later
- Arduino IDE
- ESP32 Board Package
- OpenCV
- MediaPipe

### Python Libraries

```bash
pip install opencv-python
pip install mediapipe

Working Principle

The system operates in the following sequence:

1. A webcam captures live video of the user's hand.

2. OpenCV processes the captured video.

3. MediaPipe detects the hand and its landmarks.

4. The detected hand gesture is converted into a movement command.

5. The command is transmitted to the ESP32.

6. The ESP32 controls the L298N motor driver.

7. The motor driver drives the motors according to the received command.

🎮 Gesture Controls

Gesture ➡️ Vehicle Movement

Forward ➡️ Moves Forward

Backward ➡️ Moves Backward

Left ➡️ Turns Left

Right ➡️ Turns Right

Neutral ➡️ Stops

🔃 System Flow

Webcam
   ↓
OpenCV
   ↓
MediaPipe Hand Detection
   ↓
Gesture Recognition
   ↓
Movement Command
   ↓
ESP32
   ↓
L298N Motor Driver
   ↓
DC Motors
   ↓
Vehicle Movement

📁 Project Structure

Gesture-Based-Smart-Car/
│
├── libraries/
│
├── media/
│   ├── Images
│   ├── Videos
│   └── Demonstrations
│
├── src/
│   ├── Gesture Recognition
│   └── ESP32 Control
│
└── README.md

🚀 Setup and Usage

1. Install Python

Install Python on your computer and make sure it is added to the system PATH.

2. Install Required Libraries

pip install opencv-python
pip install mediapipe

3. Configure the ESP32

Install Arduino IDE.

Install the ESP32 board package.

Connect the ESP32 to your computer.

Open the ESP32 control program.

Select the appropriate board and COM port.

Upload the program to the ESP32.


4. Run the Gesture Recognition Program

Run the Python program from the project directory:

python gesture_detection.py

The webcam will start detecting hand gestures and generating the corresponding vehicle commands.

📸 Project Media

Images, videos, circuit diagrams, and other demonstration materials are available in the media folder.

🎯 Applications

Educational robotics

Human-machine interaction

Embedded systems projects

Computer vision applications

Assistive robotic control

Wireless robotic vehicles


🔮 Future Enhancements

Add additional hand gestures

Improve gesture recognition accuracy

Add obstacle detection

Implement autonomous navigation

Improve wireless communication

Add a graphical user interface

Integrate additional sensors


📚 Key Concepts

This project combines concepts from:

Computer Vision

Hand Gesture Recognition

Embedded Systems

Wireless Communication

Robotics

Motor Control

Human-Machine Interaction


👩‍💻 Project Author

Pallavi Behura

B.Tech – Electronics and Communication Engineering
