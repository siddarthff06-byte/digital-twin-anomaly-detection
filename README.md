# Multi-Device Component-Level Digital Twin: AI-Driven Real-Time Anomaly Detection and Predictive Fault Isolation System for Smart Home Appliances

## Overview
This project builds a low-cost, real-time digital twin of a smart appliance's individual components (starting with a DC motor) using multi-sensor data (current, vibration, temperature). An AI model learns the appliance's normal operating behavior and detects anomalies at the component level, isolating faults as mechanical, electrical, or thermal — enabling predictive maintenance instead of reactive repair, at a fraction of the cost of industrial digital twin systems.

## Tech Stack
- **Hardware:** ESP32, ACS712 (current), MPU6050 (vibration), DS18B20 (temperature), L298N motor driver, DC motor
- **Simulation:** Wokwi
- **Communication:** MQTT (HiveMQ / Mosquitto)
- **AI/ML:** Python, scikit-learn (Isolation Forest)
- **PCB:** EasyEDA, JLCPCB (Phase 2)
- **Dashboard:** Grafana / custom web dashboard

## Project Status
🔨 In Progress — Breadboard prototyping phase (Week 1-2 of 5)

## Repository Structure
