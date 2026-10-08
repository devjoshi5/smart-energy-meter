# Smart Energy Meter ⚡

IoT-based energy meter that measures voltage and current, computes power and consumption, and shows live data on a Blynk dashboard, with ESP32-CAM surveillance.

## Features
- Current sensing with SCT-013 and voltage sensing with ZMPT101B
- Live monitoring on the Blynk app
- Surveillance with ESP32-CAM

## Hardware
| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller, Wi-Fi |
| SCT-013 | Non-invasive current sensor |
| ZMPT101B | Voltage sensor module |
| ESP32-CAM | Surveillance |

## Architecture
Sensors → ESP32 (ADC sampling, RMS calculation) → Wi-Fi → Blynk Cloud → Mobile dashboard

## Setup
1. Install Arduino IDE and the ESP32 board package
2. Install libraries: [Blynk, EmonLib, ...]
3. Copy `config.example.h` to `config.h` and add your Blynk auth token and Wi-Fi details
4. Upload `src/main.ino`

## Results
![Dashboard](<img width="625" height="1037" alt="image" src="https://github.com/user-attachments/assets/faf2665d-f57f-403a-8149-395b29203ad8" />
)
![Hardware](<img width="1280" height="730" alt="WhatsApp Image 2026-08-02 at 10 33 02 AM" src="https://github.com/user-attachments/assets/a33c92dc-ee47-4107-8174-be5368648166" />
)


*Developed Dec 2024 to May 2025 as my B.Tech final-year project.*
