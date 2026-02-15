# ESPHome Tempur-Pedic Adjustable Bed Controller (TEB-100-R Compatible)

ESP32-based controller for Tempur-Pedic adjustable bed using ESPHome + Home Assistant.

## Features
- Independent head and legs control (cover entities)
- Presets: Flat, Preset 1, Preset 2
- Adjustable open/close duration (5–60 s)
- Mode selector dropdown
- Basic sensors (temperature, Wi-Fi, uptime, heap)

## Hardware
- ESP32 8-channel relay module (head up/down, legs up/down, 3 presets)
- TEB-100-R remote control

## Installation
1. Copy `secrets.yaml.example` → `secrets.yaml`
2. Fill in Wi-Fi and passwords

3. Flash via ESPHome

## Wiring
Connect relays to TEB-100-R compatible inputs (usually dry-contact simulation).
<img width="531" height="511" alt="Screenshot_3" src="https://github.com/user-attachments/assets/ebb07d14-35a2-4aad-b9ad-ffe4e016d534" />
