# Arduino Multi-Pin PWM Control

## Overview
This project is a fountain for large circular ponds. All the water jet pumps are installed around the pond and the nozzles are placed at the edge of the pond.
Each of the water pumps has a special driver.
Several water dance models are coded by Arduino and are executed sequentially. Colorful lights are also produced on the bottom of the pond by RGB light strings, making the pond look beautiful.


## Features
- Control of 25 output pins (digital and analog).  
- Smooth fade-in and fade-out effects using PWM.  
- Sequential activation patterns.  
- Configurable delays and loop cycles.  

## Requirements
- **Arduino Board** (e.g., Arduino Mega is recommended due to the high number of pins).  
- **Arduino IDE** installed on your computer.  
- External components (LEDs, resistors, or motors).  

## Installation
1. Clone this repository or download the `.ino` file.  
2. Open the file in **Arduino IDE**.  
3. Connect your Arduino board to your computer.  
4. Select the correct **board** and **port** in Arduino IDE.  
5. Upload the sketch to your Arduino.  

## Usage
- Connect LEDs (with resistors) or motors to the defined pins.  
- After uploading, the sketch will automatically start running.  
- You will see fade effects, alternating patterns, and sequential activations.  

## Pin Configuration
- Output pins: **2–13, A0–A12** (25 outputs).  
- Input pins: **22, 23** (used for digital HIGH/LOW initialization).  

## License
This project is open-source and available under the MIT License.  

# Fountain
