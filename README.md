[Home Auto.txt](https://github.com/user-attachments/files/33291958/Home.Auto.txt)
# arduino-uno-bluetooth-home-automation
Arduino UNO-based home automation project using Bluetooth communication and a relay module to control connected electrical devices.
arduino-uno-bluetooth-home-automation/
├── README.md
├── code/
│   └── home_automation.ino
└── images/
    └── circuit-diagram.png
    # Arduino UNO Bluetooth Home Automation System

An Arduino-based home automation project that explores Bluetooth communication and relay-based control of connected electrical devices.

## Project Overview

This project uses an Arduino UNO, a Bluetooth communication module, and a relay module to demonstrate the fundamentals of home automation.

The Arduino processes commands received through Bluetooth and can control connected devices through the relay circuit, according to the implementation in the source code.

## Components Used

* Arduino UNO
* Bluetooth module (exact model to be confirmed)
* Relay module
* Breadboard
* Jumper wires
* Compatible power supply
* Electrical device or load, if included in the actual setup

## Features

* Arduino-based control system
* Bluetooth communication
* Relay interface for switching connected devices
* Embedded programming practice
* Educational demonstration of home automation

*Features should be confirmed against the uploaded source code and actual hardware.*

## Hardware and Software

**Hardware**

* Arduino UNO
* Bluetooth module
* Relay module
* Breadboard and jumper wires

**Software**

* Arduino IDE
* Arduino programming framework (C/C++)

## How It Works

1. The Bluetooth module receives commands from a compatible Bluetooth device.
2. The Arduino UNO processes the received commands.
3. The program controls the relay module according to the configured commands.
4. The relay switches the connected load, provided the wiring and control logic are correctly implemented.

The supported commands, Bluetooth pairing procedure, pin assignments, and relay logic depend on the actual source code and hardware configuration.

## Repository Structure

* `README.md` — Project documentation
* `code/home_automation.ino` — Arduino source code
* `images/circuit-diagram.png` — Circuit diagram, when available

## Installation and Setup

1. Install the Arduino IDE.
2. Identify the Bluetooth module and verify its voltage requirements.
3. Connect the Arduino, Bluetooth module, and relay according to the verified circuit.
4. Open `code/home_automation.ino` in the Arduino IDE.
5. Select the appropriate Arduino UNO board and port.
6. Verify the code, library requirements, pin assignments, and Bluetooth command format.
7. Upload the code to the Arduino UNO.
8. Pair a compatible Bluetooth device and test the commands using a suitable application.

## Testing Status

Document the actual results after testing:

* Code compilation: Not yet documented<img width="2736" height="1536" alt="daigram" src="https://github.com/user-attachments/assets/21fc943c-4108-464d-8569-209f0177c373" />
* Bluetooth communication: Not yet documented
* Relay switching: Not yet documented
* Complete hardware test: Not yet documented

## Safety Notice

This is an educational prototype. Relay-controlled mains electricity can cause electric shock, fire, or equipment damage. Do not handle exposed mains wiring. Use appropriate isolation, enclosures, and qualified supervision.

## Author

**Imran Khan**

* GitHub: https://github.com/Imran-khan009
* Portfolio: https://sengrimrankhan.netlify.app
