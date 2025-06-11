# 🔌 USB-C Voltage & Current Tester (RP2040 + OLED)

A USB-powered diagnostic tool that measures real-time voltage and current draw of any connected device. Designed in **KiCad**, driven by an **RP2040 microcontroller**, and visualized on a 0.96" OLED display.

## 🚀 Features
- USB-C power input
- Measures voltage via divider
- Measures current via shunt + op-amp (LM358)
- RP2040 MCU reads and displays values
- Compact 2-layer PCB, beginner-solderable

## 📦 Project Files
- `project.kicad_sch` — schematic
- `project.kicad_pcb` — board layout
- `gerbers/` — ready-to-fabricate output
- `README.md` — this doc

## 🖥️ Display
- 128x64 OLED using SSD1306 (I2C)
- SDA: GPIO0, SCL: GPIO1

## ⚙️ Future Enhancements
- USB-C PD measurement
- Onboard logging
- 3D-printed case

## 📸 Preview
![image](https://github.com/user-attachments/assets/4c6f6a98-ebbf-4788-bb59-dd48427f3cab)

## 🧑‍💻 Author
Designed by Akmal Nazir – May 2025  
MIT License
