# WaterFix WF001 Intelligent Booster Pump Controller Firmware

[![Firmware Version](https://img.shields.io/badge/Firmware-V2.54-brightgreen.svg)](https://github.com/omseven/wf001-firmware/releases/tag/WF001)
[![Model](https://img.shields.io/badge/Model-WaterFix_WF001-blue.svg)](https://elecmarketing.ir/product/waterfix-controller-wf001/)
[![Manufacturer](https://img.shields.io/badge/Manufacturer-ElecMarketing-orange.svg)](https://elecmarketing.ir/)

Official firmware distribution repository and Over-The-Air (OTA) update endpoint for the **WaterFix WF001 Intelligent Booster Pump & Soft-Start Controller** designed and manufactured by **ElecMarketing** (الکمارکتینگ).

---

## 📌 Product Overview

The **WaterFix WF001** is a cutting-edge, industrial smart booster pump controller equipped with built-in electronic **Soft-Start & Soft-Stop (سافت استارت)** technology, integrated digital power telemetry, analog/digital pressure sensing, and dual-pump automatic changeover. It eliminates severe hydraulic water-hammer shocks, extends pipeline and pump mechanical lifespan, and provides full remote telemetry via Wi-Fi and Modbus RTU/TCP.

🔗 **Official Product Page:** [https://elecmarketing.ir/product/waterfix-controller-wf001/](https://elecmarketing.ir/product/waterfix-controller-wf001/)

---

## ✨ Key Features & Technical Specifications

### ⚡ Built-in Soft-Start & Motor Drive
- **Integrated Electronic Soft-Starter:** Configurable acceleration ramp-up (ACC) and deceleration ramp-down (DCC) to eliminate mechanical shock and water hammer in plumbing networks.
- **Motor Power Support:** Single-phase pump motors from 0.37 kW up to 2.2 kW (0.5 HP to 3 HP).
- **Run Relay & Dual-Pump Architecture:** Multi-mode operation supporting single-pump soft-start, pressure-switch modes, and dual-pump alternate/master-slave changeover (Modes 1 to 4).

### 📊 Power Telemetry & Comprehensive Protections
- **Integrated High-Precision Energy & Power Metering:** Real-time monitoring of AC line voltage (V), active current (A), active power (kW), active energy (kWh), power factor ($\cos\phi$), and heatsink operating temperature (°C).
- **Under/Over Voltage Protection:** Digital line voltage window monitoring with programmable trip thresholds and auto-reset delays.
- **Dry-Run & No-Load Current Protection:** Accurate dry-running detection via current sensing without requiring external water probes.
- **Full-Load & Pipe Rupture Safety:** Automatic shutdown on continuous running without pressure buildup (valves closed or pipe bursts).
- **Expansion Tank Fault Warning (Anti-Rapid Cycling):** Detection and alerting for ruptured diaphragm tanks to prevent excessive motor cycling.
- **Over-Current / Thermal Overload Protection:** Fast hardware and software overcurrent cut-off with inverse-time characteristics.
- **Anti-Freeze Protection:** Automatic periodic circulation when ambient temperature drops below freezing threshold.

### 🎛️ Dual-Mode Pressure Sensing & Liquid Control
- **Analog Pressure Transducer Input (0–10 Bar):** Continuous pressure feedback with digital EWMA noise filtering, digital calibration offset, and independent Cut-In (P1) / Cut-Out (P2) thresholds.
- **Digital Pressure Switch Input:** Support for standard pressure switches with configurable on/off debounce delays.
- **Built-in & External Floater Support:** Direct electrode input for internal tank low/high water level detection + external multifunction float switches.
- **Multifunction Digital Inputs & Outputs (MFI / MFO):** Programmable auxiliary relays for cooling fan control, alarm beacons, system ready indicators, and reservoir auto-fill valves.

### 🌐 Smart Connectivity & Modern Web Dashboard
- **Glassmorphism Web Dashboard:** Fully responsive web application hosted on-board supporting live pressure gauges, power analytics, alarm logging, and full parameter configuration.
- **Fast In-App Radar Auto-Discovery:** Seamless discovery and control from the **ElecMarketing SmartHub App**.
- **Hardware Real-Time Clock (RTC):** Built-in RTC with 5-program weekly scheduling timers for pump operation and auxiliary relay automation.
- **OTA Firmware Updates:** Seamless Over-The-Air firmware updates with official `.efw` firmware packages.

---

## 🚀 Firmware Release & OTA Updates

This repository serves as the central endpoint for online and local OTA firmware distribution.

### Latest Release
- **Version:** `V2.54`
- **Release Tag:** [`WF001`](https://github.com/omseven/wf001-firmware/releases/tag/WF001)
- **Binary Image:** [`WaterFix_Controller.efw`](https://github.com/omseven/wf001-firmware/releases/download/WF001/WaterFix_Controller.efw)
- **Metadata JSON:** [`version.json`](https://raw.githubusercontent.com/omseven/wf001-firmware/main/version.json)

### OTA Update Instructions
1. Connect to the controller's Wi-Fi Access Point (e.g. `WaterFix_XXXXXX`) or local router network.
2. Open the Web Management Panel in your browser at `http://192.168.10.1` (or device assigned IP).
3. Go to the **تنظیمات (Settings)** tab.
4. Under **آپدیت آنلاین فریمور (Cloud Firmware Update)**, click **بررسی نسخه جدید (Check For Cloud Update)** to automatically download and flash the latest release.
5. Alternatively, upload the official `WaterFix_Controller.efw` file via **آپدیت لوکال فریمور (Local Firmware Update)**.

---

## 📚 Documentation & Downloads

| Document / Resource | Link |
| :--- | :--- |
| 📖 **User & Parameter Manual (دفترچه راهنمای پارامترها)** | [WaterFix Parameter Manual (PDF)](https://elecmarketing.ir/wp-content/uploads/2024/07/WaterFixParameter-WF001-v2.27-.pdf) |
| 📱 **Android SmartHub App (اپلیکیشن اسمارت‌هاب)** | [SmartHub App GitHub Repository](https://github.com/omseven/SmartHub_App) |
| 🌐 **Product Web Page (صفحه رسمی محصول)** | [WaterFix WF001 on ElecMarketing.ir](https://elecmarketing.ir/product/waterfix-controller-wf001/) |

---

## 🏢 Manufacturer & Support

- **Manufacturer:** [ElecMarketing (الکمارکتینگ)](https://elecmarketing.ir/)
- **Technical Support & Sales:** +98 (21) / +98 (912) Support Lines
- **Warranty:** 1-Year Full Replacement Warranty & 5-Year After-Sales Service
