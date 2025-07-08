# IoT-Based System for Preventing Underloading and Overloading of Railway Wagons

An IoT-enabled system to automate weight monitoring of railway wagons and reduce manual error.  
Uses load cells and HX711 modules to measure real-time weight, transmitting data via ESP8266 to a cloud dashboard.

## ✨ Features
- Real-time weight monitoring and visualization
- Categorizes wagons as underloaded, normal, or overloaded
- Planned Telegram Bot alerts for instant notifications
- Reduces manual checking and ensures compliance with railway safety guidelines

## 🛠 Technologies & Components
- ESP8266 microcontroller
- Load Cell sensors
- HX711 weight sensor modules
- LCD 16x2 display (I2C)
- ThingSpeak cloud platform
- (Planned) Telegram Bot integration

## 📦 How It Works
1. Load Cells measure wagon load
2. HX711 amplifies and digitizes the signal
3. ESP8266 transmits data to ThingSpeak
4. ThingSpeak dashboard displays weight status (underweight, normal, overweight)
5. (Future) Telegram Bot sends alerts

## 📷 Images & Diagrams
*(Add block diagram or screenshots here if available)*

## 📄 License
Open source under the MIT License
