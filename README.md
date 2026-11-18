# Smart Water Level Monitoring System

**An ESP32-based IoT water tank monitoring system developed by Team TechTitans as part of the EN1190 Engineering Design Project at the University of Moratuwa.**

## Project Overview

This project was developed to address common problems associated with manual water tank monitoring, including water overflow, water wastage, and unexpected water shortages.

The system uses a waterproof ultrasonic sensor to measure the water level, an ESP32 microcontroller to process sensor readings, and a SIM800L GSM module to provide SMS notifications when the water reaches predefined levels.

A Firebase-connected web dashboard provides a visual interface for monitoring tank levels and managing tank settings.

## Key Features

- Water level measurement using a waterproof ultrasonic sensor
- ESP32-based sensor processing and control
- GSM-based SMS alerts for high and low water levels
- Firebase-connected web dashboard
- User authentication and assigned device selection
- Animated water level visualization
- Adjustable tank calibration and alert settings
- Weekly reporting using stored demonstration data
- Custom-designed two-layer PCB
- Rechargeable battery with USB Type-C charging
- Custom 3D-printed enclosure and sensor holder

## Hardware Components

| Component | Purpose |
|---|---|
| ESP32-WROOM-32D | Main microcontroller |
| JSN-SR04T | Waterproof ultrasonic water level measurement |
| SIM800L | GSM communication and SMS alerts |
| TP4056 | Lithium-ion battery charging |
| 18650 Li-ion Battery | Rechargeable power supply |
| Custom PCB | Hardware integration |
| 3D-Printed Enclosure | Protection and mechanical assembly |

## Software and Tools

- Arduino IDE
- Embedded C/C++
- Firebase
- Web dashboard development
- PCB design tools
- SolidWorks

## System Working Principle

1. The waterproof ultrasonic sensor measures the distance between the sensor and the water surface.
2. The ESP32 processes the distance measurement.
3. The water level is calculated using the tank's calibration settings.
4. The system checks the measured level against predefined thresholds.
5. GSM notifications are used to alert the user when the tank reaches critical levels.
6. The web dashboard displays water level information and device status.

## Web Dashboard

The web dashboard includes:

- Firebase authentication and device-specific access
- Live tank level and status visualization
- Tank calibration settings
- High and low alert threshold settings
- SMS notification configuration
- Weekly water level summaries based on demonstration history

## Engineering Design

The project includes a custom two-layer PCB designed to integrate the main electronic components.

A 3D-printed enclosure was designed using SolidWorks to accommodate the PCB, battery, connectors, and other components.

A non-invasive ultrasonic sensor mounting method was also developed to avoid permanently modifying the water tank.

## Challenges and Improvements

During development, the team addressed several engineering challenges:

- Improving ultrasonic sensor positioning for reliable measurements
- Reducing false alerts by checking repeated stable readings
- Debugging PCB assembly and voltage-related issues
- Improving enclosure fitment
- Developing a practical sensor installation method

## My Contribution

My primary responsibilities were:

- Microcontroller programming
- Web dashboard design and development

I also contributed to component selection, documentation, and final product testing alongside my teammates.

## Team

**Team TechTitans — University of Moratuwa**

- Jilodsan Rajgiry
- Thilishaan Muthukumar
- Thushanthan P.
- Vanujan P.

## Future Improvements

Potential future developments include:

- Automatic water pump control
- Further improvements to remote monitoring
- Enhanced historical data analysis
- Additional smart water management features

## Project Documentation

The project report, presentation, hardware images, and dashboard screenshots will be organized and added to this repository.
