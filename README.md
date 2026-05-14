# **Automated Video Acquisition System**

## **Overview**

This project presents the development of an Automated Video Acquisition System using a linear positioning mechanism integrated with image acquisition and mechatronics-based control architecture. The system is designed to automatically capture video footage of a target object while moving along a controlled linear axis using a lead screw mechanism. 

The project combines:

* Mechanical systems
* Embedded control
* Machine vision
* Automation
* Mechatronics integration

The system uses:

* Stepper motor driven lead screw
* Industrial camera
* DAQ-based control
* Limit switch feedback
* Python-based acquisition system
* OpenCV and NumPy libraries

---
## Project Images 

# Images of the Structural parts
<img width="597" height="205" alt="image" src="https://github.com/user-attachments/assets/51e8ea69-f9d2-4931-a158-4ff1a92c9f64" />


# Image of the Mechanical parts 
<img width="646" height="342" alt="image" src="https://github.com/user-attachments/assets/ff8b982d-5bdd-4b13-850e-168ed0f01e32" />


# **Objectives**

The primary objective of the project is to:

* Automatically acquire video footage of a target object
* Synchronize camera recording with the linear positioning mechanism
* Implement home positioning using limit switches
* Create an integrated mechatronics solution for automated video acquisition

The mechanism first moves to the home position, after which the camera begins recording while the linear system moves downward automatically. 

---

# **Mechatronics Perspective**

This project integrates:

* Mechanical components
* Electrical systems
* Electronics
* Software
* Automation logic

The system demonstrates a complete mechatronics workflow where software commands control the mechanical motion of the lead screw mechanism while synchronizing image acquisition from the industrial camera. 

---

## Electrical Circuit Diagram 

<img width="847" height="536" alt="image" src="https://github.com/user-attachments/assets/fffa7383-cefd-4bd2-b278-4743f9bd710a" />


# **Hardware Components**

## **Mechanical Components**

* Lead screw mechanism
* Supporting rods
* Coupler
* Camera mounting system
* Structural support frame

The lead screw mechanism enables smooth and accurate linear motion of the camera assembly. 

---

## **Electrical Components**

* 12V Stepper Motor
* Power supply system
* Motor driver
* DAQ interface

The stepper motor drives the lead screw system to move the industrial camera vertically. 

---

## **Electronic Components**

* L298 Motor Driver
* Limit switches
* DAQ module
* HIK Vision Industrial Camera

The limit switches are used for:

* Home positioning
* Upper and lower travel limits
* Motion control feedback



---

# **System Architecture**

## **Hardware Block Diagram**

The system architecture consists of:

* Power supply
* Controller
* Stepper motor
* Camera
* Lead screw mechanism

The DAQ interface acts as the communication bridge between the controller and hardware components. 

---

# **Working Principle**

## **Functional Workflow**

1. System initializes
2. Mechanism moves to home position
3. Limit switch detects position
4. Stepper motor rotates clockwise/anticlockwise
5. Camera begins recording
6. Video acquisition continues during motion
7. Recording stops when upper limit switch is triggered

The project uses a closed-loop control system involving:

* Sensors
* Controller
* Actuator



---

# **Software & Programming**

## **Technologies Used**

* Python
* OpenCV
* NumPy
* HIK Vision MVS SDK
* NI-DAQmx

The software system controls:

* Motor movement
* Limit switch feedback
* Camera triggering
* Video recording

---

# **Key Features**

## **Automated Recording**

The system automatically starts recording based on the position feedback from the limit switches.

## **Linear Camera Motion**

The camera moves smoothly using a lead screw positioning mechanism.

## **Integrated DAQ Control**

DAQ hardware enables synchronized hardware communication.

## **Industrial Camera Support**

HIK Vision industrial camera integration using MVS software SDK. 

---

# **Computer Vision Integration**

The project integrates machine vision tools for automated video acquisition using:

* Industrial camera SDK
* Python APIs
* Frame grabbing
* Recording control

The MVS software SDK was integrated into the Python code for industrial camera communication and video recording. 

---

# **Performance Analysis**

The system successfully:

* Captures automated video footage
* Maintains synchronized motion control
* Performs stable linear movement
* Uses limit switch feedback for safety and positioning

One improvement identified during testing was replacing the L298 driver with a TB6600 driver for better motor performance. 

---

# **Future Scope**

Future improvements may include:

* Object detection integration
* Automated tracking
* Multi-axis motion systems
* 3D reconstruction
* AI-assisted industrial inspection
* Manufacturing automation

Potential applications include:

* Industrial inspection
* Manufacturing automation
* Robotics
* Surveillance systems
* Smart machine vision systems



---

# **Technologies & Tools**

| Category         | Tools/Components             |
| ---------------- | ---------------------------- |
| Programming      | Python                       |
| Vision Libraries | OpenCV, NumPy                |
| Camera SDK       | HIK Vision MVS               |
| Motion System    | Lead Screw Mechanism         |
| Controller       | DAQ                          |
| Motor Driver     | L298                         |
| Sensors          | Limit Switches               |
| Camera           | HIK Vision Industrial Camera |

---

# **Conclusion**

The project successfully demonstrates the integration of:

* Mechatronics
* Embedded systems
* Industrial automation
* Computer vision
* Linear motion control

The Automated Video Acquisition System provides a reliable platform for synchronized motion-based video capture and highlights the practical implementation of intelligent automation systems in industrial and robotics applications. 
