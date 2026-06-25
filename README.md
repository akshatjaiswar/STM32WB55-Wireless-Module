# STM32WB Custom Development Board

A custom STM32WB55-based wireless development board designed in KiCad. This project integrates USB Type-C power, SWD programming interface, RF front-end matching network, crystal oscillators, and onboard power regulation for Bluetooth Low Energy (BLE) and wireless embedded applications.

---

## Overview

This project demonstrates the complete hardware design of a custom STM32WB development board using KiCad.

The board includes:

- STM32WB55CEU6 Microcontroller
- USB Type-C Interface
- 3.3V Low Dropout (LDO) Regulator
- SWD Programming Header
- UART Debug Header
- RF Matching Network
- u.FL Antenna Connector
- 32 MHz High-Speed Crystal
- 32.768 kHz Low-Speed Crystal
- ESD Protection
- Reset Circuit
- Power Filtering & Decoupling Network

---

## Features

- STM32WB55 BLE MCU
- USB Type-C Power Input
- 5V → 3.3V LDO Power Supply
- SWD Debug Interface
- UART Debug Header
- RF Front-End with Matching Components
- u.FL Connector for External Antenna
- Boot0 Configuration
- User Push Button
- Status LED
- Multiple Decoupling Capacitors
- Crystal Oscillators for Accurate Timing

---

## Hardware Specifications

| Component | Description |
|-----------|-------------|
| MCU | STM32WB55CEU6 |
| Input Voltage | 5V (USB-C) |
| Operating Voltage | 3.3V |
| LDO | MIC5365-3.3 |
| Programming | SWD |
| Debug | UART |
| RF Connector | u.FL |
| HSE Crystal | 32 MHz |
| LSE Crystal | 32.768 kHz |
| USB Protection | ESD Protection IC |

---

## Design Software

- KiCad 9
- Schematic Capture
- PCB Design

---

## Project Structure

```
STM32WB-Development-Board/
│
├── Schematic/
│   └── stm32.kicad_sch
│
├── PCB/
│   └── stm32.kicad_pcb
│
├── Images/
│   └── Schematic.png
│
├── README.md
```

---

## Applications

- Bluetooth Low Energy (BLE)
- IoT Devices
- Embedded Systems
- Wireless Sensor Networks
- Home Automation
- Industrial Monitoring
- Wearable Electronics

---

## Learning Outcomes

This project improved my practical understanding of:

- STM32WB Hardware Design
- USB Type-C Interface Design
- RF Layout Fundamentals
- Power Supply Design
- Crystal Oscillator Circuits
- SWD Debug Interface
- Embedded PCB Design
- KiCad Schematic Design

---

## Author

**Akshat Jaiswar**

Electronics Engineering Student

Designed using **KiCad 9**
