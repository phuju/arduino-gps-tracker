# 🛰️ Arduino GPS Tracker

A simple Arduino-based GPS location reader using the TinyGPS++ library and a GPS module.  
It reads latitude and longitude data and outputs real-time location coordinates over Serial.

---

## 🔧 Features

- Reads GPS data using SoftwareSerial
- Parses NMEA sentences with TinyGPS++
- Outputs latitude and longitude with precision
- Simple and lightweight implementation

---

## 🧠 Hardware Used

- Arduino (Uno / Nano / compatible)
- GPS Module (e.g., NEO-6M)
- External antenna (optional)

---

## 🔌 Pin Connections

| GPS Module | Arduino |
|-----------|---------|
| TX | Pin 3 |
| RX | Pin 2 |
| VCC | 5V / 3.3V |
| GND | GND |

---

## 📡 Output Example
Latitude: 28.613939
Longitude: 77.209023

---

## 🚀 Why This Project

This project demonstrates:
- Serial communication in embedded systems
- GPS data handling and parsing
- Working with external sensor modules
- Real-time data acquisition
