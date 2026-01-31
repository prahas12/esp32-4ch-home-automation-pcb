# 4-Channel Home Automation PCB using ESP32

This repository contains the hardware design files for a **4-channel home automation system based on ESP32**, designed for reliable and safe control of electrical appliances using Wi-Fi.

The project focuses on practical IoT hardware design, including relay isolation, opto-isolated inputs, and an onboard AC-to-DC power supply.

---

## 🔧 Features

- ESP32-based Wi-Fi control (Web Server & MQTT supported)
- 4-channel relay outputs for AC appliance control
- Opto-isolated inputs for safe external switch interfacing
- Onboard AC-to-DC power module (HLK-PM03 or equivalent)
- Compact 2-layer PCB suitable for enclosure mounting
- Status LEDs for power and relay indication

---

## ⚙️ Hardware Used

- ESP32-WROOM-32 (Wi-Fi + Bluetooth MCU)
- 4 × SPDT Relays (5V)
- Optocouplers for isolated switch inputs
- AC to DC power module (HLK-PM03 or equivalent)
- Screw terminals for AC loads and inputs
- Discrete driver transistors, resistors, and protection components

---

## 🛠️ PCB Design Details

- Designed using **KiCad**
- 2-layer PCB for cost efficiency
- Proper isolation between high-voltage (AC) and low-voltage (ESP32) sections
- Wide copper traces for relay current handling
- Through-hole components used where mechanical strength is required

---
