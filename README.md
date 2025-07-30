# STM32H7 Dual-Core MCU Learning Project

This repository contains educational resources including videos, documents, and configuration examples for learning to develop with the **STM32H7 dual-core microcontrollers (Cortex-M7 + Cortex-M4)**.

![Board](https://www.st.com/bin/ecommerce/api/image.PF266503.en.feature-description-include-personalized-no-cpn-large.jpg)

## 📚 Project Overview

STM32H7 dual-core MCUs are powerful microcontrollers with two cores: a high-performance Cortex-M7 and a power-efficient Cortex-M4. Learning to develop with dual-core systems introduces concepts such as:

- Core-to-core communication (Inter-Processor Communication)
- Peripheral sharing and synchronization
- Power and clock configuration
- Boot sequence and startup modes
- RTOS vs bare-metal deployment per core

This project includes:
- 🎥 Tutorial videos (step-by-step)
- 📝 Technical documentation and diagrams
- ⚙️ STM32CubeIDE project files
- 📂 Source code examples for both cores
- 📌 Configuration tips and startup strategies

---

## 📁 Repository Structure

```bash
stm32h7-dualcore-learn/
│
├── Core/
│   ├── CM7/                # Code for Cortex-M7 core
│   └── CM4/                # Code for Cortex-M4 core
│
├── Docs/                   # PDF/Markdown documents and diagrams
│   ├── Boot_Process.pdf
│   └── InterCoreComm.md
│
├── Videos/                 # (Optional) Video thumbnails, scripts, or links
│
├── STM32CubeIDE_Project/   # Full project folder for STM32CubeIDE
│
├── README.md
└── LICENSE
