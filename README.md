# IoT Smart Home Controller

ESP32-based home automation system with real-time sensor monitoring, relay control, and Android app interface.

**Capstone Project** | Sheridan College | Computer Engineering Technology | December 2025

---

## Features

- **Temperature & Humidity Monitoring** - DHT22 sensor with real-time data acquisition
- **Remote Relay Control** - 4-channel relay switching via mobile app
- **MQTT Communication** - HiveMQ cloud broker for low-latency bidirectional control
- **Android Application** - Kotlin-based interface for monitoring and control
- **Custom PCB Design** - Designed in Autodesk Fusion 360 Eagle, fabricated and assembled

---

## Hardware Progress

### Stage 1 - Core PCB Assembly ✓

- Multi layered PCB fabricated and assembled
- ESP32 DevKit integration with GPIO breakout
- DHT sensor interface for environmental monitoring
- Status LEDs with current-limiting resistors
- Power filtering capacitor for stable operation
- Continuity and functionality tests passed

---

## Tech Stack

| Category | Technologies |
|----------|-------------|
| Microcontroller | ESP32 (MicroPython) |
| Sensors | DHT22, PIR Motion Detector |
| Communication | MQTT, Wi-Fi |
| PCB Design | Autodesk Fusion 360 Eagle |
| Mobile App | Kotlin, Android Studio |
| Cloud | HiveMQ Broker |

---

## System Architecture
```
[Android App] <--MQTT--> [HiveMQ Cloud] <--MQTT--> [ESP32] --> [Relays/Sensors]
```

---

## Testing & Validation

- Validated sensor accuracy: **99%** using calibrated multimeter
- Verified MQTT message latency: **<500ms** round-trip
- Continuity testing on all PCB traces
- Load testing on relay circuits

---

## Author

**Aryan Prajapati**  
Computer Engineering Technology | Sheridan College  
[LinkedIn](https://www.linkedin.com/in/aryan-prajapati-5ab386262/) | [GitHub](https://github.com/Aryan-1912)
