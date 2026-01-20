# PIR Sensor Motion Alarm (LED + Buzzer)

## 📌 Description
This Arduino project uses a **PIR motion sensor** to detect movement and activates an **LED and buzzer** as an alert. Motion events are also displayed on the **Serial Monitor** with timestamps.

## 🧰 Components Used
- Arduino Uno / Nano
- PIR Motion Sensor (HC-SR501)
- LED
- Buzzer
- Resistor
- Jumper wires
- Breadboard

## 🔌 Pin Connections
| Component | Arduino Pin |
|---------|------------|
| PIR OUT | D7 |
| LED | D5 |
| Buzzer | D6 |
| VCC | 5V |
| GND | GND |

## ⚙️ How It Works
- PIR sensor calibrates for 30 seconds
- When motion is detected:
  - LED turns ON
  - Buzzer sounds
  - Serial Monitor logs motion time
- When motion stops:
  - LED turns OFF
  - Buzzer stops

## 📟 Serial Monitor
- Baud rate: **9600**
- Displays:
  - Motion detected time
  - Motion ended time

## 🚀 How to Use
1. Connect the PIR sensor, LED, and buzzer
2. Upload `pirsensor_buzzerLED.ino`
3. Wait for PIR calibration
4. Move in front of the sensor to trigger alarm
