# Weather Reporting System using IOT
A top-tier IoT project, the Weather Report system provides localized forecasts, minimizing reliance on external agencies. Utilizing temperature, humidity, and rain sensors, the system reports real-time statistics online through the Internet. It also allows setting alerts—red, yellow, and green—to identify and warn of extreme events like volcanoes, tsunamis, heavy rainfall, ensuring timely responses to potential calamities
# IoT based Weather Reporting System

This is a simple Smart Weather Reporting system using **Raspberry Pi 4B+** and weather-related **sensors**. The system monitors and reports the weather parameters such as: Temperature,Humidity,Pressure, and gives alerts whenever it rains. We have also used [ThingSpeak Cloud](https://thingspeak.com/) platform for data collection and performed advanced data analysis using MATLAB and the [IFTTT](https://ifttt.com/) service to send alerts and notification.

## Installation

Use the package manager [sudo apt install](https://www.raspberrypi.org/documentation/) to install the necessary packages for Raspberry Pi.

```bash
sudo apt-get install python-smbus 
```
## Sensors
1. DHT11 Temperature Sensor
2. BMP180 Barometric Pressure Sensor
3. YL-83 Rain Sensor 
## Hardware Setup
![project setup](https://github.com/anu2a/Slash-Mark-Weather-reporting-system/assets/117003966/ce10541c-f269-4639-9801-cd5a53b6cba0)
