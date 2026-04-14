# Automated Video Acquisition System

An automated mechatronics system designed to capture video of an object using a linear positioning mechanism. The system integrates mechanical, electrical, and software components to achieve precise motion and synchronized video recording.

---

## Project Overview

This project uses a lead screw-based linear mechanism to move a camera vertically and capture video automatically when triggered by limit switches.

Key Features:
- Automated camera movement using stepper motor
- Position detection using limit switches
- Automatic video recording based on position
- Modular and extensible architecture

---

## System Architecture

- Controller: PC running Python
- Actuator: Stepper Motor
- Mechanism: Lead Screw Linear System
- Sensors: Limit Switches
- Vision: Industrial Camera

---

## Working Principle

1. System starts at home position
2. Motor moves upward
3. On reaching top limit, direction reverses
4. Camera records while moving downward
5. Stops recording at bottom limit

---

## Hardware Components

- Stepper Motor (12V)
- Motor Driver (L298 / TB6600 recommended)
- Lead Screw Mechanism
- Limit Switches
- DAQ (Data Acquisition System)
- Industrial Camera

---

## Software Stack

- Python
- OpenCV
- NumPy
- MVS (Machine Vision Software)

---

## Project Structure
