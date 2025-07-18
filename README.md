# Analog Temperature-Controlled Fan using LM35 & Transistor

This project controls a 5V DC fan based on temperature using only analog hardware components. The LM35 sensor senses temperature and switches on the fan through an NPN transistor (BC547), acting as an automatic cooling mechanism without requiring any programming.

## Components:
- LM35
- BC547
- 5V Fan
- 10k Resistor
- Power Supply

## How it Works:
As the temperature rises above 30°C, LM35’s output voltage increases. When this voltage crosses the transistor’s base-emitter threshold (~0.7V), the transistor turns on, completing the circuit and powering the fan.

## Applications:
- Low-cost cooling systems
- Analog automation
- Fan control in passive systems
