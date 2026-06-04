# IoT Water Level Controller using ESP32

## Overview

This project presents an IoT-based Water Level Controller developed using the ESP32 microcontroller. The system continuously monitors the water level in a tank using an ultrasonic sensor and provides real-time updates through an OLED display.

The main objective of the project is to automate water level monitoring, reduce water wastage, and improve water management efficiency.

---

## Objectives

* Monitor water levels automatically
* Prevent water overflow
* Reduce water wastage
* Enable remote monitoring
* Improve water management efficiency

---

## Components Used

* ESP32 Dev Kit V1
* Ultrasonic Sensor
* 0.96" OLED Display
* BC547 NPN Transistor
* LED Indicator
* Push Button
* 220Ω Resistors
* 5V Buzzer
* Terminal Connectors

---

## Circuit Diagram

The circuit consists of an ESP32 microcontroller interfaced with an ultrasonic sensor for water level measurement, an OLED display for real-time monitoring, and a buzzer with LED indicators for alerts.

*(Circuit diagram uploaded separately in this repository.)*

---

## Working Principle

The ultrasonic sensor continuously measures the distance between the sensor and the water surface.

The ESP32 processes this data and calculates the current water level. The measured level is displayed on the OLED screen. When predefined water level thresholds are reached, the system activates visual and audio alerts using LEDs and a buzzer.

The ESP32 can also transmit data through Wi-Fi, making the system suitable for future IoT-based remote monitoring applications.

---

## Features

* Real-time water level monitoring
* ESP32-based control system
* OLED display interface
* Audio and visual alerts
* IoT-ready architecture
* Low-cost implementation

---

## Hardware Prototype

A working hardware prototype was developed using ESP32, ultrasonic sensing, OLED display, buzzer, and indicator LEDs.

*(Hardware image uploaded separately in this repository.)*

---

## Applications

* Residential Water Tanks
* Industrial Storage Tanks
* Irrigation Systems
* Water Conservation Projects
* Smart Water Management Systems

---

## Project Documentation

Detailed project report is available in this repository.

---

## Author

Lavanya Bawane

B.Tech Electronics & Telecommunication Engineering

St. Vincent Pallotti College of Engineering and Technology, Nagpur
