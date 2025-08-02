# Smart Safety Device using GSM Module

# 📱 Smart Safety Device

A compact and real-time embedded system designed to enhance personal safety. It allows users to send an emergency SMS alert with just one button press using a GSM SIM800L module. The system provides feedback via an I2C 16x2 LCD display.

---

## 🔧 Key Features
- 📩 Sends instant **emergency SMS alerts** via GSM.
- 🧠 Powered by **Arduino Mega 2560** for reliable performance.
- 📟 **I2C LCD 16x2** used for status display (compact wiring).
- 🔘 Simple one-button interface for quick response.
- 💡 Ideal for **personal security and emergency communication**.

---

## 🧰 Hardware Components
| Component       | Description                  |
|----------------|------------------------------|
| Arduino Mega    | Main controller              |
| GSM SIM800L     | Sends SMS via mobile network |
| I2C LCD 16x2    | Displays system status       |
| Push Button     | Triggers emergency alert     |
| 3.7V Li-Po battery | 5V supply for GSM module  |
| Jumper Wires    | Circuit connections          |
| Power Supply    | 5V (regulated)               |

---

## 🔌 Wiring Overview

### 📟 I2C LCD Connections:
| I2C Pin | Arduino Mega |
|--------|---------------|
| VCC    | 5V            |
| GND    | GND           |
| SDA    | Pin 20        |
| SCL    | Pin 21        |

### 📡 GSM SIM800L Connections:
| GSM Pin | Arduino Mega |
|---------|--------------|
| VCC     | 5V (via AMS1117) |
| GND     | GND          |
| TX      | RX1 (Pin 19) |
| RX      | TX1 (Pin 18) |

