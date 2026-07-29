# 💧 Automated IoT Smart Water Meter

An IoT-enabled smart water metering system designed to modernize residential and utility-scale water management through real-time monitoring, automated billing, leak detection, and cloud-based data analytics. The system integrates a custom embedded hardware platform, GSM communication, cloud infrastructure, and web dashboards to improve billing accuracy, reduce Non-Revenue Water (NRW), and support the digital transformation of Sri Lanka's water distribution network.

---

# 📌 Overview

Traditional mechanical water meters rely on manual meter reading, making them susceptible to inaccurate billing, delayed data collection, water leakage, and high operational costs. Additionally, consumers and water authorities have limited visibility into real-time water consumption, making it difficult to identify leaks and abnormal usage patterns.

The **Automated IoT Smart Water Meter** addresses these challenges by combining low-power embedded hardware, wireless communication, cloud computing, and intuitive web applications into a complete smart metering ecosystem.

The system continuously measures water flow, securely transmits data to the cloud, automatically calculates water consumption, generates billing information, and provides real-time monitoring for both consumers and water utility providers.

---

# 🎯 Objectives

- Develop a low-cost IoT-enabled smart water meter
- Enable real-time water consumption monitoring
- Eliminate manual meter reading
- Automate water billing
- Reduce Non-Revenue Water (NRW)
- Detect leaks and abnormal consumption
- Provide centralized cloud-based monitoring
- Support future smart city infrastructure

---

# 🚰 Problem Statement

Sri Lanka continues to experience significant **Non-Revenue Water (NRW)** losses due to:

- Water leakage
- Manual meter reading
- Meter tampering
- Inaccurate billing
- Delayed data collection
- Lack of real-time monitoring
- High maintenance costs
- Limited consumer visibility

The proposed solution digitizes the entire water metering process while improving operational efficiency for both consumers and water authorities.

---

# 💡 Solution

The proposed system combines:

- Custom Embedded Hardware
- STM32 Low-Power Microcontroller
- Hall-Effect Flow Sensor
- GSM Communication
- Cloud Database
- Administrator Dashboard
- Consumer Web Portal

The smart meter continuously measures water flow, processes consumption locally, transmits data through GSM, stores information securely in the cloud, and presents live analytics through dedicated web dashboards.

---

# ✨ Key Features

## 💧 Smart Water Meter

- Real-time flow measurement
- Cumulative water consumption calculation
- Automated billing
- Leak detection
- Tamper-resistant monitoring
- Low-power operation
- Long battery life
- Remote monitoring

---

## 🌐 Cloud Platform

- Secure cloud database
- Historical data storage
- Live synchronization
- Consumption analytics
- Automated notifications
- REST API integration

---

## 👨‍💼 WaterboardOS (Administrator Dashboard)

- Network-wide monitoring
- Customer management
- Revenue analytics
- Water consumption statistics
- Historical usage trends
- Centralized administration
- Utility monitoring

---

## 👤 AquaSync (Consumer Dashboard)

- Real-time water usage
- Estimated monthly bill
- Historical consumption graphs
- Leak notifications
- Account management
- Previous billing history
- Live synchronization status

---

# ⚙️ Hardware Architecture

## Embedded System

- STM32L071CBT6 (ARM Cortex-M0+)
- SIM800L GSM Module
- Hall-Effect Flow Sensor
- Li-SOCl₂ Battery
- OLED Display
- RTC Crystal
- Low-Power Design

---

## Power Management

- TPS61023 Buck-Boost Converter
- XC6206 3.3V LDO Regulator
- Battery Protection Circuit
- Ultra-Low Power Sleep Mode

---

## Communication

- GSM/GPRS Communication
- HTTP POST Data Transmission
- Cloud Synchronization
- REST API Integration

---

# 🖥️ Software Stack

### Embedded Software

- Embedded C
- STM32CubeIDE
- Low-Power Firmware
- Pulse Counting
- Flow Calculation
- GSM Communication

### Web Technologies

- HTML5
- CSS3
- JavaScript

### Cloud

- Supabase
- REST APIs
- Cloud Database

---

# 📐 PCB Design

The complete hardware platform was designed as a custom **2-layer PCB** using **Altium Designer**.

The PCB includes:

- Power Subsystem
- STM32 MCU Subsystem
- GSM Communication Circuit
- Sensor Interface
- OLED Interface
- SWD Programming Interface
- Expansion GPIO Header

---

# 🛠 Mechanical Design

A custom waterproof enclosure was designed using **SolidWorks** for outdoor deployment.

Features include:

- Waterproof enclosure
- Standard plumbing connectors
- Optimized 9-blade turbine
- Hall sensor mounting
- PCB isolation
- Future expansion support

---

# 🧠 System Workflow

```text
Water Flow
     │
     ▼
Hall-Effect Sensor
     │
     ▼
STM32L0 MCU
     │
Flow Calculation
     │
     ▼
SIM800L GSM Module
     │
     ▼
Cloud Database (Supabase)
     │
     ▼
 ┌───────────────┬────────────────┐
 ▼                               ▼
WaterboardOS               AquaSync
(Admin Dashboard)      (Consumer Dashboard)
```

---

# 🔒 Security

- Secure cloud storage
- Unique meter identification
- Timestamped records
- Role-based authentication
- Secure API communication
- Centralized data management

---

# 📈 Benefits

### Consumers

- Live water usage monitoring
- Accurate billing
- Leak notifications
- Consumption history
- Better water conservation

### Water Utilities

- Reduced Non-Revenue Water
- Automated billing
- Reduced operational costs
- Remote monitoring
- Better maintenance planning
- Revenue analytics

---

# 🚀 Future Improvements

- NB-IoT Connectivity
- LoRaWAN Support
- Remote Valve Control
- AI-Based Leak Prediction
- Smart City Integration
- Mobile Application
- Predictive Maintenance
- Enterprise Cloud Infrastructure

---

# 👥 Team Excalibur

- A.H.T.M. Weerakoon
- K.D. Manatunga
- H.D.J.D. Samaranayaka
- W.M.H. Wanigasundara
- H.W.D. Prabarshana

---

# 👨‍💻 My Contributions

- Mechanical enclosure design using **SolidWorks**
- Electronic component selection
- Hardware integration
- System assembly and soldering
- Prototype testing and validation
- Performance evaluation
- Debugging and hardware verification

---

# 🎓 Academic Project

**Course:** EN2160 – Electronic Design Realization

**Department:** Electronic and Telecommunication Engineering

**University:** University of Moratuwa

---

# 📜 License

This project was developed for academic and research purposes as part of the EN2160 – Electronic Design Realization module at the University of Moratuwa.

---

