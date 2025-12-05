Project Title and Description
 Arduino Bluetooth-Controlled Car

This project is a Bluetooth-operated robotic vehicle built using an Arduino microcontroller, an HC-05 Bluetooth module, and an L298N motor driver. The car receives commands from a smartphone over Bluetooth and performs movements such as forward, backward, left, right, and stop.
The project demonstrates basic robotics, embedded programming, and wireless communication principles while maintaining a clear and organized documentation structure.

Clear Instructions for Setup, Usage, and Replication
 Setup Instructions
1. Required Components

Arduino Uno or Nano

HC-05 Bluetooth module

L298N motor driver

Two DC gear motors

Motorized chassis

Battery pack (9V or Li-ion)

Jumper wires

2. Wiring Overview

HC-05 → Arduino

VCC → 5V

GND → GND

TX → Arduino RX

RX → Arduino TX

L298N → Arduino + Motors

OUT1/OUT2 → Motor A

OUT3/OUT4 → Motor B

VIN → Battery

A full wiring diagram can be followed using the schematic provided in the repository.

 Uploading the Code

Open Arduino IDE.

Load the provided bluetooth_car.ino file.

Select your board and COM port.

Disconnect HC-05 TX/RX before uploading to avoid serial interference.

Upload the code, then reconnect the HC-05.

📱 Usage Instructions

Pair your phone with HC-05 (default password: 1234).

Open any Bluetooth terminal/control app.

Send these commands to control the car:

Command	Action
F	Move Forward
B	Move Backward
L	Turn Left
R	Turn Right
S	Stop
Replication Instructions

To recreate the project:

Clone or download the repository.

Assemble the hardware as shown in the wiring diagram.

Upload the Arduino code from /code.

Use a Bluetooth terminal app to control the vehicle.

Optional: Print or cut 3D components from the /3d_models folder.

All required materials—code, images, schematics, and models—are included.

 Summary of Purpose and Outcomes
Purpose

The goal of this project was to build a simple, effective Bluetooth-controlled robotic car that demonstrates fundamental concepts in robotics, programming, electronics, and wireless communication. It also aimed to develop clear engineering documentation through schematics, photos, and organized code.

Outcomes

A fully functional Bluetooth-controlled car was successfully built and tested.

Movement in all directions works reliably using serial Bluetooth commands.

The project features complete documentation, including wiring diagrams, images, and code.

Optional enhancements (custom 3D parts, speed control, automation) were identified for future improvement.
