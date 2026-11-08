# ESP32 RC Car Control System

## Project Overview

Designed a custom electronic control system for a remote-controlled car, consisting of an ESP32-based transmitter and a receiver/motor controller. The project focuses on PCB design, power regulation, microcontroller integration, and brushed DC motor control.

Both circuits were developed using KiCad, with custom schematics and PCB layouts.

## Receiver and Motor Controller

The receiver board integrates several electrical subsystems:

- **ESP32 DevKitC:** Microcontroller interface for motor speed, direction, and steering control.
- **MOSFET H-Bridge:** Discrete switching circuit designed for bidirectional control of a brushed DC motor.
- **Power Regulation:** 7.4V nominal (2S) LiPo battery input with 5V linear voltage regulation.
- **Servo Interface:** Three-pin connector for steering servo control.
- **Circuit Protection and Filtering:** Bulk and decoupling capacitors incorporated into the power distribution design.

## Transmitter

Designed a separate ESP32-based transmitter circuit featuring:

- Joystick inputs for throttle and steering commands.
- ESP32 microcontroller for reading user inputs.
- Power regulation and supporting circuitry.
- Custom PCB schematic and layout.

## Engineering Tools and Skills

- KiCad schematic capture and PCB layout
- Circuit analysis and component selection
- MOSFET switching circuit design
- Microcontroller interfacing
- Power distribution and voltage regulation
- Hardware documentation

## Project Status

PCB design and documentation stage. Physical assembly, firmware validation, and hardware testing are not yet documented.

## Future Development

- Assemble and test the transmitter and receiver boards.
- Develop and validate wireless communication and control firmware.
- Test motor switching, steering response, and power regulation.
- Evaluate circuit performance and refine the hardware design.
