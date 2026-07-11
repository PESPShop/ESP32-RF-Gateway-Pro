# ESP32-RF-Gateway-Pro

## Overview

ESP32 RF Gateway Pro is a web-based 433 MHz RF receiver and transmitter built around the ESP32.

It allows you to receive, analyze, save and retransmit RF signals directly from a web browser without reconnecting the ESP32 to a computer.

The firmware also includes WiFi provisioning, OTA firmware updates and configuration storage.

---

## Features

✔ Live RF Monitor (WebSocket)

✔ RF Signal Learning

✔ RF Replay

✔ Save Unlimited RF Codes (LittleFS)

✔ Search Saved Codes

✔ Delete / Edit Saved Codes

✔ Random RF Code Generator

✔ Backup & Restore

✔ WiFi Setup Portal

✔ OTA Firmware Updates

✔ Responsive Web Interface

---

## Hardware Requirements

- ESP32 Development Board
- 433 MHz RF Receiver Module
- 433 MHz RF Transmitter Module

Recommended modules:

- XY-MK-5V or SYN480 Receiver
- FS1000A or SYN115 Transmitter

---

## Default Pins

TX GPIO12

RX GPIO13

Status LED GPIO2

(These pins can be modified in config.h.)

---

## Installation

1. Install Arduino IDE.

2. Install required libraries.

3. Upload the firmware.

4. Upload LittleFS data (if applicable).

5. Connect to the temporary WiFi AP.

6. Configure your WiFi credentials.

7. Open the device IP address in your browser.

---

## Web Interface

The web interface allows you to:

- Monitor incoming RF signals
- Save RF codes
- Replay saved codes
- Send custom RF signals
- Export / Import backups
- Configure WiFi
- Perform OTA firmware updates

---

## Typical Applications

- RF Remote Learning
- RF Signal Analyzer
- Remote Control Backup
- Home Automation
- RF Device Testing
- Garage Door Remote Testing
- Smart Home Development

---

## License

This project is distributed as a commercial product.

Redistribution or resale is prohibited without written permission.
