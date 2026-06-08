# ESP32-Based Auto Irrigation System

An automated plant irrigation system built using ESP32 with dual 
capacitive soil moisture sensors and relay-controlled water pumps.

## Features
- Monitors soil moisture levels in real time
- Automatically triggers pumps when moisture drops below threshold
- Failsafe cut-off if sensor readings are abnormal
- Manages irrigation for ~100 plants without manual intervention

## Hardware Used
- ESP32 development board
- Capacitive soil moisture sensors (x2)
- Relay module
- Water pump

## Tech Stack
- Embedded C (Arduino framework)
- ESP32, GPIO, ADC peripherals
