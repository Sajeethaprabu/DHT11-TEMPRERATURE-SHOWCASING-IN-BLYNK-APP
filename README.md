🌡 DHT11 Temperature & Humidity Monitoring using Blynk App
This project demonstrates how to read temperature and humidity data using the DHT11 sensor and display it in real-time on the Blynk IoT App using an ESP32 or ESP8266 microcontroller.

📱 Project Overview
With the help of the Blynk IoT platform, this project allows remote monitoring of environmental conditions like temperature and humidity. The values are collected from the DHT11 sensor and sent to the Blynk App over Wi-Fi using a microcontroller like ESP32 or NodeMCU (ESP8266).

🔧 Components Used
🔌 ESP32 or ESP8266 NodeMCU

🌡 DHT11 Temperature & Humidity Sensor

📱 Smartphone with Blynk App

🔌 Micro USB Cable

📶 Wi-Fi Network

🔗 Features
Real-time temperature and humidity data monitoring

Data displayed on a smartphone via Blynk

Simple and beginner-friendly project

Ideal for smart home or weather station applications

🛠 How It Works
The DHT11 sensor reads temperature and humidity from the environment.

The microcontroller sends this data to the Blynk IoT Cloud using Wi-Fi.

The data is displayed on the Blynk App through virtual pins.

You can view the data from anywhere in the world using your phone.

📲 Blynk App Setup
Install Blynk IoT app (Available on Android & iOS).

Create a new project and select ESP32 or ESP8266 as the device.

Add two widgets:

Gauge or Display widget for Temperature (Virtual Pin V0)

Gauge or Display widget for Humidity (Virtual Pin V1)

Copy the Auth Token from Blynk to your Arduino code.

📦 Future Enhancements
Add data logging features

Include alerts when temperature exceeds a limit

Upgrade to DHT22 for better accuracy
