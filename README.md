# 2026 Vehicle Control Board
<img width="630" height="826" alt="image" src="https://github.com/user-attachments/assets/20562bef-f44f-40c3-88ad-6bab0abf0726" />

This repository contains the hardware documentation for the Vehicle Control Board (VCB) developed for our FSAE team. The board is based on an STM32F405 microcontroller and is designed to interface with sensors, actuators, and the driver interface for safe and reliable vehicle control.

##Features:
STM32F405 microcontroller running an RTOS for real time control
Integrated debugger using an STLINK-V3MODS
Integrated BSPD for further board consolidation
Pedal input interface for throttle pedal
Brake input via brake pressure sensor for braking indication
Steering angle input (I2C) from magnetic pot board in steering rack with LTC4311 for bus acceleration
2x CAN 2.0A interfaces for vehicle and inverter CAN buses
