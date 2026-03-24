# 🛡️ PUMP-SENTRY S3 v1.0
### **Industrial-Grade IoT Submersible Pump Controller**
Developed by **Manoranjan Das** | [ElectroIoT.in](https://electroiot.in)

---

## 📖 Project Overview
The **PUMP-SENTRY S3** is a high-performance, ESP32-S3-based monitoring and protection system for single-phase submersible pumps. It prevents pump failure by monitoring electrical parameters in real-time and providing intelligent **Dry-Run Protection**.

### ✨ Key Features
* **Dual-Core Intelligence:** Powered by **ESP32-S3-N8R8** for robust WiFi and processing.
* **Precision Monitoring:** Integrated **PZEM-004T** for Voltage, Current, Power, and Energy tracking.
* **Safety First:** Optoisolated relay drivers and physical PCB isolation slots for 230V safety.
* **Local Interface:** **16x2 I2C LCD** for live data and **SK6812 RGB LED** for status alerts.
* **Manual Control:** Dedicated **Physical Start/Stop buttons** for offline operation.

---

## 🖼️ Gallery & Design
| 3D Top View | PCB Layout |
| :---: | :---: |
| ![Top View](https://raw.githubusercontent.com/your-username/pump-sentry-s3/main/images/3d_top.jpg) | ![PCB View](https://raw.githubusercontent.com/your-username/pump-sentry-s3/main/images/pcb_layout.jpg) |

---

## 📥 Download Resources

| Resource | Action |
| :--- | :--- |
| **📦 Gerber Files** | [🚀 Download v1.0 Ready-to-Order](#) |
| **📐 Schematic (PDF)** | [📄 View Schematic](https://github.com/your-username/pump-sentry-s3/blob/main/documents/schematic.pdf) |
| **💻 ESPHome Firmware** | [🛠️ Copy YAML Code](https://github.com/your-username/pump-sentry-s3/blob/main/firmware/pump_sentry.yaml) |
| **📦 BOM (Parts List)** | [📝 View LCSC Part List](#) |

---

## 🛠️ Technical Specifications
* **MCU:** ESP32-S3-WROOM-1-N8R8 (8MB Flash/8MB PSRAM).
* **Power Supply:** HLK-5M05 (AC 230V to DC 5V 1A).
* **Voltage Regulator:** SGM2212-3.3XKC3G/TR (High-efficiency 3.3V LDO).
* **Relays:** 2x SRD-05VDC-SL-C (Start/Stop Control).
* **Communication:** USB-C Native Serial & UART for PZEM.

---

## 🚀 Installation & Pins
| Component | Pin (GPIO) | Mode |
| :--- | :--- | :--- |
| **Start Relay** | GPIO 10 | Output (Active Low) |
| **Stop Relay** | GPIO 11 | Output (Active Low) |
| **Start Button**| GPIO 12 | Input (Pull-up) |
| **Stop Button** | GPIO 13 | Input (Pull-up) |
| **LCD (SDA/SCL)**| GPIO 8 / 9| I2C Communication |
| **RGB LED** | GPIO 48 | One-Wire Data |

---

## 👨‍💻 Developed By
**Manoranjan Das**
*Computer Science Engineer & IoT Developer*

* **GitHub:** [@manoranjan](https://github.com/manoranjan2050)
* **Website:** [electroiot.in](https://electroiot.in)
* **YouTube:** [Electroiot-IN](https://youtube.com/Electroiot-IN)
* **Email:** [electroiot.in@gmail.com](mailto:electroiot.in@gmail.com)

---

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify for your DIY projects!

---
*Created for the DIY Community at Dengapol Bazar, Jagatsinghpur, Odisha.*