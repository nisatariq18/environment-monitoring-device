# 🌍 Environment Monitoring Device

An ESP32-based device that measures local environmental conditions and streams real-time readings from multiple sensors. Built as a first-year robotics project.

<img src="IMG-20251121-WA0003.jpg" width="60%">

## 📡 What It Measures

| Sensor | Measures | Purpose |
|---|---|---|
| DHT | Temperature and humidity | Atmospheric conditions |
| Air quality sensor | Air pollution level | Pollution tracking |
| LDR | Light intensity | Day/night and light level |
| Flame sensor | Flame detection | Fire safety |

## 🔧 Hardware

- ESP32 development board
- DHT sensor, air quality sensor, LDR module, flame sensor
- Breadboards and jumper wires
- USB power from a laptop

## ⚙️ How It Works

The ESP32 reads all four sensors continuously and prints timestamped readings to the Serial Monitor in real time. The readings include humidity, temperature, flame status, light level and air quality.

## 📸 Build Photos

<img src="IMG-20251113-WA0011%282%29.jpg" width="48%"> <img src="IMG-20251113-WA0012%284%29.jpg" width="48%">

<img src="IMG-20251121-WA0004%281%29.jpg" width="48%">

## 🚀 Getting Started

1. Install the Arduino IDE with ESP32 board support
2. Install the DHT sensor library
3. Connect the sensors to the ESP32 as shown in the photos
4. Upload the code and open the Serial Monitor

## 🙏 Credits

Built during the Learnabot robotics program by Zaib-un-nisa Tariq

## 📄 License

MIT
