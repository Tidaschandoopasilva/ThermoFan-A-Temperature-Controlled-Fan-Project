# ThermoFan: A Temperature-Controlled Fan Project

## Overview
ThermoFan is a temperature-controlled fan circuit designed using an NE555 timer and an NTC thermistor. The fan's speed is automatically adjusted based on temperature, offering an efficient cooling solution. This repository contains:

- **Circuit Schematic**
- **LTSpice Simulation**
- **PCB Design**

## Features
- Automatically controls fan speed based on temperature changes.
- Compact design using analog components.
- Includes simulation and PCB files for easy replication.

## Components Used
- NE555 Timer IC
- NTC Thermistor (103AT-4-050)
- MOSFET (IRF540N)
- Diodes (1N5408)
- Resistors and Capacitors
- Fan

## Files Included
1. **Schematic:** Circuit diagram in EasyEDA format.
2. **Simulation:** LTSpice simulation files for analyzing circuit behavior.
3. **PCB Design:** Gerber files for PCB fabrication.

## How It Works
1. The NTC thermistor senses temperature changes.
2. The NE555 timer generates a control signal based on the thermistor's resistance.
3. The signal modulates the MOSFET, adjusting the fan's speed accordingly.

## Getting Started
### Requirements:
- LTSpice (for simulation)
- EasyEDA (for schematic and PCB design)

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ThermoFan.git
   ```
2. Open the schematic and PCB files in EasyEDA.
3. Run the LTSpice simulation files for testing.
4. Fabricate the PCB using the provided Gerber files.

## Applications
- Electronics cooling systems
- DIY temperature-controlled projects
- Learning analog circuit design

## Acknowledgments
Designed and developed by **tidaschandoopasilva**, 2025.

---
Feel free to contribute or suggest improvements!
