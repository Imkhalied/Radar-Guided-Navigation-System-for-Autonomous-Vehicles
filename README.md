# Radar-Guided Navigation System for Autonomous Vehicles

A distributed autonomous navigation system that uses a stationary radar module to detect obstacles and wirelessly guide a mobile robot using **ESP-NOW** communication. The project demonstrates real-time obstacle avoidance through embedded control, wireless communication, and autonomous navigation.

---

# Project Overview

This project presents the design and implementation of a radar-guided autonomous vehicle where environmental sensing is performed by a stationary radar module instead of onboard sensors.

The radar continuously scans the environment using an ultrasonic sensor mounted on a servo motor and transmits obstacle information to a mobile robot through **ESP-NOW**. The vehicle receives navigation commands in real time, performs autonomous path correction to avoid obstacles, and automatically returns to its original trajectory.

The project combines embedded systems, wireless communication, sensor integration, and motor control into a complete autonomous robotic platform.

---

# Project Contents

- Design and implementation of a distributed autonomous navigation architecture
- 180° radar scanning using a servo-mounted ultrasonic sensor
- Real-time obstacle detection and distance measurement
- ESP32-to-ESP32 wireless communication using ESP-NOW
- Autonomous left/right obstacle avoidance logic
- Automatic lane recovery after obstacle avoidance
- Embedded motor control using an L298N motor driver
- Four-wheel differential drive vehicle control
- System integration, calibration, and experimental validation

---

# Key Specifications

| Parameter | Value |
|-----------|-------|
| Controllers | 2 × ESP32 |
| Communication Protocol | ESP-NOW |
| Detection Sensor | HC-SR04 Ultrasonic |
| Radar Scan Angle | 180° |
| Vehicle Platform | 4WD Mobile Robot |
| Motor Driver | L298N |
| Programming Language | Embedded C++ |
| Navigation | Autonomous Obstacle Avoidance |
| Communication Type | Wireless Peer-to-Peer |

---

# Technologies & Tools Used

- ESP32
- Arduino IDE
- Embedded C++
- ESP-NOW
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- L298N Motor Driver
- SolidWorks
- MATLAB

---

# Repository Structure

```text
Radar-Guided-Navigation-System/
│
├── Arduino_Code/
│   ├── Radar_Module/
│   └── Vehicle_Module/
│
├── CAD/
│   ├── Parts/
│   ├── Assembly/
│   └── Drawings/
│
├── Circuit_Diagrams/
│
├── Images/
│   ├── Hardware/
│   ├── Assembly/
│   └── Demonstration/
│
├── Documentation/
│   ├── Final_Report.pdf
│   └── Presentation.pdf
│
└── README.md
```

---

# Future Improvements

- Integrate LiDAR for higher accuracy obstacle detection
- Implement Computer Vision using OpenCV
- Migrate the project to ROS 2
- Implement SLAM for mapping and localization
- GPS-based outdoor autonomous navigation
- AI-based path planning and decision making
- Sensor fusion (Radar + Camera + IMU)
- Mobile dashboard for remote monitoring

---

# Supervision

**Assoc. Prof. Dr. Amgad M. Bayoumy**

---

# Author

**Khaled Diaa**

*Mechatronics Engineering Student*
