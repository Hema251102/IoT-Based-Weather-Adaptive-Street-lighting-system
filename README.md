# IoT-Based Weather Adaptive Street Lighting System Using IBM Cloud, Node-RED, Python, and Wokwi

This repository provides the complete code and instructions to build an IoT-based weather-adaptive street lighting system. The system dynamically adjusts street lighting based on weather conditions and time of day using weather data from IoT sensors. It integrates IBM Cloud, Node-RED, Python, and Wokwi to process and visualize data in real time.

## Overview

The goal of this project is to create a smart street lighting system that adapts based on external weather conditions. The system:

1. Collects weather data (such as light intensity, temperature, and humidity) using IoT sensors.
2. Adjusts the street light brightness or turns the lights on/off according to the weather conditions.
3. Utilizes IBM Cloud services and Node-RED for data processing, storage, and visualization.
4. Provides real-time feedback and monitoring using a web-based interface.
5. Uses Wokwi for simulating the hardware and testing the system.

## Features

- **Weather-Based Adjustment:** Street lights adapt based on real-time weather data.
- **Smart Street Lighting Control:** Automatic on/off control and brightness adjustment based on weather conditions.
- **Cloud Integration:** Uses IBM Cloud for storing and processing sensor data.
- **Node-RED Integration:** Real-time processing and automation of data flow from IoT sensors.
- **Python Backend:** Data processing and logic implementation in Python.
- **Simulation with Wokwi:** IoT sensor simulation to test the system before hardware deployment.

## Prerequisites

Before running the system, ensure that you have the following:

- **IBM Cloud Account**: Set up an account on IBM Cloud for storing and processing data.
- **Node-RED**: IBM Cloud provides an instance of Node-RED for integrating IoT devices and managing workflows.
- **Python**: For backend processing and communication with IoT devices.
- **Wokwi**: An online IoT simulation platform to emulate hardware devices such as sensors and actuators.

### Installing Dependencies

1. **Node-RED**: Follow the instructions [here](https://nodered.org/docs/getting-started/) to set up Node-RED on IBM Cloud or locally.
2. **Python**: Install Python 3.x and the necessary libraries.
   
   Use the following command to install dependencies:

   ```bash
   pip install -r requirements.txt
