# HMI-Cluster-imxrt1170
Human-Machine Interface (HMI) cluster application for the NXP i.MX RT1170 microcontroller, featuring GUI implementation and display management via MCUXpresso. 

5 Screens - Home, Trip A, Trip B, Mileage and Service with state machine implemented to cycle and interacte with the screens.

## Overview
This repository contains the firmware and GUI application for a Human-Machine Interface (HMI) cluster developed for the NXP i.MX RT1170 microcontroller. This project was completed during an embedded software engineering internship at Niyata Infotech.

## Features
* **Hardware Target:** NXP i.MX RT1170 MCU
* **Development Environment:** MCUXpresso IDE
* **GUI Framework:** GUI Guider / LVGL (Light and Versatile Graphics Library)
* Custom hardware configuration including clock management, pin muxing, and DCD.

## Repository Structure
* `board/`: Hardware-specific configurations (clock, peripherals, pin muxing).
* `CMSIS/`: ARM Cortex-M7 core headers and compiler configurations.
* `component/`: Reusable software components such as the serial manager and UART adapters.
* `custom/`: Custom application code, GUI event handlers, and LVGL configuration extensions.

## Getting Started
1. Clone this repository.
2. Import the project into MCUXpresso IDE using the provided `.project` and `.cproject` files.
3. Build the project and flash it to the i.MX RT1170 evaluation board.
