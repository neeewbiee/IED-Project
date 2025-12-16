# Plant Monitoring Robot

This project was done as part of **IED Project 3 (Introduction to Engineering & Design)** at Singapore Polytechnic.

The project focuses on designing and building a **mobile plant monitoring robot** that monitors plant conditions such as soil moisture, temperature, and sunlight, and moves around to find a more suitable environment for plant growth.

---

## Problem Background

Due to climate change, urbanisation, and limited land space in Singapore, traditional farming and planting methods are becoming less efficient. Plants are often not monitored closely, which can lead to poor growth, wasted resources, and lower yields.

This project explores how a **robot-based plant monitoring system** can help improve plant care while saving space in urban environments.

---

## Project Overview

The plant monitoring robot carries a plant and uses multiple sensors to monitor environmental conditions.  
The robot is able to move autonomously, avoid obstacles, and display plant health data in real time.

Sensor data such as temperature, moisture, and sunlight are shown on an LCD.  
An optional Wi-Fi module allows data to be viewed on a mobile phone.

---

## Key Features

- Soil moisture monitoring  
- Temperature and humidity monitoring using DHT11  
- Sunlight detection  
- Obstacle detection using ultrasonic sensors  
- Autonomous movement using a 2WD robot chassis  
- LCD display for real-time plant condition  
- Optional Wi-Fi data transmission (ESP-01)  

---

## System Components

### Sensors
- Ultrasonic sensor – detects obstacles  
- Soil moisture sensor – measures moisture level of the plant  
- DHT11 sensor – measures temperature and humidity  
- Target sensor boards – detect sunlight and control display mode  

### Outputs
- LCD (I2C) – displays temperature, moisture, and sunlight  
- 2WD robot motors – movement of the robot  

### Controller
- Arduino microcontroller  

---

## Software Logic (Summary)

1. Robot starts and initialises all sensors  
2. Ultrasonic sensors check for obstacles  
3. Robot stops or changes direction if an obstacle is detected  
4. Light, temperature, and moisture levels are measured  
5. Sensor data is displayed on the LCD  
6. The process repeats continuously  

Flowcharts were used during development to design the control logic.

---

## Challenges Faced

- ESP-01 Wi-Fi module did not work reliably due to network restrictions in some locations  
- Ensuring stable wiring and component placement on a moving robot  
- Protecting electronic components from potential water exposure  

---

## Outcome

The robot was able to:
- Successfully monitor plant conditions using sensors  
- Move autonomously and avoid obstacles  
- Display real-time data clearly on the LCD  

This project demonstrated how basic robotics and sensors can be applied to support sustainable plant monitoring in urban environments.

---

## Possible Improvements

- Add a buzzer to alert users when plant conditions are not optimal  
- Implement a proper IoT dashboard for remote monitoring  
- Add data logging to store temperature and moisture values over time  
- Improve mechanical stability and waterproofing  

---

## Team Members

- Byran Tia – Team Leader / Software & Hardware  
- Jensen Pang – Software & Hardware  
- Ng Yong Liang – Software  
- Yap Ee Shen – Hardware  

---

## Demo Video
https://drive.google.com/file/d/1mHejnrdhH0yzjJ7VNtIsKPH9vrjTtYcs/view?usp=sharing
---

## Module Information

ET1015 / ET1024 – Introduction to Engineering & Design  
Singapore Polytechnic
