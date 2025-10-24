# 💡 16x2 LCD Interface using PIC16F877A (4-bit Mode)

## 🔧 Project Overview
This project demonstrates how to interface a 16x2 LCD with the PIC16F877A microcontroller in 4-bit mode.  
It displays two messages on the LCD: "EMBEDDED" on the first line and "SYSTEMS" on the second line.

## ⚙️ Hardware & Software Requirements

### Hardware:
- PIC16F877A Microcontroller
- 16x2 LCD Display
- 330Ω resistor (for LCD backlight if needed)
- Breadboard / Proteus simulation board
- Connecting wires

### Software:
- MPLAB X IDE
- XC8 Compiler
- Proteus 8 Professional (for simulation)

🧩 Proteus Circuit Setup

Controller: PIC16F877A

Oscillator: 20 MHz Crystal (pins 13 & 14)

LCD: RS→RB0, RW→RB1, EN→RB2, D4-D7→RB4-RB7

Power: +5V to VDD, GND to VSS

▶️ Simulation Steps

Open Proteus_Design.pdsprj in Proteus 8.

Load the compiled .hex file from MPLAB X.

Run simulation — observe "EMBEDDED" on line 1 and "SYSTEMS" on line 2.

📸 Output

LCD displays:

   EMBEDDED
   SYSTEMS

🧰 Future Expansion Ideas

Scroll long messages across LCD.

Display sensor readings in real-time.

Add buttons to change messages dynamically.
