# 🎯 Motion Classification for Tennis-Swing Analysis

This project demonstrates how to interface the MPU6050 6-axis accelerometer & gyroscope with the ESP8266 to collect motion data (pitch, roll, acceleration), visualize it, and build a machine learning model to classify motions or postures.


## 📦 Features

- 📡 Live pitch and roll computation
- 🔌 ESP8266 Webserver for data display
- 🧪 Sensor calibration and data collection
- 🧠 Machine Learning classification using recorded data
- 📊 Ready for integration into IoT dashboards or alert systems

---

## 🛠️ Hardware Requirements

| Component       | Details                          |
|----------------|----------------------------------|
| MPU6050         | Accelerometer + Gyroscope (I²C) |
| ESP8266 (NodeMCU) | Wi-Fi Microcontroller            |
| MAX30100        | Hear-rate sensor and Pulse Oximeter |
| Jumper Wires    | For I²C connection               |
| Breadboard      | Optional                         |


## 🔌 Wiring Guide

| MPU6050 Pin | ESP8266 Pin |
|-------------|-------------|
| VCC         | 3V3         |
| GND         | GND         |
| SDA         | D2 (GPIO4)  |
| SCL         | D1 (GPIO5)  |
