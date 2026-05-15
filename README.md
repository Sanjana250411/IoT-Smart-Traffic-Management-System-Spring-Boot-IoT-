🚦 Smart Traffic Management System (IoT + Spring Boot)
📌 Overview

This project is an IoT-based Smart Traffic Management System that dynamically controls traffic signals based on real-time vehicle density.
It uses ESP32 sensors to collect traffic data and a Spring Boot backend to process and manage traffic flow intelligently.

The system helps reduce congestion by automatically prioritizing the busiest lane.

⚙️ Tech Stack
🌐 Backend: Spring Boot (Java)
📡 IoT Device: ESP32 / Arduino
🔗 Communication: REST API (HTTP)
🎨 Frontend: HTML, JavaScript
🗄️ Optional: MySQL / Firebase (for extension)
🧠 How It Works
ESP32 reads traffic density using sensors (IR/ultrasonic)
Sensor data is sent to Spring Boot REST API
Backend processes data and finds the busiest lane
System decides which signal should turn GREEN
Frontend dashboard displays live traffic statu
