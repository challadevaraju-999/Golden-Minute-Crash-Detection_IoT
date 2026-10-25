# 🚑 Golden Minute: Vehicle Crash Detection & Zero-Network Dispatch

An IoT-driven emergency telemetry system designed to automate crash reporting during the golden hour, featuring dual-station hospital alert dispatch and zero-network LoRa failover.

**Built by Team: Quantum Coders**

---

## 🌟 Key Features
- **Accident & Rollover Detection:** Evaluates impact forces (>4g) and tilt angles (>60°) using MPU6050 IMU.
- **5-Step False Alarm Mitigation:** Features a 15-second driver abort override button ("I'm OK") with OLED countdown.
- **Dual Telemetry Dispatch:** Immediate automated cellular SMS with live Google Maps GPS coordinates and heart rate triage data.
- **Zero-Network Failover:** Automatically broadcasts long-range radio packets over 433 MHz LoRa (SX1278) when cellular coverage is unavailable.

---

## 🛠️ Hardware Stack
- **Microcontrollers:** ESP32 DevKit V1 (Vehicle Node & Base Station Node)
- **Sensors:** MPU6050 6-Axis Accelerometer/Gyro, NEO-6M GPS, MAX30102 Biosensor
- **Transceivers:** SIM800L / A7670C Cellular Modem, SX1278 LoRa 433 MHz Modules
- **Display & Audio:** 0.96" I2C OLED (SSD1306), Active Buzzer, Push Button

---

## 👥 Team: Quantum Coders
- Challa Devaraju & Team Members
- 
