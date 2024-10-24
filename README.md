# IoT Based Home Automation System with Google Assistant

By [Naimur Rahman](https://github.com/nayeem-rafi)

## [Click for video Presentation](https://drive.google.com/drive/folders/1JY92GC6HMercLNbLYtevnSQWehi7-6t9?usp=drive_link)

## Introduction
Discover the future of home living with our IoT-based Home Automation System, enhanced by Google Assistant. This project allows you to control household appliances such as lights and fans through voice commands, offering a seamless, convenient, and modern living experience.

## Project Description
This project utilizes an ESP32 microcontroller along with relays, switches, and the Sinric Pro API to enable smart home automation. It allows users to control up to four devices using either Google Assistant voice commands or traditional switches. The system is connected to the internet via Wi-Fi, offering both local and remote control capabilities.

The primary components of the system include:
- **NodeMCU ESP32 Microcontroller**: The core of the project that manages device control.
- **Relays**: To switch devices on and off.
- **Sinric Pro**: A cloud platform that communicates with Google Assistant.
- **Switches**: For manual control.

The system can currently control two devices (e.g., light and fan) and is easily scalable to handle more.

## Project Objectives
- Implement a cost-effective home automation system.
- Provide seamless integration with Google Assistant.
- Enable control of home appliances remotely via the internet.
- Utilize voice commands for hands-free operation.

## How It Works
1. The **ESP32 microcontroller** connects to your home Wi-Fi.
2. Using **Sinric Pro** and Google Assistant, the system listens for voice commands.
3. When a voice command is given, Sinric Pro communicates with the ESP32 to toggle the connected appliances (like lights or fans).
4. The system also allows manual operation using physical switches connected to the ESP32.

## ESP32 Pin Explanation
- **GPIO Pins** are used to control the relays. For example:
  - GPIO23 controls the light.
  - GPIO22 controls the fan.
- **Power Supply**: The ESP32 is powered by a 5V supply from a rectifier circuit.
- **Other Pins**: Connected to relays and switches for controlling the devices.

## Voice Control with Google Home
By connecting the system to a Google Home device:
1. Set up **Sinric Pro** to link the ESP32 with Google Assistant.
2. Issue commands like "Hey Google, turn on the light" or "Hey Google, turn off the fan."
3. The system will then trigger the respective relay to switch the device on or off.

## Components and Costs
| Component             | Cost (BDT) |
|-----------------------|------------|
| ESP32 Microcontroller | 400        |
| 4-Channel Relay       | 180        |
| Switches (2x)         | 40         |
| Transformer           | 230        |
| Diodes (4x)           | 4          |
| Capacitors            | 35         |
| LM7805 Regulator      | 10         |
| **Total**             |**1199 BDT**|

## Application
This project provides a simple, reliable, and cost-effective solution for controlling home devices. Applications include:
- Smart lighting
- Remote fan control
- Integration with home security systems

## Limitations
- Limited to controlling four devices without additional hardware.
- Dependent on a stable internet connection for remote operation.

## Conclusion
This IoT-based home automation system offers a glimpse into the future of living, where convenience meets technology. It is easy to use, affordable, and can be controlled from anywhere in the world. If you're looking to automate your home and embrace futuristic technology, this project is a great starting point.




