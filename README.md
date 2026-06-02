# BrailleVision

An Arduino-based refreshable braille display prototype that uses servo-actuated braille modules to physically simulate 6-dot braille characters.

## Prototype Overview

### Final Prototype

![BrailleVision Prototype]<img width="429" height="372" alt="image" src="https://github.com/user-attachments/assets/ea3a489b-725b-4be6-a282-dc95147e9ca7" />


Complete assembled prototype showing the Arduino controller, servo motors, and braille display mechanism.

### Internal Hardware

![Internal Hardware]<img width="598" height="410" alt="image" src="https://github.com/user-attachments/assets/85d0193b-5f4d-4b27-b260-8e0d43345995" />


* Arduino Uno
* Servo Motors
* Braille Modules
* Wiring and Control Electronics

Workflow of the proposed text-to-braille conversion system.

## Features

* Refreshable braille display prototype
* Servo-actuated braille modules
* Arduino-based control system
* Physical tactile output
* Expandable OCR integration architecture

## Hardware Components

| Component       | Purpose                     |
| --------------- | --------------------------- |
| Arduino Uno     | Control unit                |
| Servo Motors    | Braille pattern actuation   |
| Braille Modules | Physical braille generation |
| Power Supply    | System operation            |

## Working Principle

The system uses servo motors to rotate custom braille modules into different positions, allowing tactile braille patterns to be generated physically.

Each braille character is represented by a specific combination of servo positions, enabling users to read the generated output by touch.

## Future Scope

* OCR integration using OpenCV and Tesseract
* Camera-based text capture
* Raspberry Pi deployment
* Multi-cell braille display
* Portable assistive reading device
