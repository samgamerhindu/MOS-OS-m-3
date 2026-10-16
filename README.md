# ⚡ M³-OS (MOS)
> **One Board. Three Souls. Infinite Possibilities.**  
> *A modular, multi-personality operating system ecosystem for ESP32 hardware.*
<p align="center">
  <img src="assets/mos-banner.png" alt="M³-OS (MOS) Banner" width="100%">
</p>

<h1 align="center">⚡ M³-OS (MOS)</h1>
<p align="center"><b>One Board. Three Souls. Infinite Possibilities.</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Status-Under%20Development%2FConcept-orange?style=for-the-badge&logo=git" alt="Status">
  <img src="https://img.shields.io/badge/Platform-ESP32--WROOM-success?style=for-the-badge&logo=espressif" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License">
</p>
---

## 🌟 About the Project

**M³-OS (MOS)** is an open-source, modular embedded operating system ecosystem designed to give a single ESP32-WROOM microcontroller four distinct operational personalities. Built to bridge rapid Python prototyping with low-level C++ performance, MOS transforms ordinary hardware into a versatile development platform without needing multiple physical devices.

---

## 🧠 Meet the Four OS Variants

*   🧠 **MOS-Core (Real-Time MicroPython OS):** Engineered for industrial IoT, precise sensor logging, and concurrent task execution featuring a preemptive scheduler with a Zephyr-like API, threads, queues, and `asyncio`.
*   📱 **MOS-LCD (GUI-Focused MicroPython OS):** Tailored for handheld devices, smart appliance displays, and robot dashboards, enabling rapid touch and button UI creation in Python without writing C.
*   📺 **MOS-OLED (Compact Monochrome OS):** A lightweight sub-variant optimized for SSD1306 and SH1106 OLED screens, ideal for wearable widgets and low-power telemetry monitors.
*   🛡️ **MOS-Hack (Native C/C++ Security Toolkit):** Built on raw C++ for wireless reconnaissance, Wi-Fi penetration testing, Bluetooth scanning, BadUSB HID injection, and RF signal analysis.

---

## 🔌 Modular Ecosystem & Extensions

MOS goes beyond static firmware with a flexible modular architecture:
*   **Software Extensions:** Dynamic app modules, custom layouts, icon packs, and theme customization (optimized for MOS-LCD).
*   **Hardware Modules:** Plug-and-play support for expansion daughterboards, including Sub-GHz, LoRa, CC1101, and NRF24L01 radio modules.

---

## 🌐 Community & Collaboration

We are an open-source collective of embedded engineers, hardware hackers, Python developers, and cybersecurity enthusiasts building the future of modular ESP32 firmware. 

M³-OS is currently an **ambitious conceptual project in active early-stage development**. We are laying down the kernel architecture and developer toolchains, and we would love your help!

### How to Get Involved:
1. **Core Kernel & Drivers:** Help build the preemptive scheduler or optimize memory for MOS-OLED.
2. **UI & Apps:** Design themes, icon packs, and software extensions for MOS-LCD.
3. **Security & Radio:** Contribute to Wi-Fi/Bluetooth testing modules for MOS-Hack.
4. **Docs & Testing:** Write tutorials, wiring guides, and test builds across hardware revisions.

📬 **Want to join the project or collaborate?**  
Reach out directly to the project lead at **[hiremathsangamesh034@gmail.com](mailto:hiremathsangamesh034@gmail.com)**!

---

## 📜 License

This project is open-source under the terms of the [MIT License](LICENSE).
