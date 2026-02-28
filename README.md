# 🚦 Wireless Red/Green Signal Alert System for Trains

![Platform](https://img.shields.io/badge/Platform-Arduino%20Nano%20%2B%20Uno-blue)
![Communication](https://img.shields.io/badge/Communication-433MHz%20RF-green)
![Library](https://img.shields.io/badge/Library-VirtualWire-orange)
![Display](https://img.shields.io/badge/Display-16x2%20LCD-yellow)
![Motor Driver](https://img.shields.io/badge/Motor%20Driver-L293D%20%2F%20L298N-red)
![Application](https://img.shields.io/badge/Application-Train%20Signal%20Alert-success)

---

## 📌 Project Overview
This project demonstrates a Wireless Red/Green Signal Alert System for trains using Arduino Nano (TX) and Arduino Uno (RX) with 433 MHz RF modules. The system wirelessly transmits track signal status (RED/GREEN) to the train, displays it on a 16x2 LCD, and automatically controls a motor based on the received signal.

---

## 🛠 Hardware Used

### 🔹 Transmitter Side (Signal Post)
- Arduino Nano  
- 433 MHz RF Transmitter  
- Red & Green LEDs  
- 220Ω Resistors  

### 🔹 Receiver Side (Train)
- Arduino Uno  
- 433 MHz RF Receiver  
- 16x2 LCD Display  
- L293D / L298N Motor Driver  
- DC Motor  
- Optional Buzzer  

---

## 💻 Software & Tools
- Arduino IDE  
- Embedded C  
- VirtualWire Library  
- LiquidCrystal Library  

---

## ⚙ Key Features
- Wireless signal transmission (RED/GREEN)
- LCD-based signal display
- Automatic motor stop/go control
- Educational RF communication demo
