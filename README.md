# Smart Multi-Source Water Purification System

## 📌 Overview

The **Smart Multi-Source Water Purification System** is a proposed automated water purification and classification system designed to handle water from different natural sources. The system identifies the characteristics of incoming water using **pH, TDS, and turbidity sensors** and selects an appropriate purification pathway based on the detected water quality.

The system integrates **automatic source classification, intelligent filtration, ceramic-based salt removal, closed-loop recirculation, and pH control** into a single platform.

---

## 🎯 Objectives

- Automatically classify water based on its quality parameters.
- Reduce manual intervention in the purification process.
- Select suitable purification processes according to the detected water characteristics.
- Integrate multiple purification stages into a single automated system.
- Continuously monitor input and output water quality.

---

## ⚙️ System Working

The proposed system follows the following workflow:

**Water Input → Quality Sensing → Source Classification → Purification Path Selection → Filtration → Ceramic-Based Salt Removal → Recirculation → pH Control → Output Water Monitoring**

The incoming water is first analyzed using **pH, TDS, and turbidity sensors**. Based on the measured parameters, the system classifies the water and determines the appropriate purification pathway.

After purification, the output water is monitored again to evaluate the change in water-quality parameters.

---

## 🔧 Hardware Components

- Raspberry Pi 4 Model B
- ADS1115 ADC
- pH Sensor
- TDS Sensor
- Turbidity Sensor
- I2C LCD Display
- Solenoid Valves
- Water Pump
- Ceramic-Based Salt Removal Unit
- pH Control System
- Power Supply

---

## 💻 Software & Technologies

- **Python**
- **Raspberry Pi**
- **I2C Communication**
- **ADS1115 ADC**
- Sensor Data Acquisition
- Automated Process Control
- Water Quality Classification

---

## 🌊 Water Quality Parameters

The system primarily considers:

| Parameter | Purpose |
|---|---|
| **pH** | Determines acidity/alkalinity |
| **TDS (ppm)** | Indicates dissolved solids |
| **Turbidity (NTU)** | Indicates suspended particles/cloudiness |

These parameters are used for water-source classification and purification-path selection.

---

## 💡 Key Features

- Multi-source water classification
- Automatic purification-path selection
- Real-time water quality monitoring
- Ceramic-based salt removal
- Closed-loop recirculation
- Automatic valve control
- pH monitoring and control
- Input and output quality comparison

---

## 🚀 Novelty

The project combines **water-source classification and automated purification** within a single system. Its proposed novelty includes:

1. Microprocessor-based multi-source water purification
2. Automatic water-source identification
3. Intelligent purification-path selection
4. Dual-stage water-quality monitoring
5. Closed-loop recirculation
6. Ceramic-based salt removal
7. Self-cleaning mechanism for ceramic-based treatment
8. Integrated pH control

---

## 📂 Project Structure

```text
Smart-Multi-Source-Water-Purification/
│
├── README.md
├── src/
│   ├── main.py
│   ├── sensor_reading.py
│   ├── water_classification.py
│   └── valve_control.py
│
├── hardware/
│   ├── circuit_diagram/
│   └── component_list/
│
├── documentation/
│   ├── project_report/
│   └── diagrams/
│
└── images/
    └── prototype/
