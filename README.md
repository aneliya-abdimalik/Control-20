# CoNtrol-20

**Remote COVID-19 Symptom Monitoring System**

CoNtrol-20 is a low-cost, Arduino-based system for remote monitoring of clinical symptoms (temperature, heart rate, oxygen saturation) to reduce infection risks for medical personnel. Developed by students in Kazakhstan, the system integrates sensors, wireless data transmission, and real-time dashboards.

## 🔧 Features

- Real-time vitals tracking: temperature, SpO₂, heart rate
- Web & mobile dashboards for doctors
- Push alerts for abnormal patient conditions
- Firebase integration for user auth & notifications
- MySQL-based storage & PHP backend
- Bluetooth and/or Wi-Fi communication
- Tested and deployed in hospital pilot (Taraz, Kazakhstan)

## 🛠️ Hardware Components

- ESP32 or Arduino Nano
- IR Temperature Sensor (GY-906)
- Pulse Oximeter (MAX30100)
- OLED Display (128x64)
- TP4056 Charging Module
- Li-ion Battery (3.7V, 3000 mAh)
- HC-06 Bluetooth Module (or ESP32 Wi-Fi)
- 3D printed enclosure

## 🖥️ Software Stack

- Arduino (C++) for device firmware
- HTML, CSS, JavaScript for frontend
- PHP & MySQL for backend
- Firebase for authentication & push notifications
- Kodular for Android mobile app
