# 🌆 Smart City Simulation using Cisco Packet Tracer

## 📌 Project Aim
To design and build an intelligent urban environment for city monitoring using Cisco Packet Tracer. This project integrates smart surveillance and intelligent street lighting that responds to environmental and sensor-based inputs.

---

## 🧠 Problem Statement
Traditional city infrastructure lacks automation and efficient resource usage. This project addresses:
- Continuous **surveillance** via IP camera.
- **Motion-based lighting** that activates only during nighttime.
- **Energy efficiency** by using sensors to minimize unnecessary light usage.

---

## 🔭 Scope of the Solution
- Use of motion sensors to detect activity on streets.
- Use of light sensors to differentiate day/night.
- Activation of streetlights **only** when motion is detected **at night**.
- IP Camera provides **24/7 video feed** to a connected device (e.g., tablet).
- Wireless communication between components using IoT protocol.

---

## 🏗️ Architecture Overview

### Devices Used:
- Motion Sensor (IoT)
- Photo Sensor (LDR equivalent)
- Street Lamps (LED outputs)
- IP Camera
- Home Gateway (IoT Router)
- Tablet PC (for video monitoring)

### Logic Flow:
1. **Photo Sensor** checks for ambient light.
2. If it’s **dark**, and **motion** is detected:
   - SBC turns ON the streetlight.
3. **IP Camera** streams continuously to a tablet over Wi-Fi.

---

## 🧰 Components Required
| Component          | Quantity |
|--------------------|----------|
| Motion Detector       | 1      |
| Siren                 | 1      |
| IP Camera             | 1      |
| Home Gateway          | 1      |
| Tablet PC             | 1      |

---




