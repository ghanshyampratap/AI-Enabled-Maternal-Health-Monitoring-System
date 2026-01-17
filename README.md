# Affordable AI-Enabled Health Monitoring System

## Overview

This project aims to revolutionize maternal healthcare by developing a low-cost, AI-enabled wearable health monitoring system for pregnant women.  
The device continuously monitors critical maternal and fetal health parameters and enables early detection of complications, especially in rural and underserved regions.


## Problem Statement

Existing maternal health monitoring solutions suffer from:

- High cost (₹30,000–₹40,000 range)
- Limited accessibility in rural and low-income areas
- Dependency on hospital infrastructure and skilled professionals
- Lack of continuous and remote monitoring


## Proposed Solution

We designed a portable, affordable, and AI-powered health monitoring device that:

- Continuously captures vital health parameters
- Uses AI-based anomaly detection
- Sends real-time alerts to doctors and caregivers
- Works both with and without internet connectivity

## Key Features

- Ultra-low cost  
  - ₹800 (without display)  
  - ₹1300 (with display)
- Wireless connectivity (Wi-Fi / Bluetooth)
- AI-based analytics for early risk prediction
- Emergency alerts via buzzer, LED, and mobile notifications
- Battery-powered and energy-efficient
- Suitable for remote and rural deployment


## Health Parameters Monitored

- Maternal heart rate  
- Blood oxygen level (SpO₂)  
- Body temperature  
- Fetal heart activity (indirect monitoring)


## Hardware Components Used

| Component | What it does |
|----------|--------------|
| ESP32 Development Board | Controls the system and sends data using Wi-Fi and Bluetooth |
| MAX30102 Pulse Oximeter | Measures heart rate and blood oxygen level (SpO₂) |
| Pulse Sensor (Finger Type) | Measures heart rate |
| 0.96" OLED Display (SSD1306, I2C) | Shows health data on the screen |
| Temperature Sensor (DS18B20 / LM35) | Measures body temperature |
| 3.7V Li-ion / Li-Po Battery | Provides power to the device |
| Battery Charging Module (TP4056) | Charges the battery safely |
| Buzzer / LED | Gives alert and status indication |
| Jumper Wires and Connectors | Used to connect all components |



## System Working

1. Sensors collect maternal and fetal health data  
2. ESP32 processes sensor data in real time  
3. AI algorithms analyze trends and detect anomalies  
4. Alerts are triggered if abnormal patterns are detected  
5. Data is transmitted to mobile applications, web dashboards, or hospital systems


## Project Images

![Prototype Image](https://github.com/user-attachments/assets/f748acc7-fef5-437b-85d9-32a855659dcf)  
![Prototype Image](https://github.com/user-attachments/assets/69267c8b-19ea-4e57-b5c9-a9c06b371a97)  
![Prototype Image](https://github.com/user-attachments/assets/20a27946-681b-4d53-a5fe-c0cfd3ecab5f)  
![Prototype Image](https://github.com/user-attachments/assets/43cf9e64-d4eb-4737-b4e6-887dbbbe013b3)  
![Prototype Image](https://github.com/user-attachments/assets/270dfc88-bd82-4e67-88ba-503f5cec28ae)



## Video Demonstration

Live working demonstration:  
https://drive.google.com/drive/folders/1-PxSylIRaWbKPORKo1JXeQCSKFr9Bfxv?usp=sharing


## Live Platform

Real-time sensor data and analytics can be accessed at:  
https://breaking-bad-frontend.vercel.app/


## Target Users

- Pregnant women, especially in rural and underserved areas  
- Hospitals and maternity clinics  
- Community health centers  
- NGOs working in maternal healthcare  
- Insurance and healthcare service providers


## Business Model

- Mass production and device sales  
- Hospital and NGO partnerships  
- AI software licensing and analytics services  
- Subscription-based remote monitoring


## Why This Project Stands Out

- Approximately 95% cost reduction compared to existing systems  
- Combination of AI and IoT for preventive healthcare  
- Portable, scalable, and locally manufacturable design  
- Addresses a real-world healthcare accessibility gap


## Future Enhancements

- Non-invasive glucose monitoring using a 940 nm infrared sensor  
- Advanced noise filtering using notch filters  
- Full ECG integration (AD8232)  
- AI-based pregnancy risk scoring  
- Expansion to support diabetic and high-risk patients


## Social Impact

This system enables early diagnosis, supports timely medical intervention, and contributes to reducing maternal mortality by providing affordable and accessible healthcare solutions.
