# solar-powered-offgrid-emergency-tracker
(GNSS & LoRa - Transmitter Module)
A solar-powered embedded wearable device designed for emergency location tracking in off-grid environments. The system uses GNSS for positioning and LoRa communication for long-range, low-power data transmission. Designed and validated through simulation with a focus on low-power and autonomous operation.

## Overview
This project presents a simulation-based solar-powered off-grid wearable emergency location tracker designed for use in areas without cellular connectivity. The system represents the transmitter side of an emergency tracking setup, where location data is obtained using GNSS and sent over long-range LoRa communication.

## Objective
To design an embedded wearable emergency location transmitter that can acquire GNSS coordinates and transmit them using low-power LoRa communication during emergency situations in off-grid environments.

##System Description

The simulated system acts as a wearable emergency transmitter. Upon user activation (trigger event), the device acquires location coordinates from a GNSS module (simulated) and prepares a location data packet intended for transmission via LoRa. The receiver side is not implemented in this simulation and is planned as future work.

## Tools
- Arduino IDE  
- ESP32 (simulated)  
- GNSS module (logic simulated)  
- LoRa communication (conceptual simulation)  
- Wokwi Simulator  
- Embedded C / Arduino framework  

## Project Status
Transmitter-side simulation completed using Wokwi. Receiver module implementation and real hardware validation are planned as future work.

## Future Scope
- Integration of real GNSS and LoRa modules  
- Solar charging optimization  
- Wearable enclosure design  
- Emergency alert transmission to rescue teams  

## Simulation Link
- Wokwi Simulation: [https://wokwi.com/](https://wokwi.com/projects/438873945378870273)

