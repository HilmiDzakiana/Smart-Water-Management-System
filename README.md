# Smart-Water-Management-System

## 📌 Overview

WaterWise is a smart water monitoring and irrigation system designed to support efficient and sustainable water management in river and agricultural areas, particularly regions prone to drought. The system integrates environmental sensors, microcontrollers, and IoT communication to enable real-time monitoring, automated irrigation control, and data-driven decision-making.

This project supports the Sleman Sembada initiative by improving water distribution efficiency and mitigating drought risks.

## 🎯 Objectives

Monitor environmental parameters related to drought and water availability

Automate irrigation systems based on predefined thresholds

Provide real-time data visualization through a web-based dashboard

Support sustainable and efficient water resource management

## 🧠 Key Features

### 📡 Real-Time Environmental Monitoring
Measures rainfall vibration, humidity, temperature, and water level.

### ⚙️ Automated Irrigation Control
Water pumps are activated or deactivated based on sensor data and control logic.

### 🌐 IoT-Based Communication
Data transmission using MQTT and HTTP protocols.

### 📊 Web-Based Dashboard
Visualizes sensor data for monitoring and analysis.

### 🚨 Emergency Shutdown Mode
Automatically disables the system under extreme environmental conditions.

## 🧩 System Architecture

Sensors → Arduino → Raspberry Pi → Database & Dashboard → Actuators

Sensors:

Piezoelectric Sensor (Rainfall vibration detection)

SHT20 Sensor (Humidity and temperature)

SRF05 Ultrasonic Sensor (Water level measurement)

## 🔧 Hardware Components

Arduino Uno

Raspberry Pi 3B+

Piezoelectric Sensor

SHT20 Humidity & Temperature Sensor

SRF05 Ultrasonic Sensor

Relay Module

Motor Driver

Water Pump

## 🖥️ Software & Technologies

Arduino IDE

Python

JavaScript

MQTT Protocol

HTTP & WebSocket

Local Database

Web Dashboard

## 🔄 System Workflow

Environmental sensors collect real-time data.

Arduino reads sensor values and transmits data to Raspberry Pi via USB.

Raspberry Pi processes and stores data in a local database.

Data is displayed on a web-based dashboard.

The system evaluates sensor data against predefined thresholds.

Water pumps are controlled via relay and motor driver modules.

In emergency conditions, the entire system is safely shut down.

## 🚀 Future Enhancements

Cloud-based database integration

Drought prediction using machine learning

Mobile application for monitoring and control

Water quality monitoring sensors integration

---
## 👤 Author
**Hilmi Dzakiana Maulidia**  
Bachelor of Engineering in Engineering Physics – Universitas Gadjah Mada  
Email: hilmi14dzakiana@gmail.com  
LinkedIn: [hilmidzakianamaulidia](https://www.linkedin.com/in/hilmidzakianamaulidia)
