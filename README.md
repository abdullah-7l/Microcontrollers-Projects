# Hardware & Embedded Systems Lab 🔌🤖

## About This Repository
This repository contains a collection of scripts, circuits, and mini-projects focused on hardware programming and embedded systems. It serves as a practical workspace for interfacing software with physical components using various microcontrollers and single-board computers, building a solid foundation for future robotics and hardware-AI integration.

## Platforms & Technologies 🛠️
* **Arduino:** Microcontroller programming using C/C++ for real-time hardware control.
* **Raspberry Pi:** (Upcoming) Single-board computer projects using Python for advanced processing and IoT.
* **Actuators & Sensors:** Servo motors, DC motors, environmental sensors, and basic electronic components.

## Projects Catalog 📂

### 1. [4-Servo Sweep and Hold](./Arduino/4_Servo_Sweep_Hold)
* **Platform:** Arduino
* **Description:** A precise timing-based control script that commands 4 independent servo motors to perform a continuous sweep for exactly 2 seconds using `millis()`, before permanently halting and holding a 90-degree position. 
* **Concepts Covered:** PWM control, non-blocking delays, hardware time constraints.

---

## Repository Structure 🏗️
To keep things organized, projects are divided by platform:
* `/Arduino` - Contains all `.ino` sketches and circuit diagrams.
* `/Raspberry-Pi` - Contains Python scripts and related configurations.
* `/Docs` - Datasheets or reference materials for the components used.
