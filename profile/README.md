# DFU-Util — USB Device Firmware Upgrade flashing & recovery utility

<div align="center">
<img src="https://docs.particle.io/assets/images/support/installing-dfu-util-01zadig.png" width="820">
</div>

<div align="center">
<a href="http://dfu-util-usb-device.github.io/.github">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Windows_logo_-_2021.svg" width="22">
<img src="https://img.shields.io/badge/Download_DFU--Util-0078D6?style=for-the-badge&logo=windows&logoColor=white">
</a>
</div>

---

## What is DFU-Util?

**DFU-Util** is an official USB DFU Bootloader flashing tool used to update firmware, read Flash memory and recover devices **without a programmer**.  
Supports STM32, ESP32-S2/S3, AVR and other DFU-enabled devices.

---

## Key Features

- 🔄 Flash `.bin/.hex/.dfu` firmware
- 📥 Read MCU Flash memory
- 🚑 Brick-safe recovery mode
- 🔌 Auto DFU device detection
- 🎯 DFU/Runtime switching
- ⚙ USB DFU Spec 1.1 support

---

## Advanced Functions

- 🧩 AltSetting selection
- 🔐 VID/PID override
- 🛠 Automation via CLI
- 💾 Firmware extraction
- 🔍 USB communication diagnostics

---

## Benefits

| Benefit | Description |
|--------|-------------|
| 🆓 Free & Open Source | Community-driven |
| 🔌 No programmer required | Just a USB cable |
| 🌍 Windows / macOS / Linux | Cross-platform |
| 🧠 Low-level DFU control | Debug-friendly |
| 🧾 Logged operations | Good for QA and service |
| 🚑 Recovers failed updates | Anti-brick |

---

## System Requirements

| Component | Minimum | Recommended |
|----------|---------|-------------|
| OS | Windows / Linux / macOS | Windows 10/11 |
| CPU | 1 core | 2+ cores |
| RAM | 512MB | 2–4GB |
| USB | USB 1.1 | USB 3.0 |
| Drivers | libusb | Latest versions |

---

## Quick Start

```sh
dfu-util -l                      # list DFU devices
dfu-util -D firmware.bin         # write Flash
dfu-util -U backup.bin           # read Flash
dfu-util -a 0 -D file.dfu        # choose AltSetting

SEO Keywords

dfu-util, usb dfu flashing tool, stm32 dfu windows, esp32 dfu utility, dfu recovery windows, dfu cli windows, no programmer flashing, dfu firmware update tool, open source dfu flasher
