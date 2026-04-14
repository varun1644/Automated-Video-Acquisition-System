# 🎥 Automated Video Acquisition System

An automated mechatronics system designed to capture video of an object using a linear positioning mechanism. The system integrates mechanical, electrical, and software components to achieve precise motion and synchronized video recording.

---

## 🚀 Project Overview

This project uses a lead screw-based linear mechanism to move a camera vertically and capture video automatically when triggered by limit switches.

📌 Key Idea:
- Move camera using stepper motor
- Detect position using limit switches
- Automatically start/stop video recording

---

## ⚙️ System Architecture

- Controller: PC with Python
- Actuator: Stepper Motor
- Mechanism: Lead Screw Linear System
- Sensors: Limit Switches
- Vision: Industrial Camera (HIK Vision)

---

## 🧠 Working Principle

1. System starts at home position
2. Motor moves upward
3. On reaching top limit → reverses direction
4. Camera starts recording while moving downward
5. Stops recording at bottom limit

---

## 🔩 Hardware Components

- Stepper Motor (12V)
- L298 Motor Driver
- Lead Screw Mechanism
- Limit Switches
- DAQ (Data Acquisition System)
- Industrial Camera

---

## 💻 Software Used

- Python
- OpenCV
- NumPy
- MVS (Machine Vision Software)

---

## 🧾 Code Features

- Stepper motor control (CW & CCW)
- Limit switch signal reading
- Video acquisition integration
- DAQ communication

---

## 📊 Control System

Closed-loop system:
Sensor → Controller → Actuator

---

## 🔮 Future Improvements

- Object detection integration (YOLO)
- Automated defect detection
- 3D reconstruction using captured images
- Replace L298 with TB6600 driver

---

## 📸 Results

The system successfully captures video automatically based on position using a linear mechanism.

---

## 📂 Project Structure

