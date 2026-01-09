# Portfolio

This repository presents selected projects in applied AI, computer vision, and research-oriented systems. 
The focus is on problem formulation, system design, and scalable ML pipelines.

---

## Projects

### Video Retrieval via Keyframe Extraction (Research)
Academic research project on classroom video analysis using computer vision and deep learning.

**Status:** Implemented and evaluated

- Designed a two-stage pipeline for video summarization via keyframe extraction.
- Implemented a CNN-based classifier to analyze activity levels in classroom recordings.
- Reduced video processing complexity while preserving relevant behavioral information.

Technologies: Python, Computer Vision, Deep Learning, CNNs

---

### Autonomous Navigation and Object Collection using Puzzlebot
Systems and robotics project focused on autonomous navigation and object manipulation.

**Status:** Implemented and tested

- Developed embedded software for a gripper control system on an STM32 microcontroller.
- Designed real-time tasks using FreeRTOS to enable communication with a Jetson Nano.
- Integrated computer vision–based object detection with navigation and manipulation logic.
- Built a distributed system bridging perception (Jetson Nano) and control (microcontroller).

Technologies: C++, Python, FreeRTOS, Computer Vision, Embedded Systems, Jetson Nano

---

### STM32-Based Robotic Gripper Control System
Embedded systems project focused on real-time control of a two-degree-of-freedom robotic gripper.

**Status:** Implemented and tested

- Developed low-level control software for a robotic gripper using an STM32F411 microcontroller (ARM Cortex-M4).
- Designed a real-time task architecture with FreeRTOS to manage motion control, safety checks, and state monitoring.
- Implemented closed-loop motor control using ADC feedback and PWM-based actuation.
- Enabled bidirectional communication with a Jetson Nano via USART and ROSserial for command execution and status reporting.
- Integrated fault detection and emergency stop logic to ensure safe operation.

Technologies: C/C++, STM32, FreeRTOS, Embedded Systems, ROSserial, Real-Time Control
