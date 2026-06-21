<img width="543" height="361" alt="bacc0d6e-f2c5-4d7f-82ed-fc5e846e303d" src="https://github.com/user-attachments/assets/14eb92f0-5c43-4ad4-95bd-882fd9af3217" />
# ECOLUME - Smart Solar Street Lighting System

🏆 Winner - 1st Place, ECE Department Hackathon

## Overview

ECOLUME is an intelligent solar-powered street lighting system designed to improve energy efficiency and road safety through sensor-driven automation.

The system utilizes an ESP32 microcontroller along with LDR, PIR, and rain sensors to dynamically control street-light brightness based on environmental conditions and pedestrian/vehicle movement.

---

## Features

- Solar-powered operation
- Automatic day/night detection
- Motion-based brightness control
- Rain and fog adaptive lighting
- Battery-powered backup operation
- Energy-efficient power management

---

## Hardware Components

- ESP32 Microcontroller
- Solar Panel
- TP4056 Charging Module
- 18650 Battery Pack
- LM2596 Buck Converter
- LDR Sensor
- PIR Sensor
- Rain Sensor
- IRFZ44N MOSFET Driver
- LED Street Light

---

## Working Principle

1. Solar panel charges the battery during daytime.
2. LDR sensor detects day/night conditions.
3. Street lights remain OFF during daytime.
4. At night:
   - No motion → DIM mode
   - Motion detected → FULL brightness
5. Rain/Fog detected → EXTRA brightness mode
6. ESP32 manages power and sensor processing.

---

## Achievement

🏆 1st Place - ECE Department Hackathon

---

## Team

Pragnya H Sulibhavi
Prakruthi M Rao
Niranjan D Chougula
Pooja K M
Namratha M
Nikhil Ravi Hosur
