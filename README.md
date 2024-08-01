# Arduino smart kitchen - IoT project

## Description

The IoT Smart Kitchen project aims to enhance the functionality and safety of a kitchen by integrating various sensors and actuators controlled by an Arduino Uno R3. The project includes features such as motion detection, temperature monitoring, gas leak detection, and automatic cabinet door control.

## Model

![image](https://github.com/user-attachments/assets/ae2cf0e8-50fc-4b85-8a0d-dbd92ec650e7)

## Activities

### 1. Cabinet Door Automation:

Uses the Ultrasonic Distance Sensor to measure the distance to the cabinet door.
If the distance is less than 15 cm, the servo motor will open the door.
The door remains open for 5 seconds before closing automatically.
Motion Detection Lighting:

### 2. The PIR Sensor detects motion in the kitchen.
When motion is detected, two light bulbs connected via relays are turned on.
If no motion is detected, the lights are turned off.
Temperature Monitoring and Alert:

### 3. The Temperature Sensor continuously monitors the kitchen temperature.
If the temperature exceeds 30°C, a relay turns on a fan or an alert system to cool the area.

### 4. Gas Leak Detection:
The Gas Sensor (assumed to be connected to analog pin A0) monitors for gas leaks.
If a gas leak is detected (reading above a threshold), an alert is triggered by turning on a light bulb connected via a relay.

### 5. Sound Alerts:
A Piezo is used to produce sound alerts when necessary, such as during gas leak detection.

## Components

1. 1 Arduino Uno R3: Microcontroller board to control all components.
2. 1 PIR Sensor: Detects motion and controls the lighting accordingly.
3. 2 DC Motor: For various mechanical operations (e.g., turning a knob, opening a door).
4. 2 Relay SPDT: To control the light bulbs and other high-power devices.
5. 3 light bulb: Used for illumination.
6. 1 Power supply: To power the Arduino and other components.
7. 1 Temperature sensor: Monitors the temperature and triggers a cooling system if it gets too hot.
8. 1 Piezo: For sound alerts.
9. 1 Micro Servo: For precise mechanical movements.
10. 1 Ultrasonic Distance Sensor: Measures the distance to the cabinet door. If the distance is less than 15 cm, it opens the door using the servo motor.
11. 1 Gas sensor: Detects gas leaks and triggers an alert system.
12. 1 Resistor and 2 Slideswitch

## Simulation and Demo

[https://www.tinkercad.com/things/jCJw7zTUw9T-smart-kitchen-for-my-house](https://www.tinkercad.com/things/jCJw7zTUw9T-smart-kitchen-for-my-house?sharecode=J-EoaXnW3DnM14OpEt9AE6FODnLi7rGFr7jly8o7l_A)
