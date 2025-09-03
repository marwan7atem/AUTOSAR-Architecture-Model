# AUTOSAR-Architecture-Model
A full AUTOSAR layered architecture implementation for TM4C microcontroller. Features AUTOSAR-compliant Port, DIO, and GPIO drivers. Demonstrates configuration, initialization, and hardware abstraction following automotive software standards.

# AUTOSAR Architecture Model: Port, DIO, and GPIO Drivers

A full AUTOSAR-compliant layered architecture implementation for the Texas Instruments TM4C microcontroller. This project demonstrates the development and integration of essential AUTOSAR MCAL drivers, providing a foundation for automotive software systems.

## ✨ Features

- **AUTOSAR-Compliant Drivers**: Implementation of Port, DIO, and GPIO drivers following AUTOSAR standards.
- **Layered Architecture**: Full adherence to AUTOSAR layered model (Application, ECU Abstraction, MCAL).
- **Hardware Abstraction**: Complete abstraction of microcontroller peripherals for portability.
- **Configuration Flexibility**: Pre-compile configuration of port pins and GPIO modes.
- **Automotive Standards**: Developed following MISRA C guidelines and automotive best practices.

## 🏗️ Architecture Overview
Application Layer
|
RTE (Run-Time Environment)
|
ECU Abstraction Layer
|
MCAL (Microcontroller Abstraction Layer)
├── DIO Driver
├── Port Driver
└── GPIO Driver
|
TM4C123GH6PM Microcontroller Hardware

## ⚙️ Driver Features

### Port Driver
- Pin direction configuration (Input/Output)
- Pin mode setup (Digital/Analog)
- Internal pull-up/pull-down resistor configuration
- Pin multiplexing configuration

### DIO Driver
- Digital channel read/write operations
- Channel group operations
- Port-level read/write functionality
- Time-efficient port manipulation

### GPIO Driver
- TM4C-specific GPIO initialization
- Alternate function configuration
- Current drive strength setup
- Slew rate control

## 🚀 Getting Started

### Prerequisites
- **IDE**: [Code Composer Studio](https://www.ti.com/tool/CCSTUDIO) or Keil MDK
- **Target Hardware**: TM4C123G LaunchPad or equivalent
- **AUTOSAR Knowledge**: Understanding of AUTOSAR architecture concepts

👨‍💻 Developer
Marwan Mohamed Hatem

Email: marwanhatem017@gmail.com

LinkedIn: https://www.linkedin.com/in/marwan-hatem-6a516b225/

GitHub: https://github.com/marwan7atem

📄 License
This project was developed as part of the Embedded Automotive and AUTOSAR course from Edges For Training. The implementation follows AUTOSAR standards for educational purposes.

