# IoT-Based School Safety Zone Sensor System

## Project Overview

The IoT-Based School Safety Zone Sensor System is a prototype designed to improve road safety near school and hospital zones.

The system detects a vehicle entering a restricted safety zone using an ultrasonic sensor. The Arduino UNO processes the sensor input and controls the vehicle model through an L298N motor driver to reduce its speed.

At the same time, LED and buzzer alerts are activated to warn the driver and nearby pedestrians. An ESP8266 Wi-Fi module is used to send real-time system information to an IoT cloud platform such as ThingSpeak.

## Objectives

- Automatically detect vehicles entering a safety zone.
- Reduce vehicle speed when a vehicle enters the restricted area.
- Alert drivers and pedestrians using LED and buzzer indicators.
- Send real-time data to an IoT cloud platform.
- Provide a low-cost prototype for school and hospital safety zones.

## Hardware Components

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- L298N Motor Driver
- DC Motor
- ESP8266 Wi-Fi Module
- Red and Green LED Indicators
- Buzzer
- 9V Battery / DC Power Supply
- Connecting Wires
- Breadboard
- 4WD Four Wheel Robotic Smart Car Chassis

## Software and Platforms

- Arduino IDE
- Embedded C
- ThingSpeak IoT Platform
- Blynk Application (Optional)

## Working Principle

1. The system is powered on and all components are initialized.
2. The HC-SR04 ultrasonic sensor continuously measures distance.
3. When a vehicle enters the predefined safety-zone range, the sensor sends the information to the Arduino UNO.
4. The Arduino processes the input and sends a control signal to the L298N motor driver.
5. The motor speed is automatically reduced.
6. The red LED and buzzer are activated as warning indicators.
7. The ESP8266 Wi-Fi module sends the current status to the IoT cloud platform.
8. When the vehicle leaves the safety zone, the system returns to its normal state and the green LED indicates safe operation.

## System Architecture

Sensor → Arduino UNO → L298N Motor Driver → DC Motor

Arduino UNO → ESP8266 → ThingSpeak IoT Cloud → Monitoring Dashboard

## Testing and Results

The prototype was tested under different conditions using different vehicle distances and sensor placements.

During testing:

- The system detected vehicles entering the safety zone.
- The motor speed was automatically reduced after detection.
- The red LED and buzzer provided warning alerts.
- The ThingSpeak dashboard displayed the vehicle detection status.
- Sensor data was successfully transmitted through Wi-Fi under stable network conditions.

The report records an approximate detection response time of 1 second and a motor speed reduction of about 50–60% upon detection.

## My Contribution

- Worked as the Group Leader for the project.
- Helped coordinate the project work within the team.
- Worked on the hardware wiring and component connections.
- Helped with the initial setup and successfully performed the first working run of the prototype.
- Explained the project working and implementation during the project presentation.

## Applications

- School safety zones
- Hospital safety zones
- Residential and parking areas
- Industrial and construction sites
- Smart city traffic management
- Educational IoT and embedded-system demonstrations

## Limitations

- The ultrasonic sensor has a limited detection range.
- Wi-Fi connectivity depends on network availability.
- The prototype uses a small motor to simulate vehicle speed.
- Environmental conditions may affect sensor performance.
- The prototype requires suitable power supply and maintenance for continuous operation.

## Future Scope

Possible future enhancements include:

- GPS and GSM integration
- Advanced sensors and AI-based detection
- Centralized traffic management
- Mobile application development
- Solar-powered operation
- Smart city infrastructure integration
- Machine learning for predictive analysis
- Real-vehicle implementation

## Project Report

The complete project report is available in this repository.

## Team Members

- Monu Mishra
- Punit Kumar Prasad
- Prince Kumar
- Mukesh Kumar
