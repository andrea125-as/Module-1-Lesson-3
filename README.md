
# Two LED Control System

## Project Description
This project demonstrates how an Arduino Uno controls two independent LEDs using digital output pins, HIGH, LOW, and delay values.

## Components Used
1. Arduino Uno
2. Breadboard
3. Red LED
4. Green LED
5. Two 220Ω Resistors
6. Jumper Wires

## Wiring Connections

### Red LED
1. Arduino D8 → 220Ω resistor
2. Other resistor end → A10
3. Red LED anode (+) → E10
4. Red LED cathode (-) → E11
5. A11 → Blue GND rail

### Green LED
1. Arduino D9 → 220Ω resistor
2. Other resistor end → A15
3. Green LED anode (+) → E15
4. Green LED cathode (-) → E16
5. A16 → Blue GND rail

### Common Ground
Arduino GND → Blue negative rail

## How It Works
- HIGH turns an LED ON.
- LOW turns an LED OFF.
- delay(1000) creates a one-second delay.
- The red and green LEDs can alternate.
- Both LEDs can also turn ON and OFF together.

## Files
- README.md – Project documentation.
- app.py – Streamlit monitoring dashboard.
- sketch.ino – Arduino control program.

## Technologies Used
- Arduino Uno
- C++
- Python
- Streamlit
- Pandas
- Wokwi
