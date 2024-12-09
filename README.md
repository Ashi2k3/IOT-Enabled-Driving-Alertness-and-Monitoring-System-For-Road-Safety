# Driver Drowsiness and Drunken Driving Detection and Alertness System Using IoT

## Overview
This project implements a **non-intrusive IoT-based driver drowsiness monitoring system** designed to enhance road safety in logistics and public transportation. The system detects signs of driver fatigue and alcohol consumption, providing timely alerts to prevent accidents.

Key Features:
- **Real-time driver monitoring** using image processing and alcohol detection sensors.
- Integration of **IoT technologies** for remote monitoring and alerting.
- **Customizable dashboard** for data visualization and analysis.
- Designed for **scalability** and easy integration with logistics or fleet management systems.

## Objectives
1. Develop a non-intrusive framework for detecting driver drowsiness and alcohol consumption.
2. Utilize IoT technologies for real-time monitoring and alerts.
3. Enhance public and logistics transport safety.

## Technologies Used
- **Programming Languages:** Python, Arduino C
- **Frameworks:** Flask/Django (for web dashboard), TensorFlow/Keras (for drowsiness detection)
- **IoT Tools:** ESP32/Arduino for hardware integration
- **Machine Learning Algorithms:** XGBoost for emotion and fatigue detection
- **Other Tools:** OpenCV for image processing, PCA for feature extraction

## Features
- **Drowsiness Detection:** Monitors eye blink patterns and head orientation using a camera.
- **Alcohol Detection:** Utilizes an MQ-3 sensor to measure blood alcohol content (BAC).
- **Alerts:** Sends real-time alerts to the fleet manager or emergency contacts.
- **Data Logging:** Tracks historical data for monitoring and reporting purposes.

## Getting Started
### Prerequisites
- Python 3.7 or later
- NodeMCU/ESP32 microcontroller
- MQ-3 alcohol sensor
- Camera module (e.g., Pi Camera, USB camera)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Driver-Drowsiness-Detection-System.git
