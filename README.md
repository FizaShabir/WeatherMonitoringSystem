# Smart Weather Monitoring and Alert System using Arduino and IoT

## Introduction
This project aims to develop an advanced weather monitoring system using Arduino, Tinkercad for simulation, and IoT for remote data access. The system will collect real-time weather data, including temperature, humidity, atmospheric pressure, and air quality, and display the data on an LCD screen and a web-based dashboard. Additionally, it will send automated alerts via email or SMS when extreme weather conditions are detected.

## Objectives
- Design and simulate a weather monitoring system using Arduino and Tinkercad.
- Measure temperature, humidity, atmospheric pressure, and air quality.
- Display real-time data on an LCD screen and send data to a cloud database.
- Trigger alerts via a buzzer and LED indicators when predefined thresholds are exceeded.
- Integrate IoT (ESP8266) for remote monitoring via a web dashboard.
- Log weather data on a cloud server for future analysis.

## Components Required
### Microcontroller
- Arduino Uno

### Sensors
- DHT22 (Temperature & Humidity)
- BMP280 (Pressure Sensor)
- MQ-135 (Air Quality Sensor)

### Display Modules
- 16x2 LCD Display with I2C
- OLED Display (Optional)

### Communication Module
- ESP8266 Wi-Fi Module

### Alert System
- Buzzer
- LED (Red, Yellow, Green)

### Power Supply & Miscellaneous
- Resistors (220Ω)
- Breadboard & Jumper Wires
- Cloud Storage (Firebase, Thingspeak, or Blynk)

## Working Principle
### Data Collection
- Sensors collect temperature, humidity, pressure, and air quality data.

### Data Processing
- The Arduino processes the data and displays it on an LCD screen.

### IoT Integration
- The ESP8266 module sends real-time data to a cloud database.

### Alert System
- If temperature or humidity exceeds predefined thresholds, a buzzer and LED alert system are triggered.
- If air quality drops below a safe level, a warning notification is sent to the web dashboard.

### Web-Based Dashboard
- Users can access real-time weather data from any location via a cloud-hosted web page.

### Data Logging
- All sensor readings are stored in the cloud for future analysis and pattern detection.

## Circuit Design in Tinkercad
1. Connect the DHT22, BMP280, and MQ-135 sensors to the Arduino.
2. Interface the LCD display with an I2C module for easy communication.
3. Connect the ESP8266 module to the Arduino for cloud communication.
4. Set up the buzzer and LED indicators for alerts.
5. Simulate the circuit in Tinkercad before implementing it in a real-world scenario.

## Expected Outcome
- A fully functional smart weather monitoring system with cloud-based data logging.
- Real-time weather data displayed on an LCD screen and a web dashboard.
- IoT-enabled remote access to weather data from anywhere.
- Automatic alerts for extreme weather conditions.
- Historical data storage for weather trend analysis.

## Future Enhancements
- Integration with AI for predictive weather forecasting.
- Mobile app development for real-time notifications.
- Solar-powered system for remote applications.
- Addition of a rain sensor and wind speed sensor for comprehensive monitoring.

## How to Use
1. Set up the hardware components as per the circuit diagram.
2. Program the Arduino with the provided code.
3. Connect the ESP8266 module to the Wi-Fi network.
4. Monitor real-time data on the LCD and web dashboard.
5. Receive alerts when predefined thresholds are exceeded.

## License
This project is open-source and available under the MIT License.
