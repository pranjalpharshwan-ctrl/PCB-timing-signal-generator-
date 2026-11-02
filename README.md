# Timing Signal Generator PCB

A **Timing Signal Generator PCB** designed using **EasyEDA Pro**, featuring clock pulse generation, decade counting, BCD-to-decimal decoding, and LED-based decimal indication. The project includes the complete schematic, two-layer PCB layout, and Gerber files for manufacturing.

##  Project Overview

This project implements a digital timing and counting circuit using an NE555 timer, an SN74LS90 decade counter, an SN74LS42 BCD-to-decimal decoder, and an SN74HCT14 Schmitt-trigger inverter.

The circuit supports both automatic clock generation and manual clock input through a push-button circuit, selected using an AUTO/MANUAL switch. Ten LEDs indicate the decimal count from **0 to 9**.

##  Main Components

| Component | Description |
|---|---|
| NE555 Timer IC | Generates clock pulses in automatic mode |
| SN74LS90 | Decade counter that produces a 4-bit BCD output |
| SN74LS42 | Decodes BCD inputs into ten decimal outputs |
| SN74HCT14 | Schmitt-trigger inverter for signal conditioning |
| 10 × Red LEDs | Display the decimal count from 0 to 9 |
| Current-limiting resistors | Limit LED current |
| Resistors and capacitors | Timing and supporting circuit components |
| SPDT slide switch | Selects between AUTO and MANUAL modes |
| Tactile push button | Generates manual clock inputs |
| 5V power connector | Provides power to the circuit |

##  Working Principle

1. **Clock Generation:** The NE555 timer generates periodic clock pulses in automatic mode.
2. **Manual Clock Input:** An SN74HCT14-based push-button circuit provides conditioned clock signals for manual operation.
3. **Decade Counting:** The SN74LS90 counts the incoming clock pulses and generates a 4-bit BCD output.
4. **BCD Decoding:** The SN74LS42 decodes the BCD output into one of ten decimal outputs.
5. **LED Indication:** The corresponding LED indicates the current count, cycling through decimal values 0–9.
6. **Mode Selection:** An SPDT slide switch selects between automatic and manual clock operation.

##  PCB Specifications

- **EDA Software:** EasyEDA Pro V3.2.209
- **PCB Type:** Double-sided PCB
- **Number of Layers:** 2
- **Board Dimensions:** Approximately 102.1 mm × 65.7 mm
- **Operating Supply:** Regulated 5V DC
- **Design Rule Check (DRC):** Passed with zero reported issues under the configured rules
- **Manufacturing Output:** Gerber ZIP

## Repository Contents

The repository contains the design and manufacturing files associated with the project:

- **Schematic:** Circuit diagram and component connections
- **PCB Layout:** Two-layer PCB design
- **Gerber Files:** Manufacturing files exported from EasyEDA Pro


##  Design Status

- [x] Schematic design completed
- [x] PCB layout completed
- [x] DRC checks passed
- [x] Gerber files exported
- [x] PCB
- [x] <img width="1111" height="712" alt="image" src="https://github.com/user-attachments/assets/5e2da763-f29d-4a9d-bc30-83659694ae7f" />
<img width="1112" height="712" alt="image" src="https://github.com/user-attachments/assets/d01d098d-0990-4dc1-964b-223e92504ba9" />

## Author 

Pranjal Pharshwan
