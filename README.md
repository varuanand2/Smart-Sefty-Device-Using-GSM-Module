# Smart Safety Device using GSM Module and GPS module

# 📱 Smart Safety Device

A real-time GPS and GSM-based safety device designed to send emergency alerts with **live location**. With a single press of a panic button, it sends an SMS containing Google Maps location link to a predefined phone number. The system provides user feedback via an I2C LCD.

---

## 🔧 Key Features
- 📩 Sends **emergency SMS with live location**.
- 📍 Integrated **GPS module** to track real-time position.
- 📡 Uses **GSM SIM800L** for communication.
- 📟 Status display via **I2C LCD 16x2**.
-🔢 **4x4 Keypad** to:
- Save 2 emergency contact numbers in EEPROM.
- Trigger SMS/call via ABCD keys.
- 🧠 Built on **Arduino Mega 2560**.

---

## 🧰 Hardware Components
| Component         | Description                             |
|------------------|-----------------------------------------|
| Arduino Mega 2560 | Main microcontroller                    |
| GSM SIM800L       | Sends SMS via mobile network            |
| GPS Module (NEO-6M) | Provides real-time location           |
| I2C LCD 16x2      | Displays device status                  |
| Push Button       | Triggers the emergency alert            |
| 3.7V Li-Po battery | 5V regulated power for GSM module      |
| Power Supply      | 5V (regulated)                          |
| 4x4 Keypad        | Input emergency contacts, trigger alert |
---

## 🔌 Wiring Overview

### 📟 I2C LCD:
| I2C Pin | Arduino Mega |
|--------|---------------|
| VCC    | 5V            |
| GND    | GND           |
| SDA    | Pin 20        |
| SCL    | Pin 21        |

### 📡 GSM SIM800L:
| GSM Pin | Arduino Mega |
|---------|--------------|
| VCC     |3.7V Li-Po battery |
| GND     | GND          |
| TX      | RX1 (Pin 19) |
| RX      | TX1 (Pin 18) |

### 📍 GPS Module (NEO-6M):
| GPS Pin | Arduino Mega |
|---------|--------------|
| VCC     | 5V           |
| GND     | GND          |
| TX      | RX2 (Pin 17) |


### 🔢 4x4 Keypad:
| Keypad Pin | Arduino Mega (Example) |
|------------|------------------------|
| R1–R4      | D22–D25                |
| C1–C4      | D26–D29                |

