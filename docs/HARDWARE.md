# Hardware

## Overview

The robot was designed using commercially available components that provide a balance between performance, reliability, and future expandability.

During the hardware selection process, each component was evaluated according to the project requirements rather than popularity alone. The selected hardware provides sufficient processing power, accurate sensing, reliable steering, and the flexibility required for future improvements.

The following sections describe the main hardware components used in the robot and the purpose of each one.

## Hardware Summary

| Component        | Model                  | Purpose                                           |
| ---------------- | ---------------------- | ------------------------------------------------- |
| Main Controller  | ESP32                  | Real-time control of sensors, motor, and steering |
| Vision Computer  | Raspberry Pi 3 Model B | Future computer vision processing                 |
| Distance Sensors | 2 × VL53L1X            | Wall detection and distance measurement           |
| IMU              | MPU6050                | Robot orientation and heading                     |
| Color Sensor     | TCS34725               | Detecting floor colors                            |
| Motor Driver     | L298N                  | DC motor control                                  |
| Steering Servo   | MG996R                 | Ackermann steering                                |
| Drive Motor      | DC Gear Motor          | Vehicle propulsion                                |
| DC Converter     | Buck Converter         | Stable voltage regulation                         |
| Chassis          | RC Ackermann Chassis   | Mechanical platform                               |

