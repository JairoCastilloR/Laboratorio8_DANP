# Laboratorio 8 - DANP: IoT Connectivity with AWS and Sensor Data Visualization

## Description

Welcome to the "Laboratorio 8 - DANP" repository! This project focuses on the Internet of Things (IoT) connectivity, specifically on connecting IoT devices to the AWS cloud platform using MQTT (Message Queuing Telemetry Transport) protocol for subscribing and publishing data.

## Features

- **IoT Connectivity:** The project explores the connectivity of IoT devices to the AWS cloud using MQTT.
- **Secrets Management:** The "Secrets" module securely stores certificates like CA1 as cacert, privateKey, and client_cert, in addition to containing methods for connecting to a Wi-Fi network securely.
- **Sensor Data Collection:** The code uses three pins to connect a DHT11 temperature and humidity sensor and two pins for a resistor and a blue LED. Sensor data is collected and transmitted to the AWS server.
- **Data Processing:** The messageReceived method receive data from serialized JSON messages received from the server.
- **LED Intensity Control:** The project employs analogWrite to control the intensity of the blue LED. The map() function is used to convert a value from one range to another, and a maximum value of 100 is set to limit the LED intensity.

This project is an excellent resource for anyone interested in learning about IoT connectivity, AWS integration(lambda and iot core), and data visualization with sensors. Feel free to explore the code and adapt it for your own IoT projects!

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Set up the necessary hardware components (DHT11 sensor, resistor, blue LED) as indicated in the code.
4. Place the certificates in the "Secrets" module for secure connectivity.
5. Upload the code to your IoT device and run the application.

Feel free to reach out if you have any questions or need assistance with the setup.

Happy IoT hacking! 🚀
