# 🔥 Basic Heater Control System – Embedded Systems Intern Assignment

Welcome to the repository for my Embedded Systems Intern Assignment at [upliance.ai](https://upliance.ai/)!  
This project demonstrates a **temperature-controlled heater system** built using the **ESP32 microcontroller**, **DHT22 sensor**, and a few essential peripherals.

---

## 📌 Project Overview

The goal of this assignment was to simulate a basic embedded system that controls a heater based on temperature thresholds.  
The system uses a digital temperature sensor to read ambient temperature and intelligently switches between five defined states:

- 🟡 **Idle** – System is inactive or cooled down
- 🔴 **Heating** – Temperature is below desired, heater is turned ON
- 🟠 **Stabilizing** – Approaching target temperature
- 🟢 **Target Reached** – Desired temperature achieved, heater turned OFF
- 🔥 **Overheat** – Temperature too high, buzzer alert

This system was designed and simulated using [Wokwi](https://wokwi.com/) and implemented in C++ using the Arduino framework.

---

## 🔧 Hardware Components (Simulated in Wokwi)

| Component     | Description                        |
|--------------|------------------------------------|
| ESP32         | Microcontroller for control logic |
| DHT22         | Digital Temperature Sensor        |
| LED           | Simulates Heater Status Indicator |
| Buzzer        | Alerts user in Overheat condition |

---

## 🧠 System Architecture

- Temperature is continuously read from the **DHT22 sensor**.
- Based on the measured temperature, a **state machine** controls the heater and system status.
- All actions and states are **logged in the Serial Monitor** for real-time debugging.
- In **Overheat** state, a **buzzer toggles repeatedly** to alert the user.
- Future upgrade possibilities include:
  - BLE state broadcasting
  - Multiple heating profiles
  - Overheat protection auto shutdown
  - Cloud logging

---

## 📁 Folder Structure

📦 basic-heater-indicator/
├── heater_control.ino # Main Arduino C++ Code
├── README.md # You're here!
└── design.pdf # Part 1 Design Document


---

## 🚀 How to Simulate

You can try this project right now using Wokwi – no hardware needed!

🔗 **Simulation Link:**  
[👉 Click to Open Wokwi](https://wokwi.com/projects/438608855860611073)

**What you'll see:**
- A DHT22 module
- Heater indicator (LED)
- Buzzer alert
- Serial monitor with real-time temperature and state logs

---

## 🔍 Features Implemented

- ✅ Real-time temperature tracking
- ✅ Five-state heater control logic
- ✅ Visual feedback (LED)
- ✅ Audible alert on overheat (buzzer blinking)
- ✅ Serial monitor logs
- ✅ Clean and modular Arduino code

---

## 🛠 Technologies Used

- **Language:** C++
- **Platform:** Arduino (ESP32)
- **Simulator:** [Wokwi](https://wokwi.com/)
- **Version Control:** Git & GitHub

---

## 💡 Future Roadmap

The system is designed for scalability and enhancement. Possible future additions:

- 🔗 BLE integration for mobile app updates
- 🌡️ Multiple heating profiles (e.g. Low, Medium, High)
- ☁️ Cloud data logging & analytics
- 🧠 AI-driven temperature prediction (aligned with upliance’s AI direction)

---

## 👨‍💻 Author

**Vikash Banwari**  
📧 [LinkedIn](https://www.linkedin.com/in/vikash-banwari/)  
🎓 Electronics and Communication Engineering Student  
💻 Passionate about embedded systems and real-world IoT automation

---

## 📄 Simution Links
- 💾 **Simulation on Wokwi:** [Click Here](https://wokwi.com/projects/438608855860611073)
- 📂 **GitHub Repository:** [github.com/vikash-banwari/basic-heaeter-indicator](https://github.com/vikash-banwari/basic-heaeter-indicator)

---

## 🙏 Acknowledgement

Special thanks to the upliance.ai team for this exciting opportunity to apply embedded skills in a practical, innovative context.  
Looking forward to pushing the boundaries of smart appliance design!

---
