# 🏎️ ESP32-CAM RC Car (Server)

This repository contains the firmware and hardware design for a Wi-Fi-controlled RC car. It uses an ESP32-CAM to stream live video and receive movement commands.

## 🚀 Features
* **Live Video:** Streams MJPEG video over a local web server.
* **Dual Motor Control:** Differential steering logic for 2WD/4WD chassis.
* **Compact Design:** Optimized for low-latency control.

## 🔌 Hardware Setup
* **Controller:** ESP32-CAM (AI-Thinker)
* **Motor Driver:** L298N Dual H-Bridge
* **Power:** 7.4V Li-ion battery (18650 cells)

### Pin Mapping
| Component | ESP32-CAM Pin |
| :--- | :--- |
| Motor Left (IN1/IN2) | GPIO 12 / GPIO 13 |
| Motor Right (IN3/IN4) | GPIO 14 / GPIO 15 |
| Flash LED | GPIO 4 |

## 🛠️ Installation
1. Clone this repo: `git clone https://github.com/nipun6480/ESP32-CAM-RC-Car.git`
2. Open `src/main.ino` in Arduino IDE.
3. Install the **ESP32** board manager and necessary libraries.
4. Upload to your ESP32-CAM.
