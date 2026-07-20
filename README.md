<img width="1672" height="941" alt="ChatGPT Image Jul 20, 2026, 09_50_39 PM" src="https://github.com/user-attachments/assets/24fb739e-ce69-4e84-9d4e-a5c22f146077" />


# FoxSense STM32 - Custom PCB Development Board

A custom STM32 development board designed from scratch using Altium Designer, programmed with STM32CubeIDE, and built for learning embedded systems, PCB design, and analog sensor interfacing.

🚀 Overview

FoxSense STM32 is a compact custom development board based on the STM32F103C8T6 microcontroller. The project demonstrates the complete hardware and firmware development workflow—from schematic capture and PCB layout to embedded firmware development.

The board measures temperature using an LM35 sensor and ambient light intensity using an LDR, then displays the measured values on a 0.96-inch SSD1306 OLED display. Sensor data is acquired using the STM32's built-in 12-bit ADC.

This repository contains everything needed to understand and reproduce the project, including the complete Altium Designer files and STM32 firmware.

✨ Features
✅ Custom STM32F103C8T6 PCB
✅ USB Type-C power input
✅ 3.3 V power supply using LF33 regulator
✅ 8 MHz external crystal oscillator
✅ LM35 temperature sensor interface
✅ LDR light sensor interface
✅ SSD1306 0.96" OLED display
✅ ADC-based sensor acquisition
✅ SWD programming/debug connector
✅ GPIO expansion headers
✅ Compact and beginner-friendly hardware design
🛠 Hardware Components
Component	Description
STM32F103C8T6	Main Microcontroller
SSD1306 OLED	0.96-inch I²C Display
LM35	Temperature Sensor
LDR	Light Sensor
LF33	3.3 V Voltage Regulator
USB Type-C	Power Input
8 MHz Crystal	System Clock
SWD Header	Programming & Debugging
Decoupling Capacitors	Power Filtering for STM32
📷 Project Demonstration

The board continuously:

Reads temperature from the LM35
Measures ambient light intensity using the LDR
Converts analog signals using the STM32 ADC
Displays live values on the OLED display

This project serves as a practical example of integrating sensors, ADCs, and an OLED display into a custom STM32-based hardware platform.

📁 Repository Structure
FoxSense-STM32/
│
├── Hardware/
│   ├── Schematic
│   ├── PCB
│   ├── Gerber Files
│   └── Manufacturing Outputs
│
├── Firmware/
│   ├── STM32CubeIDE Project
│   ├── Drivers
│   ├── Core
│   └── Libraries
│
├── Images/
│   └── Project Photos
│
└── README.md
🧰 Software Used
Altium Designer
STM32CubeMX
STM32CubeIDE
STM32 HAL Library
🎯 Project Objectives

This project was created to demonstrate:

Custom STM32 PCB design
Embedded firmware development
ADC configuration and sensor interfacing
OLED graphics using I²C
Hardware and software integration
Professional PCB design workflow
📸 Preview

It is recommended to place a photo of the completed PCB here.

![FoxSense PCB](Images/FoxSense_PCB.jpg)
🚀 Getting Started
Open the Hardware folder using Altium Designer.
Review the schematic and PCB layout.
Open the Firmware project using STM32CubeIDE.
Build and flash the firmware using an ST-Link programmer.
Power the board through the USB Type-C connector.
🤝 Contributing

Contributions, suggestions, and improvements are always welcome. Feel free to open an issue or submit a pull request.

📺 Video Demonstration

A complete walkthrough of this project—including the PCB design in Altium Designer, firmware development in STM32CubeIDE, hardware explanation, and live demonstration—is available on the Sly Fox Electronics YouTube channel.

If you find this project helpful, consider watching the video and subscribing to support future open-source embedded systems and PCB design projects.

📄 License

This project is released under the MIT License.

Designed and developed by Sly Fox Electronics 🦊
