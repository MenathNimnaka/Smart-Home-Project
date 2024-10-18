# Smart Home System for Safety and Automation

Welcome to the **Smart Home System** project repository, developed as part of the *Electrical Measurements and Instrumentation* module in Semester 04 at the University of Moratuwa. This system offers an advanced solution for home automation and safety monitoring by combining real-time control and sensor integration via LabVIEW and NI DAQmx.

## Overview

This project focuses on automating key home functions, such as fire detection, motion sensing, gas monitoring, and weather-based roof control. By leveraging an interactive LabVIEW interface, users can monitor and control these systems seamlessly.

## Core Features

### 1. Fire Hazard Detection
- **Temperature Monitoring**: The system continuously measures temperature using an NTC thermistor connected through a Wheatstone bridge.
- **Alert Mechanism**: If the temperature exceeds a certain limit, a buzzer is triggered, indicating a potential fire.

### 2. Motion Detection and Lighting
- **PIR Sensor**: Detects any motion in the room and activates an LED strip to visually indicate movement.

### 3. Gas Leak Detection
- **MQ2 Gas Sensor**: Monitors the environment for the presence of harmful gases (e.g., smoke or flammable gas) and sounds a buzzer alarm when dangerous levels are detected.

### 4. Automatic Roof Closure
- **Rain Detection**: Uses a raindrop sensor to detect rainfall. When rain is detected, an SG90 micro servo motor is activated to automatically close the roof, ensuring the home remains protected.

### 5. Real-Time Data Monitoring and Control
- **LabVIEW Front Panel**: The system is equipped with an intuitive graphical interface developed in LabVIEW, allowing real-time data visualization from all sensors and control of the system.

## Technology Stack

- **LabVIEW**: Real-time control and monitoring interface.
- **NI DAQmx**: Data acquisition and system integration.
- **Sensors**:
  - *NTC Thermistor* for temperature sensing.
  - *PIR Sensor* for motion detection.
  - *MQ2 Sensor* for gas detection.
  - *Raindrops Module* for weather sensing.
- **Actuators**:
  - *SG90 Micro Servo Motor* for automated roof control.
  - *Buzzer* and *LED Strip* for alerts and notifications.

## System Workflow
1. **Environmental Monitoring**: The system constantly tracks environmental conditions like temperature, gas levels, and rainfall.
2. **Fire Alarm Activation**: If the NTC thermistor senses a dangerous rise in temperature, a buzzer will sound to warn of a potential fire.
3. **Motion and Light**: The PIR sensor detects any movement, prompting the LED strip to illuminate the area.
4. **Gas Detection**: Upon detecting hazardous gases, the MQ2 sensor triggers an immediate alarm for safety.
5. **Roof Automation**: The raindrops module ensures the roof is automatically closed in response to rainfall.

## Prototype

![1](https://github.com/user-attachments/assets/5a9457b3-0e62-4203-a5b2-39aa07d60c1a)
![2](https://github.com/user-attachments/assets/38c63369-286b-4de7-b11d-4a830097d85f)
![3](https://github.com/user-attachments/assets/60e9c637-1438-40e0-bc25-1021eb9d4668)

## Our Team

![Team](https://github.com/user-attachments/assets/db8b5445-365d-4291-aa58-ea12cfe30c31)

