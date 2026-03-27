# ClearEye
Vision Assistance System using MLX90640, ESP32-S3 and Sensor Fusion
# 🔥 ClearEye - Vision Assistance System

ClearEye is a wearable embedded system designed to assist users in navigating environments with poor visibility such as smoke, fog, and darkness.

---

## 🚀 Features

- 🌡️ Thermal Imaging using MLX90640 (32×24)
- 📏 Obstacle Detection using ToF Sensor
- 🧭 Motion Tracking using MPU6050
- 📱 Mobile Display (No Internet Required)
- 🔔 Haptic Feedback System
- ⚡ Real-time Edge Processing

---

## 🧠 System Overview

The system uses multiple sensors to provide situational awareness:

- Thermal Sensor → Detects heat signatures
- ToF Sensor → Measures distance
- IMU → Tracks motion
- ESP32-S3 → Processes data

---

## 📸 System Architecture

![System Diagram](images/circuit.png)

---

## 🔥 Working

1. Thermal sensor captures heat data  
2. ESP32 generates heatmap  
3. ToF detects obstacles  
4. IMU stabilizes readings  
5. Output shown on display/mobile  
6. Haptic feedback alerts user  

---

## 📱 Mobile Interface

The ESP32 creates its own WiFi network.

- Connect mobile to ESP32 hotspot  
- Open browser → `192.168.4.1`  
- View live thermal heatmap  

---

## ⚙️ Hardware Used

- ESP32-S3  
- MLX90640 Thermal Sensor  
- VL53L0X ToF Sensor  
- MPU6050 IMU  
- TFT Display  
- Vibration Motors  

---

## 📊 Advantages

- Works without internet  
- Low cost  
- Portable  
- Real-time feedback  

---

## ⚠️ Limitations

- Limited resolution compared to high-end thermal cameras  
- Limited sensing range  
- Requires calibration  

---

## 🔮 Future Scope

- AI-based human detection  
- Friend vs foe classification  
- Mobile app development  
- Solar charging  

---

## 📂 Project Structure
