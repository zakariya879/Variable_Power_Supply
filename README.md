# Variable Power Supply

**An adjustable power supply for electronic devices, outputing from 0V to 15V.**

---

## Table of Contents

- [Key Features](#key-features)
- [Specifications](#specifications)
- [System Overview](#system-overview)
- [Hardware Design](#hardware-design)
- [Bill of Materials (BOM)](#bill-of-materials-bom)
- [Acknowledgments](#acknowledgments)

---

## Key Features

- **Precise Output Control:** Adjustable voltage and current limit, controlled via a potentiometer.
- **High Performance:** Delivers low output ripple and excellent load regulation.
- **Real-Time Monitoring:** Built-in voltage display for constant feedback.

---

## Specifications

| Parameter | Value |
| :--- | :--- |
| **Input Voltage** | 220V RMS |
| **Output Voltage** | 0-15V DC |

---

## System Overview

This power supply is built around a linear regulator architecture.

- **AC/DC Conversion:** A transformer steps down the mains voltage, which is then rectified and smoothed.
- **Regulation:** The core regulation is handled by a LM317T voltage regulator, providing stable output.

### Block Diagram

<img width="1123" height="794" alt="Block_Diagram" src="https://github.com/user-attachments/assets/49720766-512e-4f96-bf7d-a459bc789d7c" />


---

## Hardware Design

### Schematic and PCB
The complete schematic and PCB layout were designed using EasyEDA.

**Schematic**
<img width="996" height="708" alt="image" src="https://github.com/user-attachments/assets/a0b4c21e-a77a-4211-9083-556eb69e9d73" />

**PCB Layout**
<img width="2160" height="1079" alt="2D_PCB3_PowerSup_EasyEDA" src="https://github.com/user-attachments/assets/d0992505-63f3-4d44-bf73-548c0a25ff4e" />

**PCB 3D Render**
<img width="2160" height="1027" alt="3D_PCB3_PowerSup_3D_PNG" src="https://github.com/user-attachments/assets/3166b19b-559a-4c63-bc22-d9d0e8461700" />

---

## Bill of Materials (BOM)

| Component | Description | Quantity |
| :--- | :--- | :--- |
| **Transformer** | 220V to 16V Center Tap | 1 |
| **Voltage Regulator** | LM317T | 1 |
| **Full Bridge Rectifier** | 3A | 1 |
| **Bipolar Capacitor** | 2200uF | 1 |
| **Capacitor** | 330nF | 2 |
| **Diode** | 3A | 5 |
| **Resistor** | 500 Ohm | 1 |
| **Resistor** | 400 Ohm | 1 |
| **Resistor** | 1k Ohm | 1 |
| **Potentiometer** | 5k Ohm | 1 |

---

## Acknowledgments

This project was made possible by Ahmed Saleh, who contributed to the project from start to finish. Thank you for bringing the Variable Power Supply to life.

I hope this project can be a useful resource for anyone interested in power supplies!

