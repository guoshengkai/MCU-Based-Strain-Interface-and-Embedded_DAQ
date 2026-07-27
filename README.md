<img width="4796" height="5017" alt="Hardware signal chain and single-channel strain amplifier (a) system block diagram, (b) circuit schematic" src="https://github.com/user-attachments/assets/e3900bb1-69e8-4fa9-a503-231fe71aa835" />

# MCU-Based-Strain-Interface-and-Embedded_DAQ
This project demonstrates a STM32-based embedded strain sensing system integrating analogue strain conditioning circuits and real-time microcontroller data acquisition.  The firmware converts ADC measurements from a Wheatstone bridge strain interface into calibrated strain values (με).
# STM32 Strain Interface and Embedded DAQ System


## Overview

This project demonstrates a STM32-based embedded strain sensing system integrating analogue strain conditioning circuits and real-time microcontroller data acquisition.
This open-source code was produced with the support/sponsorship of the UKRI-funded AVATAR project. Demo video here:  https://www.linkedin.com/feed/update/urn:li:activity:7425270364093599744/

The firmware converts ADC measurements from a Wheatstone bridge strain interface into calibrated strain values (με).


## System Architecture


Strain Gauge
      |
      |
Wheatstone Bridge Circuit
      |
      |
Analog Conditioning
      |
      |
STM32 ADC
      |
      |
Embedded Calibration Algorithm
      |
      |
Microstrain Output


## Hardware

MCU:
- STM32L476RG (Nucleo-L476RG)

Sensor:
- 350 Ω strain gauge

Interface:
- Wheatstone bridge strain conditioning circuit
For strain gauge amplifier and conditioning circuits details, please see/read paper:
"Guo, S.; West, A.; Papuga, J.; Theodossiades, S.; Jiang, J. Design of a Modularized IoT Multi-Functional Sensing System and Data Pipeline for Digital Twin-Oriented Real-Time Aircraft Structural Health Monitoring. Sensors 2025, 25, 6531. https://doi.org/10.3390/s25216531 "


## Firmware Features

- ADC acquisition
- Voltage-to-resistance conversion
- Strain calibration
- Gauge factor compensation
- Real-time microstrain calculation


## Application

Developed for embedded structural health monitoring systems.
