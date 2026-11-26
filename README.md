# C3-Mini-Sensor-SGP40-Plug-n-Play


| Front View | Back View |
| :---: | :---: |
| ![GY-SGP40 Adapter Front View](./GY-SGP40%20Adapter%20Front%20View.png) | ![GY-SGP40 Adapter Back View](./GY-SGP40%20Adapter%20Back%20View.png) |


Carenuity plug-and-play adapter for the SGP40 Air Quality Sensor module.


# Overview

The SGP40 is a digital metal-oxide (MOx) gas sensor made by Sensirion for measuring volatile organic compounds (VOCs) in indoor air quality applications.

This PCB allows easy integration of the SGP40 VOC sensor into development platforms such as ESP8266 (D1 Mini), C3 Mini, and similar 3.3V microcontroller systems. 

The adapter carries a GY-SGP40 sensor module and plugs directly into the Carenuity headers, enabling rapid integration into IoT devices and environmental monitoring systems.

# Specifications 

| Parameter | Value |
| :--- | :--- |
| Sensor | Sensirion SGP40 (GY-SGP40 module) |
| Output | 	VOC Index (0 to 500) |
| Interface | 	I²C, fixed address 0x59 |
| Supply and logic level | 3.3V |
| Compatible boards | ESP8266 (D1 Mini), ESP32-C3 Mini, other 3.3V boards  |
| PCB Version | V1.2 |

# SGP40 Sensor Module Pins

| Pin | Description |
| :--- | :--- |
| VIN | 3.3V power|
| GND | Ground |
| SDA | I²C data |
| SCL | I²C clock  |

# Typical wiring

| SGP40 | ESP32-C3 Mini | ESP8266 D1 Mini |
| :--- | :--- | :--- |
| SDA | GPIO8| D2(GPIO4)| 
| SCL | GPIO10 | D1(GPIO5)|
| VIN | 3V3 | 3V3 |
| GND | GND  | GND  |

# File schematics
[GY-SGP40 Adapter Schematic](./GY-SGP40%20Adapter%20Schematic.pdf)

# Example usage 
SGP40 adapter with a C3 Mini and a 0.96" OLED showing a live VOC Index reading.
![SGP40 adapter with a C3 Mini and a 0.96" OLED showing a live VOC Index reading](./SGP40%20C3%20Mini%20OLED%20Display%20Example.jpeg)


# Applications 
- Indoor air monitoring
- Smart buildings
- HVAC automation
- Environmental IoT nodes
- Smart home systems

# Sensirion support files
[Sensirion SGP40 Datasheet](https://sensirion.com/media/documents/296373BB/6203C5DF/Sensirion_Gas_Sensors_Datasheet_SGP40.pdf)

# Example code 







