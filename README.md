# Task-1-Nikhitha
# ESP32 Smart Environmental Monitor

## 📌 Project Overview

The ESP32 Smart Environmental Monitor is a simple IoT-based project that measures the surrounding temperature and humidity using an ESP32 and DHT22 sensor.

The sensor collects environmental data and the ESP32 processes and displays the readings through the Serial Monitor.

## 🛠️ Components Used

- ESP32 DevKit
- DHT22 Temperature and Humidity Sensor
- Wokwi Simulator

## 🔌 Circuit Connections

| DHT22 | ESP32 |
|-------|-------|
| VCC   | 3V3   |
| GND   | GND   |
| DATA  |GPIO 15|

## ⚙️ Working

1. The DHT22 sensor measures temperature and humidity.
2. The ESP32 reads the sensor values.
3. The readings are displayed on the Serial Monitor.
4. The system continuously updates the environmental readings.

## 📊 Sample Output

Temperature: 24 °C  
Humidity: 40 %

## 💻 Simulation

The project was designed and tested using the Wokwi ESP32 simulator.

## 📁 Project Files

- `sketch.ino` – ESP32 program code
- `diagram.json` – Wokwi circuit configuration
- `libraries.txt` – Required library information
- `wokwi-project.txt` – Wokwi project configuration

## 🎯 Objective

To develop a simple and low-cost system for monitoring environmental temperature and humidity using ESP32 and DHT22.

