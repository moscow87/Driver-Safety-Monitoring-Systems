# 🚗 Driver Safety & Monitoring Systems

## 🔥 Overview
This repository contains an integrated set of projects aimed at creating an intelligent Driver Monitoring System (DMS).  
It includes:
- Driver drowsiness detection
- Driver behavior analysis
- Phone and cigarette usage detection
- Python-Arduino integration for real-time alerts

The main project in this repository is **Driver-Guard**, which simulates a drowsiness detection device and monitors driver behavior during driving, sending alerts when dangerous conditions are detected.

---

## 📁 Repository Structure


---

## 🧠 Included Projects

### ✅ 1) Driver-Guard (Main Project)
- Simulates a drowsiness detection device
- Monitors driver movement and alertness
- Sends visual and audible alerts via Arduino, LCD, and buzzer
- Built with Python, OpenCV, dlib, and YOLO

### ✅ 2) AI Driver Monitoring System
- Detects phone and cigarette usage while driving
- Monitors unsafe driving behaviors using YOLO

### ✅ 3) Real-Time Drowsiness Detection
- Detects drowsiness using Eye Aspect Ratio (EAR)
- Tracks eye and facial movements to determine driver state

### ✅ 4) Driver Behavior Detection using YOLO
- Monitors driver attention
- Detects head tilts, looking away, or distraction

### ✅ 5) Embedded Driver Safety System
- Hardware alerts: buzzer and LED
- Integrates sensors with Arduino for motor control

### ✅ 6) Fatigue Detection with Python ↔ Arduino
- Python-Arduino communication for sending/receiving alerts
- Real-time driver monitoring and alerts

---

## 🧩 How These Projects Come Together
| Component | Project |
|-----------|---------|
| Drowsiness Detection | Project 3 + Driver-Guard |
| Dangerous Behavior Detection | Project 2 + Project 4 |
| Object Detection (Phone/Cigarette) | Project 2 + Project 4 |
| Python-Arduino Integration | Project 6 + Driver-Guard |
| Hardware Alerts | Project 5 + Driver-Guard |

---

## 🛠️ Technologies Used
- Python (OpenCV, dlib, imutils)
- YOLO / Tiny YOLO
- Serial Communication
- Arduino (Embedded Systems)
- Real-Time Video Processing
- Facial Landmarks & EAR

---

## 📌 Usage
1. Open the main project folder **Driver-Guard**  
2. Run the Python scripts for each system (Drowsiness, Phone/Cigarette, Head Pose)  
3. Connect the Arduino to the project for alerts and motor control  
4. Monitor the live driver state
