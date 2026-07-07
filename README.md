# ⚡ IoT-Based Wireless Power Transmission for Electric Vehicle (EV)

## Overview

The IoT-Based Wireless Power Transmission for Electric Vehicle (EV) system is a smart contactless charging solution that uses **Resonant Inductive Coupling** to transfer electrical power wirelessly. The system integrates an **ESP8266** microcontroller for real-time voltage and current monitoring, enabling remote monitoring through IoT for improved efficiency and user convenience.

---

## Features

- Contactless wireless EV charging
- Resonant inductive power transmission
- Real-time voltage and current monitoring
- IoT-based remote monitoring using ESP8266
- Power transfer across a 5 cm air gap
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
- IoT Platform (Blynk / ThingSpeak)

---

## Components Used

| Component | Purpose |
|----------|---------|
| ESP8266 NodeMCU | Controls the system and enables IoT connectivity |
| Transmitter Coil | Generates the magnetic field for wireless power transfer |
| Receiver Coil | Receives wireless power from the transmitter |
| MOSFET Driver Circuit | Generates high-frequency switching signals |
| Voltage Sensor | Measures output voltage |
| Current Sensor | Measures output current |
| Capacitors | Maintain resonance for efficient power transfer |
| DC Power Supply | Supplies power to the transmitter circuit |
| Breadboard/PCB | Circuit assembly and prototyping |
| Connecting Wires | Electrical connections |

---

## Working Principle

The transmitter coil generates a high-frequency magnetic field using resonant inductive coupling. The receiver coil captures this magnetic field and converts it into electrical energy to power the load. The ESP8266 continuously measures voltage and current, uploads the data to an IoT platform, and enables users to monitor the charging process remotely in real time.

---

## Results

- Successfully achieved wireless power transmission across a 5 cm air gap.
- Monitored voltage and current in real time.
- Uploaded charging data to an IoT platform using ESP8266.
- Demonstrated an efficient and reliable contactless EV charging prototype.

---

## Applications

- Electric Vehicle Wireless Charging
- Smart Charging Stations
- IoT-Based Energy Monitoring
- Autonomous Vehicle Charging
- Smart Transportation Systems

---

## Future Enhancements

- Increase wireless charging distance
- Improve power transfer efficiency
- Automatic coil alignment
- Battery Management System (BMS) integration
- Mobile application for remote monitoring and notifications
- Cloud-based data analytics for charging performance

---
