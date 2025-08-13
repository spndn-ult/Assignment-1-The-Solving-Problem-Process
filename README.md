# Automated Pet Feeder Assignment

This repository contains the **step-by-step design, development, and testing** of an Automated Pet Feeder system.

The project was created for a local animal shelter and covers **problem analysis, data organisation, algorithm design, implementation in Arduino C++, and testing scenarios**.

---

## 📂 Folder Structure

- **Overall/**
  - Contains the **full combined document** with all steps in a single file.

- **Step_1_Analysis/**
  - Problem statement, goals, constraints, and system requirements.

- **Step_2_Data/**
  - Input/output descriptions, sensor and actuator details, and data tables.

- **Step_3_Algorithm/**
  - Pseudocode and logic flow for the automated feeder system.

- **Step_4_Code/**
  - Arduino C++ implementation code and explanation.

- **Step_5_Testing/**
  - Testing scenarios, expected outputs, results, and improvements.

---

## 🛠 Technologies & Components

- **Arduino UNO** (main controller)
- **Servo Motor** (food dispenser)
- **Load Cell + HX711 module** (weight sensing)
- **IR / Limit Switch Sensor** (food level detection)
- **16x2 LCD Display (I2C)** (status display)
- **Buzzer** (alert system)
- **RTC Module** (time tracking)

---

## 🚀 How to Use This Repository

1. **Read through each step folder** to understand the development process.
2. **Open Step_4_Code/** to find the Arduino code (`.ino` format) for running the project.
3. If you have the hardware, **assemble the components** as per Step 4 and Step 5 details.
4. **Test the system** using the sample scenarios provided.

---

## 📌 Notes

- The provided code is **tested in simulation**; real hardware calibration is needed.
- Improvements like Wi-Fi control or mobile notifications can be added in the future.
