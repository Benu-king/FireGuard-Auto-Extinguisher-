# 🔥 FireGuard Auto Extinguisher

**Author:** Benayas Wondwosen

**Category:** Embedded Systems • Robotics • Safety Automation

---

## 📌 Project Overview

FireGuard Auto Extinguisher is an Arduino-based automatic fire detection and suppression system. It scans an area using a servo motor, detects the strongest flame direction with a flame sensor, locks onto the fire position, and activates a water pump until the fire is extinguished.

This project is designed for learning, demonstrations, and small-scale safety automation systems.

---

## ⚙️ How It Works

1. The servo motor scans from 0° to 150°
2. The flame sensor reads analog values at each angle
3. The strongest flame direction is detected
4. The servo locks to that angle
5. The water pump turns ON while fire exists
6. Once the flame disappears, the pump turns OFF and the system resets

---

## 🧰 Components Required

* Arduino UNO / Nano
* Flame Sensor (Analog)
* Servo Motor (SG90 / MG90)
* Relay Module
* DC Water Pump
* External Power Supply
* Jumper Wires

---

## 🔌 Pin Configuration

| Component    | Arduino Pin |
| ------------ | ----------- |
| Flame Sensor | A0          |
| Servo Motor  | D9          |
| Relay Module | D10         |

---

## 🚀 Getting Started

1. Connect all components according to the pin configuration
2. Upload the Arduino code to your board
3. Open Serial Monitor (9600 baud) to verify startup
4. Introduce a flame to test detection and suppression

---

## 📁 Project Structure

```
FireGuard-Auto-Extinguisher/
│── FireGuard.ino
│── README.md
```

---

## 📜 License

Free for learning and personal use.

Commercial use requires permission from the author.

Credit must be given to **Benayas Wondwosen**.

---

## 🤝 Contribution

Contributions, improvements, and feature ideas are welcome.
Feel free to fork this repository and submit pull requests.

---

## 📞 Contact

* **Author:** Benayas Wondwosen
* **Company:** Nafiyas Solution

---

⭐ If you like this project, give it a star on GitHub!
