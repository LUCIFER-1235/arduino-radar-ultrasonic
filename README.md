# 📡 Arduino Radar System using Ultrasonic Sensor

A real-time radar system built using **Arduino, Ultrasonic Sensor, and Servo Motor**, with a **Processing-based graphical interface** for live object detection and visualization.

---

## 📌 Overview

This project simulates a radar system by rotating an ultrasonic sensor using a servo motor to scan the surroundings. The detected object distance and angle are transmitted to a computer and visualized in real-time using a custom **Processing GUI**, mimicking an actual radar display.

---

## ⚙️ Features

*  Real-time object detection using ultrasonic sensor
*  180° scanning using servo motor
*  Live radar visualization using Processing
*  Angle-distance mapping system
*  Serial communication between Arduino and PC
*  Smooth and continuous scanning operation

---

## 🛠️ Tech Stack

* Arduino (UNO / Nano)
* Ultrasonic Sensor (HC-SR04)
* Servo Motor (SG90)
* Processing (for visualization)
* Embedded C (Arduino IDE)

---

## 🔧 Working Principle

The servo motor rotates the ultrasonic sensor from 0° to 180°, scanning the environment. At each angle, the sensor measures the distance of any object present.

This data (angle + distance) is sent via serial communication to the Processing application, which plots it in real-time on a radar-style interface.

The system continuously updates, creating a dynamic visualization of detected objects.

---

## 📊 Results

* Accurate object detection within sensor range
* Smooth scanning and real-time updates
* Clear radar visualization of object position
* Reliable serial communication with minimal delay

---

## 📌 Key Learnings

* Integration of hardware and software systems
* Real-time data acquisition and visualization
* Serial communication protocols
* Sensor-based environment mapping

---

## 🔮 Future Improvements

* 360° radar using rotating base
* LiDAR integration for higher accuracy
* Wireless data transmission (Bluetooth/WiFi)
* Object classification using AI

---
