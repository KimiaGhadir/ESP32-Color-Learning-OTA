# Color Detection and Learning System with ESP32

## Introduction
This project implements an embedded system based on the ESP32 that uses the TCS34725 color sensor to detect colors and supports learning new color samples. The model is trained on a Python server, and updated model versions are delivered to the device via Wi-Fi using OTA updates.

## Features
- I2C communication with the TCS34725 sensor
- Reading and processing color data
- Sending samples to the server for model training
- Generating and receiving TensorFlow Lite models
- Updating the model via OTA
- Real‑time color detection and display

## Tools and Technologies
- ESP32
- Embedded C
- Python
- TensorFlow Lite
- I2C
- HTTP
- OTA
