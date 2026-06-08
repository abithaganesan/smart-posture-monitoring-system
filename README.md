# Smart Posture Alignment and Regulation Technology

## Overview
The Smart Posture Monitoring and Feedback System is a wearable biomedical electronics project designed to detect incorrect body posture and provide real-time corrective feedback. The system aims to support ergonomic health by reducing long-term musculoskeletal strain caused by improper sitting or standing posture.

This project was developed as part of an academic biomedical engineering curriculum.

## Objective
To design and implement a wearable system capable of monitoring human posture and generating immediate feedback when incorrect posture is detected using sensor-based measurements.


## System Description
The system continuously monitors body posture using wearable sensors. The acquired data is processed through a microcontroller, where predefined threshold logic is used to classify posture as correct or incorrect. If incorrect posture is detected, the system triggers an alert mechanism to notify the user for correction.

## System Architecture

Sensor Unit → Signal Acquisition → Microcontroller Processing → Threshold Analysis → Decision System → Feedback Output

## Working Principle
1. Wearable sensors continuously capture posture-related body movement data  
2. Sensor signals are transmitted to a microcontroller  
3. Embedded firmware processes incoming signals in real time  
4. Threshold-based logic determines posture correctness  
5. If incorrect posture is detected, an alert is generated  
6. User receives immediate feedback to correct posture  

## Hardware Components
- Arduino Uno / ESP32 microcontroller  
- MPU6050 IMU sensor / Flex sensor (based on implementation)  
- Buzzer / vibration motor for feedback alerts  
- LCD display module (optional output interface)  
- Supporting passive electronic components  


## Technologies Used
- Embedded C programming  
- Microcontroller-based system design  
- Sensor data acquisition and processing  
- Threshold-based classification logic  
- Real-time embedded feedback system  


## System Features
- Real-time posture monitoring  
- Wearable sensor-based detection system  
- Immediate feedback mechanism (audio/vibration alert)  
- Low-cost biomedical ergonomic solution  
- Portable embedded system design  


## System Workflow
1. Sensor captures posture data  
2. Microcontroller reads and processes signals  
3. Signal values are compared with threshold limits  
4. Posture state is classified as correct or incorrect  
5. Alert is triggered if incorrect posture is detected  


## Results & Observations
- The system successfully detects posture deviations based on sensor input  
- Real-time processing enables immediate feedback response  
- Alert mechanism effectively notifies users of incorrect posture  
- Demonstrates feasibility of low-cost wearable ergonomic monitoring systems  


## Limitations
- Calibration depends on sensor positioning and user body type  
- Accuracy may vary with movement noise and environmental conditions  
- System requires further optimization for clinical or industrial deployment  


## Future Improvements
- Integration of machine learning for posture classification accuracy improvement  
- Wireless connectivity for mobile-based posture tracking  
- Cloud-based posture analytics and reporting  
- Miniaturized wearable PCB design for improved portability  
- Enhanced sensor fusion for higher accuracy  


## Status
Prototype successfully built and tested during academic project phase (2024–2025).

## Author
Abitha Ganesan  
B.E. Biomedical Engineering  

GitHub: https://github.com/abithaganesan  

## Note
This project was developed as part of academic biomedical engineering coursework and demonstrates a functional prototype of a wearable posture monitoring system.
