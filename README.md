# Automated Parking Gate System with License Plate OCR

Automated access control system that combines Computer Vision in MATLAB for license plate Optical Character Recognition (OCR) with an ESP32 micro-controller driving a servo motor for barrier gate operation.

## 🚀 Key Features
- **License Plate OCR:** Image processing and character recognition executed in MATLAB.
- **Hardware Integration:** Real-time serial communication with ESP32.
- **Actuation:** Servo-controlled parking barrier gate.

## 🛠️ Built With
- **Software:** MATLAB (Image Processing & Computer Vision Toolboxes)
- **Hardware:** ESP32, Servo Motor, Camera
- **Communication:** Serial Cable / USB

## 📹 System Demo
*(Here you can attach a short GIF or video showing the MATLAB script processing a plate and the ESP32 opening the barrier)*

## 📂 Repository Structure
- `/matlab`: Scripts for image acquisition, preprocessing, and OCR algorithm.
- `/esp32`: C++ firmware for reading commands over serial and driving the servo.
