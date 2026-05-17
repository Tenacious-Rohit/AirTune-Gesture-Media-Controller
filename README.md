# AirTune 🎵
### Gesture Controlled Bluetooth Media Controller using ESP32

![AirTune](setup.jpg)

## Overview

AirTune is a wireless gesture-controlled media controller built using ESP32, MPU6050, OLED display, and BLE HID technology.

The device allows users to control music playback through hand gestures.

---

## Features

- Bluetooth media control
- Gesture recognition using MPU6050
- OLED real-time display
- Volume control
- Track switching
- Play/Pause gesture
- Wireless BLE connectivity

---

## Components Used

- ESP32
- MPU6050
- SSD1306 OLED Display
- Buzzer
- Breadboard
- Jumper wires

---

## Gesture Controls

| Gesture | Action |
|----------|--------|
| Tilt Right | Volume Up |
| Tilt Left | Volume Down |
| Tilt Forward | Next Track |
| Tilt Backward | Previous Track |
| Shake | Play/Pause |

---

## Connections

### MPU6050
- VCC → 3.3V
- GND → GND
- SDA → GPIO21
- SCL → GPIO22

### OLED Display
- SDA → GPIO21
- SCL → GPIO22

### Buzzer
- Positive → GPIO27
- Negative → GND

---

## Technologies Used

- ESP32 BLE HID
- MPU6050 Motion Sensing
- Embedded C++
- Arduino Framework
- OLED UI Design

---

## Demo

Watch the project demo in the repository video.

---

## Future Improvements

- Wearable version
- AI gesture recognition
- Battery-powered system
- Custom gesture mapping
- 3D printed enclosure

---

## Author

Rohit
