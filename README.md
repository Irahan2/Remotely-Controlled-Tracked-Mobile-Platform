# 🚀 Remotely Controlled Tracked Mobile Platform   

## 📖 Overview  
This project is a remotely controlled tracked robotic platform built using **Arduino (ESP32)** and **Python**. The robot is controlled via a **WebSocket-based** communication system that allows users to operate it using keyboard inputs.  

### **Key Features**
✅ **Remote Control via Python** – Uses WebSockets to send commands.  
✅ **Arduino-Python Integration** – Communication between ESP32 and Python.  
✅ **DC Motor Control** – Uses RS775 motors for movement.  
✅ **Ultrasonic Sensor** – Detects obstacles and prevents collisions.  
✅ **Lightweight & Modular** – Expandable for future developments.  

---

## 🛠️ Technologies Used  
- **ESP32-WROOM-32** (Wi-Fi & Bluetooth-enabled microcontroller)  
- **Python** (WebSocket server & user control)  
- **Arduino IDE** (ESP32 programming & motor control)  
- **HC-SR04 Ultrasonic Sensor** (Obstacle detection)  
- **RS775 DC Motors** (For movement)  

---

## 🎯 **How It Works?**
1. The **Python script** establishes a WebSocket connection with the ESP32.  
2. The **ESP32 receives movement commands** (forward, backward, left, right) from the Python script.  
3. The **Arduino code** processes these commands and controls the DC motors.  
4. The **ultrasonic sensor** checks for obstacles and stops movement if needed.  

---

