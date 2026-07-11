# Isolated DC Motor Driver v1.0

A simple DC motor control circuit using **optocouplers** for galvanic isolation between Arduino (5V) and 12V motor driver.

## Features
- Full galvanic isolation (protects Arduino from motor noise and spikes)
- Forward and Reverse motor control
- Flyback diode for inductive spike protection
- Separate 5V control and 12V power supplies

## Components
- Arduino or similar MCU
- 2x Optocoupler (4N35 / PC817)
- L298N Motor Driver
- 1N4007 Flyback Diode

## How It Works
Optocouplers provide electrical isolation between the low voltage control side and the motor driver side.

## Future Improvements
- MOSFET based H-Bridge for higher efficiency
- Current sensing
- Professional 2-layer PCB design

## License
Open for learning and personal use.
