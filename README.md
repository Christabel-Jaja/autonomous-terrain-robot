time contr# Autonomous Mobile Robot for Rough Terrain Navigation

A fully autonomous mobile robot designed and built from scratch for my Bachelor's thesis at Don State Technical University (2024).

## Robot Photo
![Robot](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/Vkp%20robot.jpg)

## What I Built
A mobile robot capable of navigating complex terrain autonomously, with remote control and live video surveillance capabilities. Every component was designed, 3D-printed, wired, and programmed by hand.

## Hardware
- Arduino Mega (main controller)
- GPS module + TinyGPS++ library
- Magnetometer (orientation sensing)
- L298N motor driver
- Ultrasonic sensor (obstacle detection)
- ESP32 camera (live video surveillance)
- Bluetooth module (SoftwareSerial)
- FM Transmitter and Receiver modules (remote control)
- 12V DC geared motors
- Custom 3D-printed chassis and terrain-specific tires

## Software
- Arduino IDE
- TinyGPS++ (GPS navigation)
- SoftwareSerial (Bluetooth communication)
- Arduino Math libraries

## Mechanical Design
- Full chassis designed in KOMPAS 3D
- Custom tire geometry designed specifically for rough terrain stability
- All components 3D-printed

## Assembly & General View
![Assembly](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/%D0%92%D0%9A%D0%A0%20%D0%A1%D0%B1%D0%BE%D1%80%D0%BA%D0%B0%20_%D0%9E%D0%B1%D1%89%D0%B8%D0%B9%20%D0%B2%D0%B8%D0%B4%2C%20.jpg)

## Kinematics
![Kinematics](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/%D0%92%D0%9A%D0%A0%20kinematics.jpg)

## Electrical Schematics

### Transmitter Circuit
![Transmitter](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/Electrical%20%D1%81%D1%85%D0%B5%D0%BC%D0%B0%20(transmiter).jpg)

### Receiver Circuit
![Receiver](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/Electri%20%D1%81%D1%85%D0%B5%D0%BC%D0%B0%20reciever%20%D0%A7%D0%B5%D1%80%D1%82%D0%B5%D0%B6.jpg)

## Robot Behavior Algorithm
![Algorithm](https://raw.githubusercontent.com/Christabel-Jaja/autonomous-terrain-robot/main/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BF%D0%BE%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D0%B0%20%20%D1%81%20%D0%B4%D0%B8%D1%81%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%BC%20%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%D0%BC%20.jpg)

## Skills Demonstrated
- Embedded systems programming
- Electrical wiring and circuit design
- Mechanical design and 3D printing
- System integration (mechanical + electrical + software)
- GPS navigation and real-time controlol
