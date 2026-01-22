# U7800C Linear Regulator PCB Design
The 7800 series (78xx) is a family of three-terminal linear voltage regulators designed to provide a fixed, stable positive output voltage from a higher, unregulated input voltage
## Overview
This project is a PCB design of a linear voltage regulator based on the U7800C series.
The board provides a regulated DC output from a higher DC input and was designed
as a learning project to practice schematic capture, PCB layout, and power routing
fundamentals using KiCad.
## Specifications
- Regulator: U7800C (7805 variant)
- Input Voltage: 7 V – 20 V
- Output Voltage: 5 V
- Output Current: up to 1 A (with proper thermal dissipation)
- Package: TO-220
- PCB Layers: 2-layer
## Design Details
- Schematic implemented using the datasheet typical application circuit
- Input and output decoupling capacitors placed close to regulator pins
- Through-hole components selected for ease of assembly and learning
- Input and output screw terminal connectors for external wiring
## Files Included
- KiCad schematic and PCB files
- Gerber and drill files (fabrication-ready)
- Schematic and PCB layout screenshots
- Manufacturer datasheet
## Learning Objectives
- Reading and applying datasheet application circuits
- Selecting correct packages and footprints
- Understanding grounding and decoupling in linear regulators
- Converting schematic designs into manufacturable PCBs
## Status
✔ Completed  
✔ ERC/DRC clean  
✔ Ready for fabrication  
## Tools Used
- KiCad

