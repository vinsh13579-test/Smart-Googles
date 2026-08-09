https://wokwi.com/projects/471868069744432129
# 🕶️ Smart Obstacle Detection Goggles (ESP32)

An IoT-based wearable device built to assist visually impaired individuals by scanning for incoming physical obstacles using ultrasonic acoustic tracking logic.

## 🚀 Features
* **Real-time Proximity Tracking:** Continually monitors distances using ultrasonic sound waves.
* **Variable Frequency Audio Alarm:** Beeps with distinct urgency patterns based on object proximity thresholds.
* **Compact Core Logic:** Powered by the robust ESP32 development board.

## ⚙️ Component Map
1. **ESP32 DevKit v4 Board** (Main processing unit)
2. **HC-SR04 Ultrasonic Distance Sensor** (Obstacle eye transceiver)
3. **5V Electronic Audio Buzzer** (Acoustic alert module)

## 📌 Distance Warning Zones
* **Safe Zone (> 100 cm):** Safe pathway. Buzzer remains completely silent.
* **Caution Zone (30 cm - 100 cm):** Moderate obstacle ahead. Slower pacing audio beep pulse.
* **Danger Zone (< 30 cm):** Immediate physical barrier detected. High-frequency continuous alert tones.

