# Wireless Power Transmission for Electric Vehicle (EV)

## Overview

The Wireless Power Transmission for Electric Vehicle (EV) system is a contactless charging solution that uses **Resonant Inductive Coupling** to transfer electrical power efficiently across an air gap. The prototype enables wireless energy transfer while continuously monitoring voltage and current in real time using an ESP8266 microcontroller.

---

## Features

- Contactless wireless power transmission
- Resonant inductive coupling technology
- Power transfer across a 5 cm air gap
- Real-time voltage monitoring
- Real-time current monitoring
- Low-cost embedded prototype

---

## Technologies Used

### Hardware
- ESP8266 NodeMCU
- Transmitter Coil
- Receiver Coil
- MOSFET Driver Circuit
- Voltage Sensor
- Current Sensor
- DC Power Supply

### Software
- Arduino IDE
- Embedded C
- Proteus

---

## Components Used

| Component | Purpose |
|----------|---------|
| ESP8266 NodeMCU | Controls the system and monitors electrical parameters |
| Transmitter Coil | Generates the magnetic field for wireless power transfer |
| Receiver Coil | Receives power from the transmitter coil |
| MOSFET Driver Circuit | Produces high-frequency switching signals |
| Voltage Sensor | Measures output voltage |
| Current Sensor | Measures output current |
| Capacitors | Maintain resonance for efficient power transfer |
| DC Power Supply | Supplies power to the transmitter circuit |
| Breadboard/PCB | Circuit assembly and prototyping |
| Connecting Wires | Electrical connections between components |

---

## Working Principle

The transmitter circuit generates a high-frequency alternating magnetic field using resonant inductive coupling. The receiver coil captures this magnetic field and converts it into electrical energy to power the load. The ESP8266 continuously monitors the output voltage and current, enabling real-time performance analysis of the wireless charging system.

---

## Results

- Successfully achieved wireless power transfer across a 5 cm air gap.
- Monitored voltage and current in real time using ESP8266.
- Demonstrated stable and efficient contactless power transmission.
- Developed a reliable prototype for EV wireless charging applications.

---

## Future Enhancements

- Increase wireless charging distance
- Improve power transfer efficiency
- Automatic coil alignment
- IoT-based remote monitoring
- Integration with Battery Management Systems (BMS)

---
