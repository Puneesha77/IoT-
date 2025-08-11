# 💧 IoT-Based Water Quality & Monitoring System

## 📖 About the Project
This project was inspired by the **growing number of chronic kidney disease (CKD) patients in Sri Lanka**, especially in rural areas where access to clean water is limited and often unmonitored.  

We aimed to create a system that **raises awareness** and **empowers individuals and authorities** to take proactive steps toward ensuring water safety — because **clean water is not a privilege, it's a right**.

---

## 💡 System Overview

### 🔹 **Home Tank Unit**
- **Sensors:** Ultrasonic + TDS
- **Function:** Monitors household water **level** and **purity**
- **Controller:** NodeMCU ESP8266
- **Connectivity:** Wi-Fi enabled for real-time cloud updates

### 🔹 **Resource Unit**
- **Sensors:** Flow + TDS
- **Function:** Analyzes common water sources for **flow rate**, **volume**, and **purity**
- **Additional:** Pump control for automated water management

---

## 🎯 Target Users
- **General Water Users**
  - Monitor their own water tank’s quality
  - Receive instant alerts on contamination or low water levels
- **Water Management Authorities**
  - View cross-location water data
  - Track feedback and usage trends for better decision-making

---

## 🛠 Tech Stack & Tools
- **Microcontroller:** NodeMCU ESP8266 / ESP32
- **Languages:** C, C++
- **Sensors:** Ultrasonic, TDS, Flow Sensor
- **Networking:** Wi-Fi
- **Cloud:** Rule-Based Access for IoT data management
- **Version Control:** Git / GitHub

---

## 📷 How It Works
1. **Data Collection**
   - Home Tank Unit measures water level & purity
   - Resource Unit measures source flow rate, volume, & purity
2. **Data Transmission**
   - Sensor readings sent to cloud in real-time
3. **Analysis & Alerts**
   - Cloud logic triggers alerts if purity falls below threshold
4. **Access**
   - Users and authorities can monitor via dashboards or alerts

---


