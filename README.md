# Dual-Axis-Solar-Tracker

This Arduino code is designed to track light using four LDR (Light Dependent Resistor) sensors connected to an Arduino board. The code controls two servo motors, adjusting their positions based on the detected light levels to track the brightest spot.


## Functionality

The code performs the following functions:

- Reads analog values from four LDR sensors.
- Calculates average values for each direction (top, bottom, left, right).
- Determines the difference in light levels between opposite directions (vertical and horizontal).
- Adjusts servo motor positions based on the detected light levels to track the brightest spot.
- Includes tolerance thresholds to prevent excessive servo movements for small changes in light levels.

## Hardware Requirements

To use this code, you'll need the following hardware:

- Arduino board (e.g., Arduino Uno)
- Two servo motors for horizontal and vertical movement
- Four LDR sensors (connected to analog pins)
- Necessary connections and power supply

## Setup

1. Connect the LDR sensors to the analog pins of the Arduino board.
2. Connect the servo motors for horizontal and vertical movement to the designated pins.
3. Upload the provided Arduino code to the Arduino board.
4. Power on the Arduino board and observe the servo motors adjusting their positions to track the brightest spot.

## Configuration

- You can adjust the servo angle limits and other parameters by modifying the constants defined in the code.
- Tolerance thresholds for light level differences can also be adjusted to fine-tune the responsiveness of the tracking system.

## Credits

[Brown Dog Gadgets](https://www.browndoggadgets.com/), a provider of educational kits and resources for makers and educators.

For more projects and educational resources, visit their website: [https://www.browndoggadgets.com/](https://www.browndoggadgets.com/).


