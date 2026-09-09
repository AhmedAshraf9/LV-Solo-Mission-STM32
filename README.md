# Low Voltage Solo Mission — STM32 Milestones 1 & 2

## Overview

This repository contains my implementation of **Milestone 1** and **Milestone 2** of the STM32 project from the Low Voltage Individual Technical Mission.

The project uses the **STM32F103C8T6** microcontroller and was developed using:

- STM32CubeMX
- STM32 VS Code Extension
- STM32 HAL Drivers
- CMake

The mission defines:

- **Milestone 1:** Configure PC13 as a GPIO output and toggle an LED every 500 ms.
- **Milestone 2:** Read two analog signals using ADC1, scale them into Engine Temperature and Throttle Position, and transmit the results through USART1. 

---

# Repository Structure

```text
STM32-Milestones/
│
├── Milestone_1/
│   ├── Core/
│   ├── Drivers/
│   ├── cmake/
│   ├── ASURT.ioc
│   ├── CMakeLists.txt
│   ├── CMakePresets.json
│   ├── startup_stm32f103xb.s
│   └── STM32F103XX_FLASH.ld
│
├── Milestone_2/
│   ├── Core/
│   ├── Drivers/
│   ├── cmake/
│   ├── Milestone_2_ADC_UART.ioc
│   ├── CMakeLists.txt
│   ├── CMakePresets.json
│   ├── startup_stm32f103xb.s
│   └── STM32F103XX_FLASH.ld
│
└── README.md