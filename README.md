# 🧵 UART Driver Implementation for RTEMS

This project is a UART (Universal Asynchronous Receiver/Transmitter) driver for a microcontroller in the RTEMS real-time operating system.

> 📌 **Project Type**: RTOS Driver Development | RTEMS  
> 🧠 **Skills Used**: C Programming, Embedded Systems, Interrupts, RTOS Concepts

---

## 📌 Overview

The objective is to implement a basic UART driver supporting:
- Initialization
- Transmit and receive functionality
- Interrupt handling
- Integration with RTEMS BSP (Board Support Package)

---

## 🎯 Why This Project?

UART is a fundamental protocol in embedded systems for debugging, communication with sensors, and connecting peripheral devices.

✅ Benefits:
- Adds UART support for specific microcontrollers in RTEMS  
- Enables easier development/debugging on embedded platforms  
- Helps beginners contribute meaningfully to RTEMS open source

---

## 🛠 Target Hardware (Example)

- ATmega328P (used in Arduino UNO)
- 8051 Microcontroller  
> You can port this driver to any microcontroller supported by RTEMS.

---

## 🔧 Features

- UART init with custom baud rate
- Transmit and receive characters
- Optional interrupt-based implementation
- Clean, reusable C code following RTEMS guidelines

---

## 📂 File Structure

RTEMS-UART-Driver/ ├── docs/ │ └── proposal.md ├── src/ │ └── uart_driver.c ├── tests/ │ └── uart_test.c ├── README.md

---

## 📄 Docs & Resources

- [`design_proposal.md`](./docs/proposal.md): Architecture and flow
- [`GSoC Proposal`](https://github.com/ANIDEEPCODE/RTEMS-UART-Driver/docs/Proposal.md): Full project plan for GSoC 2025
- RTEMS Development Guide: https://docs.rtems.org/

---

## 🚀 Future Goals

- Add circular buffer support
- DMA-based UART support (if MCU allows)
- Add example integration with RTEMS shell

---

## 🙋‍♂️ Author

**Damaraparapu Anideep**  
🔗 [GitHub](https://github.com/ANIDEEPCODE) | [LinkedIn](https://www.linkedin.com/in/damaraparapu-anideep-370638241)

---

⭐ *If this project helped or interested you, please give it a star!*

---

> 📝 *This repository was created as part of my [Google Summer of Code 2025](https://summerofcode.withgoogle.com/) proposal for RTEMS.*
