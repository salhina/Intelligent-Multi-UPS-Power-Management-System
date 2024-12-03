# Intelligent Multi-UPS Power Management System

## Project Overview

This capstone project demonstrates an advanced embedded system for dynamic UPS (Uninterruptible Power Supply) management, developed at Sidi Mohammed Ben Abdellah University, Fez. Led by Nabil Salhi, the system optimizes power delivery by intelligently activating UPS units based on real-time load demands, featuring a web-based Human-Machine Interface (HMI) for comprehensive monitoring and control.

![Project HMI Screenshot](https://github.com/user-attachments/assets/3588260b-6f96-4e27-ad4a-6b4b007b1821)

## Key Features

### Embedded Control System
- **Microcontroller**: PIC 16F877A
- **Real-Time Measurements**:
  - Voltage transformer for system voltage monitoring
  - Current transformer for load current tracking
- **Power Calculation**: Instantaneous power computation using P = V × I

### Intelligent Load Management
The system employs a sophisticated algorithm for dynamic UPS unit activation:

| Power Range | UPS #1 | UPS #2 | UPS #3 | UPS #4 |
|-------------|--------|--------|--------|--------|
| p < 2.6 kW | Active | Inactive | Inactive | Inactive |
| 2.6 kW ≤ p < 5.2 kW | Active | Active | Inactive | Inactive |
| 5.2 kW ≤ p < 7.85 kW | Active | Active | Active | Inactive |
| p ≥ 7.85 kW | Active | Active | Active | Active |

### Web-Based Human-Machine Interface (HMI)
- Real-time current, voltage, and power consumption display
- Dynamic power consumption graphing
- Manual UPS unit control functionality

## Technologies Utilized

1. **Embedded Systems**
   - Microcontroller: PIC 16F877A
   - Embedded C Programming

2. **Power Electronics**
   - Voltage transformers
   - Current transformers
   - UPS unit interfacing

3. **Communication**
   - Serial communication protocol
   - Web server data transmission

4. **Web Technologies**
   - JavaScript for dynamic interface
   - Real-time data visualization

## Project Details

- **Duration**: March 2013 - June 2013
- **Institution**: Sidi Mohammed Ben Abdellah University, Fez
- **Project Lead**: Nabil Salhi
- **Team Size**: 4 members

## Performance Metrics and UPS Status (from Screenshot)

### Instantaneous Data
- **Current**: 40.8 Amperes
- **Voltage**: 151 Volts
- **Power Consumption**: 6.15 kW

### UPS Unit Status
- **Onduleur1 (UPS #1)**: On
- **Onduleur2 (UPS #2)**: On
- **Onduleur3 (UPS #3)**: On
- **Onduleur4 (UPS #4)**: Off (Load demand < 7.85 kW)

## Project Highlights

- **Energy Efficiency**: Adaptive power management
- **Scalability**: Easily expandable to additional UPS units
- **User Accessibility**: Intuitive web interface
- **Robust Design**: Seamless hardware-software integration

## Connect

[![Portfolio](https://img.shields.io/badge/GitHub-Portfolio-blue?logo=github)](https://salhina.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/nabil-salhi)

## License

[Specify License - e.g., MIT, Apache 2.0]

## Acknowledgments

Special thanks to Sidi Mohammed Ben Abdellah University for providing the academic environment, resources, and support that made this innovative project possible.
